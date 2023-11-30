# Setting up git commands.

git config is used to confgure our git setting, we use it to set up our username and email, it has 3 parameters --global for global .config file, --local for the local repository and --system for the system rether than the repository

`$ git config --global user.name "John Doe"`
`$ git config --global user.email johndoe@example.com`

git init is used to set up a local git repository.
`$ git init` 

When you initialize a Git repository using the `git init` command, you can specify various options to customize the initialization process. Here are some of the common options:

## Set the Initial Branch Name:

Specify the name of the initial branch (default is "master").
`$ git init -b <branch_name>`
## Specify the Shared Repository Mode:

Set the shared repository mode, allowing multiple users to push into the repository.
`$ git init --shared[=<permissions>]`