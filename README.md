
  
# Create a Simple File Sharing Web App
Today’s task is to create a simple wetransfer clone using Firebase

  

At the end of the session; you should as a minimum be able to upload files from your computer via a web page to a cloud service, and return a download link. You can then use this commercially or add this to your portfolio.

  ## Tools

We will be using the following tools and framework:

 
1.  Reactjs/vuejs/meteorjs
2.  Firebase
3.  Firebase Admin-sdk - Nodejs
4.  Firebase Store/Storage/auth

  

The general setup of this session is for you to try to set up the environment on your own and build up the script. This task should be completed within 2hours or so. For those who are fast, we have additional tasks such as adding the files’ information to a database (noSQL).

We have chosen Firebase so that it is easier for you to spin a up a setup that can host your final product as well as store the code all in one SDK and cloud service. The Firebase cloud system is mostly a Baas (back end as a service.)

During the session you can ask the organiser for help or work in pairs to complete the tasks. Do not overcomplicate the task, keep it as simple as possible without fancy designs or additional bells and whistles.

  
## Steps
The steps are as follows:

  

1.  Create a front end app using any of your chosen framework (vuejs, reactjs, meteor, etc…). Create a simple SPA with an upload field and additional fields of your choice. Your aim is to be able to drag and drop the files or allow your page to select and upload multiple files online. You can use Axios or any other API to upload the files. If you want... you can even use the good ol' xmlhttprequest.

2. Add

  

**Additional:**
The following are optional tasks

1.  Create a Firebase Store to add the file details to the database. Run a cron job on a daily basis to delete anything that has expired after an amount of time. This can be done under firebase function.  [Guide](https://firebase.googleblog.com/2017/03/how-to-schedule-cron-jobs-with-cloud.html)
2.  Create a way to delete the files using your SPA. 
3.  Add restrictions in both frontend and backend to restrict certain types of files such as .exe, .docx, etc… using the rules under firebase store. It is very easy


  

Make sure that your credentials are not published on Github or stored unsafely. Please also limit its usage and add a budget limit.

  

Resources:

Signup to Firebase her:

[https://firebase.google.com/](https://firebase.google.com/)

Firebase Rules:

[https://firebase.google.com/docs/rules](https://firebase.google.com/docs/rules)

Firestore (database):

[https://firebase.google.com/docs/firestore/quickstart](https://firebase.google.com/docs/firestore/quickstart)


File Storage on firebase:

[https://firebase.google.com/docs/storage/web/start](https://firebase.google.com/docs/storage/web/start)

