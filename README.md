# The first pipeline

<!-- This is just some test code -->

## Create Python File
- create a file called: `hello_world.py`
- add code to the file that prints like "Hello World!"
- commit and push your changes to your GitHub repo

## Create GitHub Workflow
- create a new file at `.github/workflows/main.yml`
- use the following [example](.github/workflows/main.yml)

> [!NOTE]  
> Push the python file first, then push the main.yml file

> [!TIP]
> if the pipeline doesn't start automatically, make a small change to your README.md file and push again

## Watch Pipeline
- go to your repository on the GitHub website
- lick on the "Actions" tab
- You should see your workflow "My First Pipeline" in the list
- click on the job "run-python" to see individual steps

## Check Results
- in the "Run Python script" step, you should see the output you defined in the python script
- if everything worked correctly, the workflow will show a green checkmark
