Node JS App on EC2 with git 
```
// clone repo 

git clone https://github.com/atulkamble/todo-app.git
cd todo-app/

ls

# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
 # in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"
# Download and install Node.js:
nvm install 22
# Verify the Node.js version:
node -v # Should print "v22.15.0".
nvm current # Should print "v22.15.0".
# Verify npm version:
npm -v # Should print "10.9.2".
node -v

ls -la

npm init -y
touch app.js
npm install express
npm fund
ls -la
nano app.js 
nano package
nano package.json 
npm install
npm run
npm start
sudo nano package.json 
npm start
touch .gitignore
nano .gitignore 
clear
git add .
git commit -m "code"
git push origin main
```
