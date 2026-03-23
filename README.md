# Open Source Exploration: Draw.io (diagrams.net)

## 1.Project Overview

Draw.io is an open-source diagramming and whiteboarding tool that lets users create flowcharts, UML diagrams, network diagrams, and other visual representations.

### What does the software do?
It has a web-based and offline tool for making diagrams with parts that you can drag and drop.

### What problem does it solve?
Draw.io makes making diagrams easier by giving you an easy-to-use interface and a lot of pre-made shapes and templates.

### Who would typically use it?
- Students (flowcharts,project diagrams)
- Software developers (UML diagrams,system design)
- Business professionals (process flows,presentations)

## 2. Repository Structure

The repository contains several important folders:

- **src/**  
  This file has the main source code for the app, which includes the UI components and the core logic.
  
- **docs/**  
  Files that explain features, how to use them, and rules for developers.
  
- **test/**  
  The repository does not follow a traditional testing structure with a dedicated `tests/` folder. Testing is handled differently or within specific parts of the project.

- **webapp/**  
  Contains files related to the web version of the application, including HTML, CSS, and JavaScript.

- **build/**  
  Scripts and settings that are used to make and package the app. 

## 3. Technologies Used

**Programming Languages:**  
  JavaScript, HTML, CSS

**Libraries/Frameworks:**  
  - mxGraph (core diagramming engine)

**Build Tools:**  
  - Node.js
  - npm

**Other Tools:**  
  - Git for version control

## 4. Contribution Workflow

**Code of Conduct:**  
  The repository includes a Code of Conduct based on the Contributor Covenant, which defines expected behavior such as respectful communication and inclusivity within the community.

**Issues:**  
  Even though direct code contributions are not accepted, issues are still used by the community to report bugs, suggest features, and provide feedback. (Issue tracker)

**Pull Requests:**  
  The project explicitly does not accept pull requests. Development is handled internally by the core team.

**Community Interaction:**  
  Contributors mainly participate by raising issues and engaging in discussions rather than directly modifying the codebase.

## 5. Something Interesting I Noticed

I selected this repository because I have used similar websites before to create diagrams. I was interested to see how it worked internally.

What I found interesting about this project is that it does not follow the clean, minimal structure that I expected to see within a smaller repository. Initially, it was a little overwhelming, but after working my way through it, I could see why it's complicated.
