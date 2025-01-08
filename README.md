## 1.Create a New Node.js Project:

- mkdir dev-env-setup
- cd dev-env-setup

## 2. Initialize Git

- git init

- git remote add origin https://github.com/gitsibi/backend-Dev-Environment-Setup.git

## 3. Initialize the Node.js Project

- npm init -y -> This command to create a package.json file

## 4.Install Required Packages

**Install the packages Express, Nodemon, Dotenv and Mongoose.**

- npm install express dotenv mongoose
- npm install --save-dev nodemon

## 5. Verify Package Installation

Open the package.json file and make sure the installed packages are listed under "dependencies" and "devDependencies".

## 6. Commit and Push Changes

- git add .
- git commit -m "Installed all packages"
- git branch -M main
- git push -u origin main