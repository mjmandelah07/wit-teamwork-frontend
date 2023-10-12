# Teamwork frontend

## Project Overview

Teamwork is an internal social network for employees of an organization. The goal of this
application is to facilitate more interaction between colleagues and promote team bonding.

**NOTE:**
The APIs used in this project was designed by Mjmandelah07 [https://github.com/mjmandelah07](https://github.com/mjmandelah07)

## Names and Github handles of contributors

1. Anna Isumonah Amuda

    * GitHub Handle amd Url: Isumonah | [https://github.com/Isumonah](https://github.com/Isumonah)
2. Nwakpa Chiamaka Flora

    * GitHub Handle amd Url: Flora-dot | [https://github.com/Flora-dot](https://github.com/Flora-dot)
3. Eke Stephanie Chinasa

    * GitHub Handle amd Url: ekestephanie1 | [https://github.com/ekestephanie1](https://github.com/ekestephanie1)

## Getting Started

Follow these steps to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have met the following requirements:

* Node.js: Make sure you have Node.js installed on your system. You can download it from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone the project repository to your local machine only if you are a collaborator:

    ```bash
   git clone https://github.com/mjmandelah07/wit-teamwork-frontend.git
    ```

2. Navigate to the project directory:

    ``` bash
    cd wit-teamwork-frontend
    ```

3. Install the project dependencies using npm:

    ```bash
    npm install
    ```

#### Usage

To start the Techsterverse Backend server, run the following command:

```bash
npm start
```

The server will start and be accessible at <http://localhost:3000> OR at the port specified in the .env file.

#### Configuration

You can configure the application by creating a .env file in the project root and specifying environment variables as needed. An example .env file is included in the project root to know which environment variables is required:

##### .env.example

```bash
PORT=3000
DATABASE_URL=postgres://localhost/
SECRET_KEY=mysecretkey
```

#### Contributing

Contributions are welcome! Feel free to open issues and submit pull requests to help improve this project.

### Before Starting Your Assigned Task

Before you begin working on your assigned task, follow these steps to ensure you are working on the correct branch and keep your codebase up-to-date:

1. Check the current git branch you are on using:

   ```bash
   git status
   ```

2. If you are on the master or main branch [NOTE: Check the branch name if it is master or main], it's essential to pull the latest changes from the remote repository and if not make sure to checkout to main or master branch before start a new task.

    * If you are on the master or main branch.

        ```bash
        git pull origin master or main
        ```

    * If you are not on master or main branch. Git checkout to master or main before git pull.

        ```bash
        git checkout master or main
        git pull origin master or main
        ```

3. Create a new branch for your task by running the following command. Replace branch-name with the name of the task you are assigned to for the first time. If the branch already exists, skip this step:

    ```bash
    git checkout -b branch-name
    ```

    * If the branch already exists, switch to that branch using:

        ```bash
        git checkout branch-name
        ```

### Working on Your Task

After ensuring you are on the correct branch, you can proceed with writing code and installing dependencies for your assigned task.

```bash
git status
```

### Completing Your Task

Once you have completed your task, follow these steps to commit your changes:

1. Add your changes to the staging area:

    ```bash
    git add .
    ```

2. Commit your changes with a descriptive message:

    ```bash
    git commit -m "Add a concise commit message here"
    ```

3. Push your changes to the remote repository. Replace branch-name with the name of the branch you created for your task:

    ```bash
    git push origin branch-name
    ```

### Submitting Your Changes

After pushing your changes, go to the repository on your Git hosting platform (e.g., GitHub) and create a pull request for your commit or branch. Submit the pull request link to the team lead or designated reviewers for inspection and approval.

### License

This project is licensed under the ISC License - see the LICENSE file for details.
