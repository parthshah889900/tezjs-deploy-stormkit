# Deploy to Stormkit
In this guide, you will learn how to deploy your TezJs Site to  Stormkit.

## Deployed Url:
https://chillcandy-daow1t--66964838116263.stormkit.dev/

## Preparing for deployment:
Run the following command to create tezjs project:
  - `npm create tez@latest`
  - `cd [projectName]`
  - `npm install` - for installing the required dependencies
  - `npm run build` - for build the project
  - `npm run dev` - for run the project

## Pre-requisites:
  - Need a Stormkit account.
  - To deploy your Tezjs project, make sure it has been pushed to a Git repository.

## Deploying your Tezjs project to Stormkit:
  Go to Stormkit dashboard for creating project: https://www.stormkit.io/
1. Create a new project in Stormkit.
2. Import your git repository while creating that project.
3. Give the build command - `npm run build`
4. Give the build folder name - `dist`
5. Click on the button: `Deploy Now`

## References:
- [Stormkit Docs](https://www.stormkit.io/docs)
- [Stormkit Deployments](https://www.stormkit.io/docs/deployments)
