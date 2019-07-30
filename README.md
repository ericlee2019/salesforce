# salesforce

# Download CLI
Install Salesforce CLI [here](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm).

# Run the following commands to ensure correct installation
```
$sfdx

$ sfdx --version

$ sfdx update
```
## Create test account
http://developer.force.com/

# Enable "Dev Hub" in Setup

# Run following commands
```
$ sfdx force:auth:web:login -d -a "Test Org"

# check to see if you are connected
$ sfdx force:org:list

$ sfdx force:auth:web:login -s

# run test query
sfdx force:data:soql:query -q "SELECT Name FROM Account"
```