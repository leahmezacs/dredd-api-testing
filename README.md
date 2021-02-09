# Setup 
> I know it can be difficult, so stop me anytime if you have questions. These commands can be done on a mac or linux machine.

## Step 1: Git
> Open up your terminal to a desired directory for this project. 

Enter the following command, replacing leah with your name:

`mkdir leah-api-testing` [this creates a directory] 

Validate whether you have git installed:

`git --version` [if it returns nothing, you need to install git]

- If you dont have git installed:
  - [download git instructions](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

- If you do have git installed, enter: 
  - `git clone https://github.com/leahmezacs/dredd-api-testing.git` [the readme.md will now download to your directory]

## Step 2: Node.js
> We will use a version manager to control the versions on node on our machines. 

1. Check if node and npm are already installed:
   
`node -v` [if it returns nothing, you need to install node - see #2]

`npm -v` [if it returns nothing, you need to install npm - see #3]

2. [Download NVM (Node Version Manager)](https://github.com/nvm-sh/nvm#git-install).

3. Use NVM to download version on node and npm:

`nvm install 12.20.1` [installs node version 12.20.1]

`nvm use 12.20.1` [node version for local directory]

`npm install -g npm` [install npm]

## Step 3: Dredd
> In the same directory, we will install dredd and configure framework.

#### Dredd Documentation: https://www.npmjs.com/package/dredd/v/11.2.19

`npm install -g dredd` [install [dredd]()]
`dredd --version` [check if it installed correctly]
`dredd init` [interactive configuration]

## Step 4: Runnning Tests
Just run `dredd` to run the tests.
