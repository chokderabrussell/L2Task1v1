QA Automation Tutorial Level 2
======================================================================

>> Description:
These are solution to tasks carried out to learn QA 
Automation on websites in Level 2 trained by a1qa.

>> Requirements:
IDE: Intellij IDEa Community Edition
Programming Language: Java
Testing library: TestNG

To work with browser/elements of pages you should use
Selenium WebDriver library.
Test should be working with Chrome browser.

1. You should use WebDriverManager in your solution.
2. PageObject pattern should be used in your solution (i.e.
   all of the actions with elements from page should be described
   in that page's class).
3. Locators should be: (i) Stable (ii)Precise (iii) Easy to read
   (iv) Doesn't have redundant parts.
4. Singleton pattern should be used in your solution.
5. Some parts of auto test should be separated into pre- and 
   post- conditions
6. Test data and config data should be stored separately, to work
   with them you'll need to create a utility class. For storing
   this data you should use either XML or JSON. 
7. Explicit wait should be used as principal wait type.
8. BaseForm class should be implemented in your solution and
   used as a parent class for all forms and pages.

>> How to use it?:
The whole project consists of main branch with each 
new branches extending out when a new task is added
along with fix of the previous tasks.

All important files are uploaded in the repository.
It has to be a quickstart Maven project. The pom file
is given in the commits which includes details of all
dependencies, plugins, etc. necessary for the maven 
project.

>> Task 1
Subject: Practical application of Git-related skills on example
of GitHub + IDE
Difficulty level: Medium
Time estimate: 8h

Task description
Precondition: Init repo
1 Create a private repo, add README.md, .gitignore (with a pattern
  for your programming language) when creating a repo.
  Navigate to commit history, check that "initial commit" is 
  present.

2 Set up branch deletion after Pul Request (PR) is merged.

3 Grant an access to the repository to the reviewer (collaborators
  tab).

4 Clone a project in your IDE.

>> Credits
Training organisation: a1qa
Trainer: Aleksey Samchuk

Other sources used:
1 https://www.youtube.com/watch?v=RyzmpTBEYDw
2 https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/