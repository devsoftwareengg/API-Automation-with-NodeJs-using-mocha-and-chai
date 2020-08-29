# API-Automation-with-NodeJs-using-mocha-and-chai
API Automation with NodeJs using mocha and chai

#install NodeJs in your system

wget -qO- https://deb.nodesource.com/setup_8.x | sudo bash -

sudo apt-get install -y nodejs verify your installation

node --version

#Install Newman in your system if not installed

npm install -g newman

#Install htmlextra plugion to get the html report 

newman run collection.json -r htmlextra

#Command to Run the Tests:

newman run ApiTesting.postman_collection.json -r htmlextra


#View the results in htmlReport:

cd "newman" directory and view the html report
