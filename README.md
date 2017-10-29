## Install PHP 7.1 on a Cloud 9 Workspace

### Usage

**NOTE:** If you are reading this in a cloned workspace with PHP 7.1 already installed,
you do NOT need to run `bash install.sh`. Proceed to verifying the installation.

1. To install:

```
bash install.sh
```

2. Verify installation by viewing info.php in your workspace's url:

* Click "Run Project" above.
* The "Apache & PHP" tab should display your web site URL.

3. Verify your MySQL installation:

* Your MySQL user is "homestead".
* You will be prompted for the password which is "secret".

```
mysql -u homestead -p
   show databases; -- should see six databases including homestead
   use homestead;
   show tables;    -- should be empty
   quit            -- Bye
```

### Documentation

Getting started with Cloud9:

* https://docs.c9.io/docs/
* https://www.youtube.com/user/c9ide

The second (youtube) link is their channel page. You can see intro videos on that page.
Click on the "Uploads" section and you can find more useful videos such as
[Setting Up phpMyAdmin](https://www.youtube.com/watch?v=71BJF3HQzZQ) and
[Debugging PHP Code with Cloud9](https://www.youtube.com/watch?v=l5HxwCMTMz8).

### Workspace Update

This workspace has been set up from a GitHub repository. If repository material has
been added/updated, you can pull it into your workspace with `git pull`. You can check
the repository status with `git status`.