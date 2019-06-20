Please follow these steps carefully! They will allow you to set up an identical development environment.



GLOBAL DEPENDENCIES: install first

1. Install NVM to manage possible multiple versions of node <code>curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash</code>

2. Install Node (a javascript server side environment) and NPM (a package manager that keeps track of downloads and their dependencies) <code>nvm install node</code>

3. Inside of a directory/folder that will be the parent of the develoment folder on your local maching do <code>git clone https://github.com/app-mds/frontend-environment.git</code>

4. go into the directory you just pulled down. <code>cd frontend-development</code>
If you install any additional development software make sure that it is add to <code>package.json</code> by using the <code>-save--dev</code> flag as in <code>npm install webpack -save--dev</code> 

PREVIEW APP ON MOBILE DEVICE VIA DEVAPP
1. Your phone has to be in 'developer mode'. (check google for instructions to your particular device)

2. You have to have and log into your ionic account when you run the dev-app oh your device.

3. You have to be on the same wifi-Network as the machine building the project.

4. In Code (VSCode aka Visual Studio Code) select 'Terminal' from top menu, then 'New Terminal'. It will open inside of the project (because when you are editing in Code that's where you should be) inside of the terminal type <code>ionic serve --devapp</code>





