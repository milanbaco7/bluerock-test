[BlueRock Logo](https://assets-global.website-files.com/5c860ded219c64010f1b4548/5d3550616b1d5c18152399b0_logo_main_infinite%20scalability.svg)
# JS Candidate Challenge
Congratulations to making this far in the interview process with BlueRock! We are thrilled to have you taking this javascript challenge.

This challenge has been setup to get you using your mad skillz with javascript using any framework or flavour of javascript you want to use.
You will be using jQuery in this role, however feel free to use whatever you are comfortable with.

## The brief
You will need to write javascript that adds interactivity to the products.html page, so that when you click on a client (in the dropdown) the colours of the boxes below change based on the status of client which could be "already_engaged", "in_progress", "opportunity", "external" or null if no status is registered currently.

The colours for each of the status's are covered in products.html:(Line 66) onwards.

When the page first loads, a "client_db" variable is preloaded from the products.js file.
This contains all the data for each client, and your challenge is to use this "database" and change the colours of the corresponding boxes based on what the user selects in the dropdown.

## Setup instructions & Help with the challenge
To get this pre-existing solution working follow these steps
1. If you haven't installed node.js already, install node.js and check it's installed by running in the command line 'node -v' and 'npm -v'. This should come back with a version number for each command
2. Next Install 'http-server' globally 
3. Run 'http-server' in this 'js-candidate-challenge' folder and open the URL's displayed. Click on products.html and verify you see a drop down list with boxes saying 'Accounting', 'Law', etc
4. Add your code at the base of the 'products.html' file and use the client_db which contains all the client data from the 'products.js' file
5. Once complete, add the solution to a public github (or other code repo of your choosing) and send the link to the public repo to your BlueRock hiring manager for browsing
