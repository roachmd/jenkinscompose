## A compose file for jenkins/jenkins:lts

---
* Reason: *
Well, taking a refresher course on jenkins.  
I find that I really really hate the old school of actually installing software.
Actually, I also hate writing dockerfiles at this point in history 
The glory of docker hub.

### Directory structure
---
jenkins_home mounts to internal /var/jenkins_home
backup is for when you want to schedule backup outside docker image

``` .
├── README.MD
├── docker-compose.yaml
└── jenkins_home
    └── backup
```

