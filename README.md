# Skill up with Microsoft Power Platform and GitHub
#
# BuildLab2023


1. We change some source code .
2. Push that source code control into an environment .
3. Build a low code app and use the code-based control.
4. Run a workflow in GitHub to promote the changes from the developer environment to your test environment and understand the difference between managed and unmanaged solutions.


## **As a prerequisite, you will need:**
1. A GitHub Account.
2. Microsoft Power Platform Developer Plan ([link](https://powerapps.microsoft.com/en-us/developerplan/))
3. Azure portal access using AAD account to be used for this lab.

## **Items to be provisioned:**
1) Developer environment (using Developer Plan)
2) Test environment (using Developer Plan)
3) App registration in Azure AD and create the APP ID and Client ID and the SECRET (this is required for the workflow; use Setup page to review how to get these)

We will need to provide the ability to clone GitHub repository with all modifications for the PCF control.

## **What is expected out of this lab?**

The expectation of this lab is as follows: 
Understand the few of the code first capabilities available in Power Platform and how can code first developers work with Power Platform using their existing tools. We will go through a set of tools that are familiar to developers and a few concepts that are unfamiliar to developers. We will also experience how to develop and deploy low code applications using a continuous integration/continuous delivery paradigm. The intent of this lab is to do everything over the web and not have install any components on the local workstation, but you will have step by 
step instructions on how to proceed and become productive with your existing developer skills with low code platforms.

We will learn how to deploy low code applications with code first components and how to stage them from Development, to QA to Production. 

**We will:**
1. Use codespace and build a PCF control.
2. Push it into a DEV environment.
3. Add the PCF control to an app.
4. Export the new app with PCF control to GitHub.
5. Have a GitHub workflow to deploy from Dev to Test.
