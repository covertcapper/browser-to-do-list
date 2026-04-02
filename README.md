# Browser To-Do List
This is a simple browser based To-Do List application that can save user's inputted tasks locally as well as edit and delete them. 

![To-Do App screenshot](./images/2026-04-02_to-do-list-screenshot.png)

> I created this project using very little AI. I only used it to assist me if I absolutely could not solve a problem, and I never had it outright create the code for me. 

**Link to Project:** https://covertcapper.github.io/browser-to-do-list/

## How It's Made
**Tech used:** HTML, CSS, JavaScript.

Before beginning this project, I began by learning Git. Professionals in the programming industry told me that many beginners ignore doing this and that it was a good idea that I learned it early. After finishing a git course, I began a simple HTML review since I already had an understanding of how to use the language. I then spent just over a month doing a CSS course, and after that moved on to JS. While doing the JS course, I decided I wanted to start this project to try and change up my learning each day so I wouldn't get bored. I watched some different tutorials on building a simple to-do list app so I wasn't just copying code and tried to make mine my own. I found this difficult once it came to JS because I was still early in learning the language. I did my best to break it down though and at least try to understand how different elements were connecting to my HTML and what they were doing. I was able to edit the CSS to my liking more since I had a stronger understanding in this area. Still though, working on this project has shown me I still have a lot to learn. 

## Lessons Learned
- How to better use Flexbox when placing elements that need to resize in a container. 
- Slightly more of an understanding for practical JS uses as opposed to only doing simple exercises using functions, loops, etc. 
- The transition property in my css was affecting text when I optimized the app for smaller screens. The text was meant to shrink, and it would shrink slowly as if animated. A small nuance, but I figured out how to fix it anyways. 
- Learned how to create buttons with smooth animations when you hover and click. 
- Improved workflow when using git (cleaner commit messages, keeping "main" clean) and understanding how to commit within the terminal.
- Learned about using .gitignore.
- Had an issue where the text in each individual to-do list item was not wrapping and would spill outside of its container. I learned how to correct this with:
```
overflow-wrap: break-word; 
``` 
- I also learned how to use "flex: 1;" so that the text wouldn't push the edit and delete buttons out of the container.