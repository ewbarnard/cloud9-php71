# Steps Taken

These are the steps I took in setting up the Cloud9 workspace.

1. Fork https://github.com/svpernova09/cloud9-php71 to become
https://github.com/ewbarnard/cloud9-php71 . Since we will be creating the
Cloud9 workspace from this fork, the Cloud9 workspace can pull
workspace updates.

1. Merge my updates to the fork's master branch. This makes the
Cloud9 workspace-creation step cleaner.

1. From the Cloud9 dashboard, create a new workspace. This will be
the master from which student workspaces will be cloned.

  * **Clone from Git or Mercurial URL**: Enter the GitHub forked
  repository's URL. I use "Clone with HTTPS" rather than "Use SSH"
  so that I don't need to enter credentials.
  * **Choose a template**: Click on "PHP, Apache ...".
  * Click the "Create workspace" button.
  
  