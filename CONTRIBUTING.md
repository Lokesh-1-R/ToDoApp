# Contributing To ToDoApp

Thank you for considering contributing to ToDoApp! Please follow these guidelines to ensure smooth collaboration.

## Getting Started
**`Step 1 : Forking`**
- Fork this repository to your GitHub.
- Forking is a way to create a copy of the original repository under your GitHub account.
- This allows you to make changes without affecting the original repository.
- To fork the repository, navigate to the main page of the repository on GitHub, and click the **`Fork`** button in the top right corner.
- This action will create a copy of the repository under your GitHub account.

**`Step 2 : Cloning`**
- Clone the forked repository to your local machine.
- Cloning means downloading a copy of the repository to your local computer so that you can work on it.
  To clone the forked repository, open a terminal/command prompt and use the git clone command followed by the URL of your forked repository.
- It should look something like this `git clone https://github.com/ajjayymahato/ToDoApp.git`
- This command will create a local copy of the repository on your computer.

**`Step 3 : Branching`**
- Create a new branch for your work in your local system using below naming convention.
  - If contributing to frontend `git checkout -b frontend/MyFirstName/BirthdayDate/CityName`
  - If contributing to backend `git checkout -b backend/MyFirstName/BirthdayDate/CityName`
  - If contributing to fullstack `git checkout -b fullstack/MyFirstName/BirthdayDate/CityName`
  - Examples Are : 
    - `git checkout -b frontend/Ajay/23/NewDelhi`
    - `git checkout -b backend/Vijay/04/Chennai`
    - `git checkout -b fullstack/Preety/30/Bengaluru`
  - Keep city names and not state names to avoid duplicated branch names.
- If you want to contribute multiple times than make multiple branches with same strategy.

**`Step 4 : Writing Code`**
- Make your changes and write your code.

**`Step 5 : Pushing Code`**
- After doing all your code check which files to add using `git status` 
- To add all files `git add .`
- To add few files write space seprated `git add file1 file2 file3`
- And commit them `git commit -m "My ToDoApp Commit"`.
- Push the changes to your fork `git push origin frontend/myfirstname/birthdaydate/CityName`.
- Create a Pull Request (PR) to the original repository.
- The maintainers of the main repository can then review your changes, leave comments, and merge them if they approve.

## Folder Structure
Please adhere to the following naming convention for your project folders:

`<YourFirstName>-<birthdaydate>-<CityName>`
- Examples Are :
  - Ajay-23-NewDelhi
  - Vijay-04-Chennai
  - Preety-30-Bengaluru


```css
ToDoApp
├── frontend
│   ├── react
│   │   ├── MyFirstName-BirthdayDate-CityName
│   │   │   ├── src
│   │   │   ├── screenshots
│   │   │   ├── README.md
│   ├── angular
│   │   ├── ...
│   ├── vue
│   │   ├── ...
│   ├── bootstrap
│   │   ├── ...
├── backend
│   ├── springboot
│   │   ├── MyFirstName-BirthdayDate-CityName
│   │   │   ├── src
│   │   │   ├── screenshots
│   │   │   ├── README.md
│   ├── django
│   │   ├── ...
│   ├── flask
│   │   ├── ...
├── fullstack
│   ├── react-springboot
│   │   ├── MyFirstName-BirthdayDate-CityName
│   │   │   ├── frontend
│   │   │   ├── backend
│   │   │   ├── screenshots
│   │   │   ├── README.md
│   │   ├── MyFirstName-BirthdayDate-CityName
│   │   │   ├── frontend
│   │   │   ├── backend
│   │   │   ├── screenshots
│   │   │   ├── README.md
│   ├── angular-springboot
│   │   ├── ...
│   ├── react-django
│   │   ├── ...
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── README.md
```

In each project folder, create a README.md file with the following template:
```
# [Project Name]

- Author  : [Your Full Name]
- Location: [State, Country]

[Brief description of your project]

[Installation instructions, how to run, etc.]

```
Create a screenshots folder to add a screenshot of the frontend or backend apis

## Adding New Languages/Frameworks
If you want to add a language/framework not mentioned above, please create a folder in the appropriate category following the same naming convention.

## Code of Conduct
Please review and adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) to create an inclusive and respectful environment.


