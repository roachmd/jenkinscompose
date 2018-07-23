## A compose file for jenkins/jenkins:lts

---
Reason: 

``` Well, taking a refresher course on jenkins.  
I find now... I really really hate the old school of actually installing software.
Actually, I also hate writing dockerfiles at this point in history 
So, via the glory of docker hub i'm using /.jenkins:lts
```

### Directory structure
---
* jenkins_home mounts to internal /var/jenkins_home
* backups goes in jenkins_home/backup {{ Using thin_backup or baskups }} 

``` .
├── README.MD
├── docker-compose.yaml
└── jenkins_home
    └── backup
```

