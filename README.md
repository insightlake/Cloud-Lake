# Cloud-Lake

<img style="width:100%;" src="images/cloudlake.png">

## Introduction
Cloud Lake allows provisioning of secure entrprise data lake easy on different cloud platforms like AWS, GCP and Azure.

## Designer
Designer allows drag and drop of components to design the data lake. Operations team can deploy the components from the designer tool.

## Security
Cloud Lake solution hides the complexity of building enterprise data lake solution by plumbing different services together seamlessly.

## Pages

1. Designer

<img style="width:100%;" src="images/designer.png">

1. Script

<img style="width:100%;" src="images/script.png">

3. Template

<img style="width:100%;" src="images/templates.png">

4. Dashboard 

<img style="width:100%;" src="images/dashboard.png">
5. Data Usage 

<img style="width:100%;" src="images/datausage.png">

6. Catalogs 

<img style="width:100%;" src="images/catalog.png">

7. Tenants 

<img style="width:100%;" src="images/tenants.png">

8. Resources 

<img style="width:100%;" src="images/resources.png">

9. Workflow 

<img style="width:100%;" src="images/workflow.png">

Installation
------
* Download or clone the repository. 
* Run bin/insightlake command.
* Open browser with URL as http://localhost:9494/
* Change configuration in /conf folder to set different ports
* By default H2 database is used, you can change the database details in jdbc.properties file

Installation using docker 
------
* Download or clone the repository. 
* cd /docker
* Run `docker-compose -f docker-compose.yaml up --build`
* Open browser with URL as http://localhost:9494/insightlake/


License
------
InsightLake Report Maker is closed source but distributed to be used freely. Please contact contact@insightlake.com for details.

Getting Help
----------

You can get help easily :
Community - Google Groups
Slack Channel
Twitter
Facebook
Email: contact@insightlake.com
