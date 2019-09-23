# TS Script Starter
Project template that configures a project for the execution of helper Node 
scripts written in typescript.

## Example Workflow & Usage (No NPM)
**Prerequisites:** Docker must be installed and on the path. 
1. Create a repository using this one as a template
2. Create a new Typescript script in the 'scripts' directory
3. Run the script using `./run scripts/<script_name>`

This will create a docker container for executing Node scripts, and execute
the requested Typescript script.

## Example Workflow & Usage (With NPM)
1. Create a repository using this one as a template
2. Create a new Typescript script in the 'scripts' directory
3. Run the script using `npm run --silent exec:ts scripts/<script_name>`
