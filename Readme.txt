This is the example for Webhook
# We'll need to get a personal API key from our git repo
#1, create a fork of this repository:

https://github.com/robertstarmer/jenkins-git.git

# creating

https://github.com/{your_github_user_name}/jenkins-git.git
#2, in github, get a personal access token:

https://github.com/settings/tokens

#3, when creating the token, add:
admin:repo_hook
repo:*
notifications:*

#4 after configuring jenkins, verify that the webhook
# was created
https://github.com/{your_github_user_name}/jenkins-git/settings/hooks



