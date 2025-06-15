# Easy access Instructions For ReadMe

4. README Documentation
Create a README file in your repository that includes:
An overview of the project and the chosen Frontend Mentor challenge.
A description of your approach and any customizations made.
Any challenges faced during implementation and how they were addressed.
5. Reflection
Write a brief reflection (100-200 words) discussing:
Challenges you encountered during the project.
Your approach to solving these challenges.
Improvements you would make if given more time.

# Question Answers

## Chosen project
- Bento grid challenge found on frontend
- url: https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj

## Challenges faced
- The biggest challenge faced with this assignment was trying to arrange the grid as seen in the preview using bootstrap.  I could not find a way to intuitively stretch column items to reach multiple rows, despite trying multiple ways without using too many divs (I think I have trauma now from using so many divs and trying to track them all).  To solve this, I spent around an hour googling bootstrap and reading documentation before coming across an answer on stack overflow, and ended up solving both the grid layout and order change from mobile to desktop by grouping everything into rows and nested columns, with order functionality from bootstrap.  This was excerbated moreso by not understanding that nested columns become their own grid systems, which I did my best to fix at the end through more testing/eyeballing the way the grid looks and different ratio of columns with one another.
- Another challenge faced was not having access to figma files as frontend mentor pro is required for those.  I ended up having to eyeball and test a lot of different sizes to eventually get the grid to fit as needed.  This involved adjusting image sizes and positions, text sizes and such and constantly double-checking against the preview.
- Bootstrap does not give many options for adjust images in the way I needed to for this assignment, but I was able to get the desktop images to match close enough to the preview messing around with css.
- I had issues with getting proper vertical gaps and sizing on the left column, which I solved by swapping to d-flex and using flex-fill and gap features to help fix the layout

- ## If given more time: 
- The biggest thing remains the sizing of the central column.  I would like to find or work on a solution that requires less divs and more fine-tunable elements that would allow me to better control it's size, allowing for better fitting of elements within the column.  
