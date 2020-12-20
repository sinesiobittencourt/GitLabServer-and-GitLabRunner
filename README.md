# GitLabServer-and-GitLabRunner
How to install GitLab and configure a CI/CD Runner


>> Command: docker-compose up -d


Configured runners apply the URL and the registration token needed to configure one.

We return to the terminal and install the runner in two steps, the first will generate the configuration volume based on the token:

>> Command: gitlab-runner register
