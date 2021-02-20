# macOS Installers for Jenkins LTS 

## Homebrew Installer

Sample commands:

Install the latest LTS version: `brew install jenkins-lts`

Install a specific LTS version: `brew install jenkins-lts@YOUR_VERSION`

Start the Jenkins service: `brew services start jenkins-lts`

Restart the Jenkins service: `brew services restart jenkins-lts`

Update the Jenkins version: `brew upgrade jenkins-lts`

Change port: 
```
vi /usr/local/Cellar/jenkins-lts/2.222.1/homebrew.mxcl.jenkins-lts.plist

```


Ref: https://jenkins.io/download/lts/macos/