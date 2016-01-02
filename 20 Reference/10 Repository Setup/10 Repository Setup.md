# Repository Setup

While working on your problem definition, you can start creating your development environment. If
you have not done so already, you should setup **git** to share your code with the teaching staff on
a daily basis.

> You should put all of your code in a subfolder in your GitHub repository, separate from the **README.md** etc.

## Creating a project inside your existing repository

Your repository is required to be neat and tidy througout the course. It will contain various
documents but also the code of your project. To make sure the repository does indeed stay tidy,
follow these instructions.

For *Android Studio*:

- make sure you have created your repository as per the instructions
- make sure Android Studio is fully up-to-date
- install and start Android Studio
- close any open projects
- create a new project
  ![](android-start.png)
- choose an appropriate project name (you can't change this later!)
- give your project a *domain* in inverse order: nl.mprog (or anything appropriate)
- then, as your *project location* choose the folder that is the root of your repository
- now, choose an appropriate type of project and create it
- finally, choose *Add Root* in this popup:
  ![](android-add.png)

For *Xcode*:

- make sure you have created your repository as per the instructions
- make sure Xcode is fully up-to-date
- install and start Xcode
- close any open projects
- create a "New Xcode Project"
- choose an appropriate template for your project
- choose an appropriate product name (you can't change this later!)
- give your project an *organization identifier* in inverse order: nl.mprog (or anything appropriate)
- choose Swift as your language and select *Next*
- then, as your project location choose the folder that is the root of your repository

For a *D3 visualization* project:

- create a folder inside your repository that is named after your project
- create folders there for the kinds of source files you will have: **css** and **javascript** are likely candidates
- if your application will be implemented in one or only a few **html** files, simply put these in the project folder
- make sure there is a *main* html file that is called **index.html** with an empty `<body>` tag

Upon following these steps succesfully, you should be able to commit and push the new project to your GitHub repository. Make sure you do this before continuing.
