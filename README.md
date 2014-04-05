##iCodeNY Web Application Instructions 

1. Set up a new box on Nitrous.io: https://www.nitrous.io

Accounts to Sign Up  

1. Github 
2. Nitrous 
3. Heroku 

Add SSH Key for Nitrous 

ssh-keygen -t rsa -C "your_email@youremail.com"

Run the following code to copy the key to your clipboard.

pbcopy < ~/.ssh/id_rsa.pub

OR

cat ~/.ssh/id_rsa.pub

Next, Login to your Nitrous.IO account and click ”Public Keys” in the top right navigation. You shouldn’t have any keys listed if this is the first key you are adding. Click the “Add Public key” button:

