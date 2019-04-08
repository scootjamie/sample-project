# Sample Project

This project is a sample template which can be cloned to initialize a Scoot dev project. 

The sample code used here has been cloned from the [ NGINX Hello World Demo ]( https://github.com/nginxinc/NGINX-Demos/tree/master/nginx-hello )

Projects using the schema expressed in this sample template may easily use the standardized Build, Push, and Deploy jobs available in Jenkins.

## Schema:

```
<files>
deploy/
-- Dockerfile  # Used for build and push operations
-- deploy.yml  # Used to deploy to kubernetes
```



