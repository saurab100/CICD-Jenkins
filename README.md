# CICD-Jenkins
1. Create a spring boot application
2. Go to dashboard and create a new item -> select freestyle project, now follow these: 
   ** source code management: Git -> give your git repo url
   ** Build Triggers: We have 5 options
   ** Build Steps: Invoke top=level Maven targets ==> clean compile test package
   ** Post-build Actions
3. Manage Jenkins -> plugins -> install build pipeline plugin
4. On Dashboard, ext to all we have a '+' sign, click on it to create a pipeline (We won't this option if pt 3 is not followed)
