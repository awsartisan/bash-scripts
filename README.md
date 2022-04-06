# bash-scripts
A collection of bash scripts


## create-git-credentials-codecommit

This script creates an IAM user, assigns it HTTPS git credentials for CodeCommit (if you change the --service-name flag, this could also be used for CodeBuild) and then saves the username and password to shell variables.

## install-jenkins

This script installs Jenkins on an AmazonLinux host and updates iptables to forward the default port (8080) to 80. It also installs a couple of Jenkins plugins.
