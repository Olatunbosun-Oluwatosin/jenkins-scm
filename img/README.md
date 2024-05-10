## Jenkins Pipeline Job

### _My First Job_
![](./01.%20jenkins-job.png)

### _Webhook configured on github_
![](./02.%20github-webhook.png)
Webhook configured successfully on github using the ip address of the jenkins server. I also ensure to update the IP address whenever the server is restarted due to change in the ip address.

### _Jenkins job triggered_
![](./03.%20job-triggered-automatically.png)
The webhook configured on github is not all that is needed, while configuring the job i also ensure to check the the webhook github during the setup stage. This enables the jenkins job to run automatically whenever any changes is made to github which act as the source-code.
### _Jenkins pipeline script_
![](./04.%20pipeline-script.png)

### _docker script_
![](./05.docker-script.png)
An executable file name docker.sh was created to contain the script.

### _docker image install_
![](./06.%20docker-installed.png)
Docker was installed successfully and running(active) as seen in the image using the dicker script provided in the manual.

### _Jenkins pipeline job completed_
![](./07.%20pipeline-job-completed.png)
The pipeline job was completed after 5th trial. This gives me the insight into what i did wrong which i needed to adjust to arrive at the appropriate setup to have the needed result.

### _index.html content page_
![](./8.%20congratulation-page.png)
The jenkins server now serving us with the content in the index.html


Thank you!!