# Intro
Welcome to the assessment! 

You have 1 hour to complete the assessment. Please use a timer make sure you stay within that alloted time range. While you may feel pressure to complete all the problems, you do not have to complete everything! Complete as much as you can within the allotted time frame.

## Prerequisites

```
nvm
node v24.11.0
VSCode
git
Google Chrome
```

### Installing NVM and Node
```shell
# Installing NVM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# Installing and using Node v24.11.0
nvm install v24.11.0
nvm use v24.11.0
```

### Installing VSCode
```shell
https://code.visualstudio.com/download
```
NOTE: You may also use your IDE of choice if VSCode is not your preference


### Git
```shell
https://git-scm.com/install/

```

# Assessment
View the problems at [ASSESSMENT.md](./ASSESSMENT.md)

## Running the tests
The commands to run the specific have already been bundled to run against the chromium browser
```shell
# Runs all the tests
npm run test 

# Runs just the API tests
npm run test:api

# Runs just the E2E tests
npm run test:e2e
```

# Rules
1. Clone this repo
2. Check out a git branch with your name first name + last initial
3. Push this branch up to the same repository
    * Regardless of how many problems you have completed, push up the branch at the end of the 1 hour period
4. Email a link to your branch to the recruiter in contact

NOTE: Your branch **will be deleted** at the end of the interview process
