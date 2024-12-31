Date: 27th of December

Project Title: Frontend Mentor Bento Grid

This README file is a personal note to self to record the things I learnt, found challenging, and problems I am yet to solve so I can revisit in future for reference purposes.

Difficulty:
1. Working with Grids
I like working with Grids. In fact, in situations where you have to pick between using a grid or flexbox I will prefer using grids due to how definite it is; it places items exactly where you want as long as you get the code right.

The difficulty arises when the design is something complex that has a lot of distinct parts and the child element's content are not the same like this project. Each item in the grid has it's own unique design/content so getting them to behave the same was difficult.

The upside to this difficulty is that it required me to have a lot of control over every child element and dictate exactly how I want each item to behave. This led to writing large and complex code that led to mistakes(bugs).

I never liked writing large complex code. I like code that is concise and short over long lines of code. This preference was re-enforced when I read a line in the book I am currently reading: "A large program is a costly program, and not just because of the time it takes to build. Size almost always involves complexity, and complexity confuses programmers. Confused programmers, in turn, introduce mistakes (bugs) into programs. A large program then provides a lot of space for these bugs to hide, making them hard to find".

But maybe this is what the practice required; to test your ability to use grids with items that required a lot of control. But I plan to revisit the project again and refine the code to see if I can achieve the same result with less code and complexity.

2. 100vh height
Another difficulty I faced was getting the grid to fit the viewport height without the need to scroll vertically. I don't know if this was the solution, but I was able to get the grid to fit the screen by reducing the size of elements in the child items. I reduced the font-sizes, h1s, and image sizes so the grid was compact and fit the screen perfectly without the user having to scroll up or down when using a laptop or desktop. 

Lesson Learnt:
1. The complexity of working with the individual items in the grid thought me a lot on the capabilities and features of CSS grid, and it's a lesson that will make solving other grid problems that are not as complex as this easy.

Snapshots:

Desktop screensize:

<img src="assets/Screenshots/Desktop.png">

Tablet screensize. The assignment didn't provide an example of how tablet screensize should look like so I had to improvise and come up with a concept myself. Having the same design for mobile and tablet didn't look good.

<img src="assets/Screenshots/Tablet.png">

Mobile screensize:

<img src="assets/Screenshots/Mobile2.png">