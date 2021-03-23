### what is Jenkins?

- Continous Integration/Continous Delivery
- Jenkins only focuses on CI part? not sure
- create Jenkins server, it polls the github repo for any changes
- if there are changes, it triggers a build, then sends to a testing server or prod server based on how you config

- ![ci/cd workflow](/img/CI_CD.png)

### Tutorials

- Techworld with Nana  
  https://www.youtube.com/playlist?list=PLy7NrYWoggjw_LIiDK1LXdNN82uYuuuiC
- Edureka Video  
  https://www.youtube.com/watch?v=p7-U1_E_j3w
-

### Features

- 5 key areas
- easy installation
- easy configuration
- plugins
- extensible
- distributed

### Pipeline

- committing code to a server(github)
- Jenkins Builds
- runs tests
- everything passes -> release ready environment
- deploy deliver
- to production

![pipeline](/img/pipeline.png)

### Architecture

- github -> Jenkins(CI server) -> Maven(build) -> Selenium(test) -> prod server
  ![arch ex](/img/jenkins-arch.png)

### Master/Slave Architecture

- when you have multiple code builds
- Jenkins doesnt allow for that so you can use M/S arch
  ![master slave](/img/jenkins-master:slave.png)
