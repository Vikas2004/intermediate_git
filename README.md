# intermediate_git
This repository is created to explain about:  
1. Branching
1. Workflow 
1. Merge conflicts

## Group Members

1. Krishna Sumanth Koyyalamudi

2. Gopichand Bandarupalli

3. Vikas Baswapuram

4. Harish Thadka

* **BRANCHES**:

  * A Branch in github represents another copy of the master branch(made at that point of time).
  * A Branch is used to work with different versions of a repository at a same time.
  * By default a repository has a master branch otherwise called as production branch.
  * New branches are generally created for bug fixes and feature work seperate from the master branch.
  * When changes are ready, they can be merged into the master branch. If you make changes to the master branch while working on a new branch these updates can be pulled in.  
Source obtained from [here](https://www.w3schools.com/whatis/whatis_github.asp)
   
 * **WORKFLOW**:
  
    * Workflows are custom automated processes that you can set up in your repository to build, test, package, release, or deploy any project on GitHub.
    * With workflows you can automate your software development life cycle with a wide range of tools and services. 
    * You can create more than one workflow in a repository. You must store workflows in the .github/workflows directory in the root of your repository.
    * You can configure a workflow to start when a GitHub event occurs, on a schedule, or from an external event.
    * You need to configure workflows using YAML syntax, and save them as workflow files in your repository. Once you've successfully created a YAML workflow file and triggered the workflow, you will see the build logs, tests results, artifacts, and statuses for each step of your workflow.  
Source obtained from [here](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/configuring-a-workflow#about-workflows)  
Use the [Workflow syntax for GitHub Actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions) reference documentation to choose events to trigger an action, add actions, and customize your workflow.

* **Merge Conflicts**:

    * The Merge pull request button is deactivated unyil you've resolved all conflicts between the compare branch and base branch.
    * Merge conflicts happen when you merge branches that have competing commis, and Git needs your help to decide which changes to incorporate in the final merge.
    * Git can often resolve differences between branches and merge them automatically.
    * Often, merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file.
    * You can view a list of the files with conflicting changes above the Merge Pull request button.
    * The merge pull request button is deactivated until you've resolved all conflicts between the compare branch and base branch.  
Source obtained from [here](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-merge-conflicts)




