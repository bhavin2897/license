This JSON file includes a list of licenses which CKAN users utilize when they are creating datasets. 

## How to user

1- clone the repository in: "/etc/ckan/default/"

2- edit the ckan config file "/etc/ckan/default/ckan.ini":
    
    - find this line and uncomment it (if it is not already): licenses_group_url = http://licenses.opendefinition.org/licenses/groups/ckan.json

    - change the license path to: file:///etc/ckan/default/license/licenses.json
 
