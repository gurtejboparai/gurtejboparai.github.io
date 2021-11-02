## Host your resume on Github Pages
------------
### Purpose
To explain how to host a resume on Github Pages and reflect on some key principals and tools in technical communication.

### Prerequistes
You will need the following:
1) Resume
   - You will need an up-to-date resume in markdown format
   - For markdown tutorial, go to [More Resources](#more-resources)
2) Github account
   - Create a new Github account if you don't have one
3) Markdown editor
   - You will need a markdown editor to edit your resume in markdown format
   - You can find a link to an article naming the best markdown editors in [More Resources](#more-resources)
  
### Instructions
#### 1) Create a new repository in your Github account
To host our resume, we will use a Distibuted Version Control system(DVCS) such as Git. Andrew Etter in his book _Modern Technical Writing_, mentions that DVCS have better performance, allow online work and are superior for concurrent work on the same file. Github is a great web-based inteface for managing Git repositories. 
- Log in to your Github account
- Click on `New` next to repositories in top left
- Fill in the name for your repository in the standard format: `username.github.io`. Note: use the same username as your Github account's username
- Make sure `Public` is checked so that anyone with the link can acess your website
- Click on `Create repository` to create the repository
![NewRepository](newRepository.gif)  

#### 2) Write your resume in markdown format
In relation to markdown, Etter talks about the popularity of markdown and the fact that it has the cleanest syntax. Moreover, one can easily learn how to write in markdown format within ten minutes. A link to markdown tutorial can be found in [More Resources](#more-resources).
- Write your current resume in markdown fomat using a markdown editor
- Save your resume as `index.md`
#### 3) Upload your resume file to Github repository
Github is mainly designed for software development, that's why developers prefer to use it. Etter acknowledges the fact that Github (Git) has a very high funtionality that is not even needed for a typical documentation workflow. But he still insists to use it because it is a modern tool. Therefore, if you do not use Git, you are basically confessing to potential contributors that you can't be bothered to use modern tools. 
- Click on `uploading an existing file` under `Quick setup` in your repository
- Upload your resume named as `index.md` to your repository
- Click on `Commit changes` to save your file
#### 4) Select a Jekyll theme for your website
Jekyll is a static site generator that will help you to add a theme (templated HTML and CSS) to your website. Jekyll is very popular to use to create a beautiful, functional documentation website. Etter in his book, suggests to take the time to customize the theme. He goes on to mention that customization is your chance to differentiate your content from the thousands of ugly and disorganized sites on the internet. 
- Click on `Settings` inside your repository
- Scroll down to `Github Pages` section at the bottom of the page
- Click on `Check it out here!` to open Github pages tab
- Click on `Choose a theme` under `Theme Chooser`
- Choose any given theme and click on `Select theme`  
- Click on `Commit changes` to save your changes
![ChangeTheme](changeTheme.gif)

#### 5) View your website
Etter emphasizes on the importance to build and host a website for your resume instead of distributing PDFs. Because eventually, PDFs will go out of date and you can never update them once they get downloaded in someone else's hard drive. Another benefit of hosting your content online is the power to fix inaccuracies instantly and keep your content in sync with the latest events.
- Go the link you chose as your reposiroty name `username.github.io` in your browser
- Keep refreshing the tab if you don't see your resume, it might take some time
- Hurray!! success
![MySite](mySite.gif)

### More Resources

- **Markdown Tutorial:** https://www.markdowntutorial.com/  
- **Markdown Editors:** https://www.oberlo.ca/blog/markdown-editors  
- **Mordern Technical Writing by Andrew Etter:** https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS 

### Authors and Acknowledgements
**Author:** [Gurtej Boparai](https://github.com/gurtejboparai)  
**Group Members:** Dean Pistorius, Tim Appleyard, Jordan Unger and Yucong Nie  
I would like to thank my group members for helping me with this project.

### FAQs
1) Why is Markdown better than a word processor?
   - Markdown is better than word because it is free and superior in every meaningful way. Moreover, Markdown is a popular choice and fine choice for simple web-based help systems.
2) Why is my resume not showing up?
   - Sometimes it might take a few minutes to show your resume on Github Pages. Keep refreshing the tab until you see your resume. 
   






