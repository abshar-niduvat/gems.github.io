## Run these commands on your local computer.

#### For an existing project ...

Step 1:  Navigate to your repository's directory: `cd /path/to/your/repo`

Step 2: Configure your local repository to push to the self-hosted repository:

```
git remote add origin ssh://kalotus.com@ssh.gb.stackcp.com/home/sites/25a/8/874869d5cb/gems
git push -u origin master
```

<br>

----------

#### To start a new project ...

Step 1:  Clone the self-hosted repository to your local computer and navigate to its directory:
```
git clone ssh://kalotus.com@ssh.gb.stackcp.com/home/sites/25a/8/874869d5cb/gems
cd gems
```

Step 2:  Add additional commands to `stack-deploy.sh` in order to use automatic or manual deployment

Step 3:  Commit the `stack-deploy.sh` file to the project:
```
git add stack-deploy.sh
git commit -m "Change deployment configuration"
git push -u origin master
```

