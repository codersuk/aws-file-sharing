
  
# Create a Simple File Sharing Web App
Today’s task is to create a simple wetransfer clone using AWS.

  

At the end of the session; you should as a minimum be able to upload files from your computer via a web page to Amazon S3, and return a download link. You can then use this commercially or add this to your portfolio.

  ## Tools

We will be using the following tools and framework:

 
1.  Reactjs/vuejs/meteorjs
2.  Amazon S3
3.  Amazon Lambda - Nodejs, lambda or php
4.  DynamoDB - this is optional

  

The general setup of this session is for you to try to set up the environment on your own and build up the script. This task should be completed within 2hours or so. For those who are fast, we have additional tasks such as adding the files’ information to a database. We have chosen DynamoDB to stick within the AWS environment so that it is easier for you to spin up and destroy these containers.

During the session you can ask the organiser for help or work in pairs to complete the tasks. Do not overcomplicate the task, keep it as simple as possible without fancy designs or additional bells and whistles.

  
## Steps
The steps are as follows:

  

1.  Create a front end app using any of your chosen framework (vuejs, reactjs, meteor, etc…). Create a simple SPA with an upload field and additional fields of your choice. Your aim is to be able to drag and drop the files or allow your page to select and upload multiple files online
2.  Create a nodejs/java lambda endpoint on AWS. Make sure the gateway API is configured so that it can read/write to an S3 bucket in the same region.

  

**Additional:**
The following are optional tasks

1.  Create a DynamoDB to add the file to the database. Run a cron job on a daily basis to delete anything that has expired after an amount of time.
2.  Create a way to delete the files using your SPA. Do not worry about authentication just yet.
3.  Create a deployment workflow using Claudiajs or Terraform to upload the files to AWS.
4.  Add restrictions in both frontend and backend to restrict certain types of files such as .exe, .docx, etc…

  

  

  

Make sure that your credentials are not published on Github or stored unsafely. Please also limit its usage and add a budget limit.

  

Resources:

[https://claudiajs.com/](https://claudiajs.com/)

[https://www.terraform.io/intro/index.html](https://www.terraform.io/intro/index.html)
