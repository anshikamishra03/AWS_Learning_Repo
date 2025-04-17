AWS Code Pipeline-

User --->AWS CodeCommit(AWS Managed Version Control system) ---> AWS Code PipeLine(Triggering the pipeline & takes responsibility of invoking CI and CD) ---> AWS Code build( invoke CI all continous steps) ---> AWS Code Deploy( takes part of deployment either on k8s or ec2)

Why use AWS Code Pipeline as it is pay as you use service where as there are different open source platforms?
1. For Jenkins we will use master slave archtitecture.(Managing will be done by devops engineer of jenkins architecture).
2. AWS know how to manage services.
