# activiti-process-services-helm
Helm chart sources for the alfresco process services
<br>Usage:
<br>helm install --debug --name=aps activiti-process-services-helm
<br>In case if helm repository is used 
1. First is to add repository
<br> helm repo add almerico https://almerico.github.com/helmrepo/
2. then install
<br>helm install almerico/aps --name=aps
<br>
<br>
In case if Jenkins X is used
<br>
Simply add 
<br>
```
  - name: aps
    repository: https://almerico.github.com/helmrepo
    version: 0.1.0
```
