# 01 Arguing Semantics

## Objective
In this challenge the objectives are as following.
* Change div property to semantic language.
* Adjust corresponding CSS.
* Submit clear README file with deployed challenge link of operational web application.

NOTE: Please make necessary changes to the documents provided so the code is cleaner but still fully operational.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes Made
In this challenge I read through the README file and established what was being asked through the acceptance criteria. I went through the index.html changing the div tags to semantic elements utilizing header, aside, section, footer, nav, etc. Following adding semantic language it affected the CSS. With that being said the changes made in HTML then needed to reflect those same changes to operate correctly, especially with adding nav to retain the navigation option in the app. Redundancies of repeated code and measurements were found in the CSS. Those were then consolidated into groups in an attempt to NOT repeat unnecessary code. Final task was to deploy the web application to a live link, attach link to updated README file. Goal was to clean up the code, have a fully operational web application, and make it user friendly.

## Screenshots
* ![Alt text](<Screenshot 2023-06-14 at 12.04.10 PM.png>)
* ![Alt text](<Screenshot 2023-06-14 at 12.04.20 PM.png>)
* ![Alt text](<Screenshot 2023-06-14 at 12.04.26 PM.png>)

## Final Submissions
* https://jiujitsucarrot.github.io/challenge-1/
* https://github.com/jiujitsucarrot/challenge-1

## Mock-Up

The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./Assets/01-html-css-git-homework-demo.png)

> **Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. Eventually you'll learn how to make elements responsive so that your web application is optimized for any screen size.

## Getting Started

Follow these instructions to create your project and deploy it to GitHub Pages:

1. Create a new repository on your GitHub account and clone it to your computer.

2. When you're ready to deploy, use the `git add`, `git commit`, and `git push` commands to save and push your code to your GitHub repository.

3. Navigate to your GitHub repository in the browser and then select the Settings tab on the right side of the page.

4. On the Settings page, scroll down to the GitHub Pages section. Then, in the section labeled Source, select the `main` branch as your source.

5. Navigate to <your-github-username.github.io/your-repository-name> and you will find that your new webpage has gone live! For example, if your GitHub username is "lernantino" and the project is "css-demo-site", then your URL would be <lernantino.github.io/css-demo-site>.

You can also refer to this [YouTube video on enabling GitHub Pages](https://youtu.be/P4Mu1t5rIXg) for more guidance.

> **Important**: It might take a few minutes for GitHub pages to display your site correctly. If your project does not deploy or display correctly, check that all file paths in your application are relative and use the right casing. GitHub is case-sensitive, an inccorect capital or lowercase letter could cause problems in deployment.

Be sure to add, commit, and push your work to see the most up-to-date version of your app!

## Grading Requirements

> **Note**: If a Challenge assignment submission is marked as “0”, it is considered incomplete and will not count towards your graduation requirements. Examples of incomplete submissions include the following:
>
> * A repository that has no code
>
> * A repository that includes a unique name but nothing else
>
> * A repository that includes only a README file but nothing else
>
> * A repository that only includes starter code

This Challenge is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following code improvements:

  * Application's links all function correctly.

  * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

  * Application's CSS file is properly commented.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Application Quality: 15%

* Application resembles mock-up provided in the Challenge instructions (at least 90%).

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository, with a unique name and a README that describes the project.

---
© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
