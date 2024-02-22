# 🚀 Git Commit Patterns Standardization for Games Development
<a href="https://github.com/Ayslan-gamedev/Gamedev_Commitzen/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ayslan-gamedev/Gamedev_Commitzen?color=blue&style=flat-square"></a>

This repository creates an automatic way to write automatically organized commits through git commands, using a commit patter to game development repositories for more descriptive and informative commit messages.

## ⚙️ Initial Setup

  Follow the steps below to set up and start using this commit pattern in your project:
  
  ### 1. Make sure you already have node.js installed on your machine.
  
  If you don't have Node.js installed yet, install in [nodejs.org](https://nodejs.org/en)
  
  ### 2. Start the repository and enter the following commands to install dependencies into the repository:

    npm init
    npm install --save-dev commitizen cz-customizable

  ### 3. Extract the files released in this repository
  
  ### 4. Then move the “.czrc” and “.cz-config.js” files to the root of the repository.
  
  ### 5. write the following lines in your .gitignore file:
    # Node Modules (commitzen dependencies)
    /node_modules/
    
    # CommitzenConfiguration
    .czrc
    .cz-config.js
    package.json
    package-lock.json
    cz-config.js
  
  ### 6. Update the package.json
  Write the item below inside "package.json":

     "scripts": {
       "test": "echo \"Error: no test specified\" && exit 1",
       "commit": "npx git-cz"
     }
     
  Now, you're ready to start using the commit pattern! use “npx git-cz” to commit

## 🛠️ How to Use
To create commits following this pattern, follow these steps:

Run the custom commit command:

    npx git-cz
    
You will be presented with a series of interactive questions. Fill in the requested information, such as the commit type, a concise description, and optionally a more detailed body.
After answering the questions, the commit will be automatically generated with the proper formatting.
you can read the commit instructions at: [Git Commit Standardization for Games Development](https://instal-entretenimento-org.github.io/)
