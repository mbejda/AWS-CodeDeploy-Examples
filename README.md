# AWS-CodeDeploy-Examples
**CD into Agent Work Directory**
```shell
cd /opt/codedeploy-agent/deployment-root/$DEPLOYMENT_GROUP_ID/$DEPLOYMENT_ID/deployment-archive
```


**CD into Agent Work Directory and download NPM dependencies, Bower dependencies and grunt build.**
```shell
cd /opt/codedeploy-agent/deployment-root/$DEPLOYMENT_GROUP_ID/$DEPLOYMENT_ID/deployment-archive
npm install
bower install --config.interactive=false --allow-root
grunt build
```
