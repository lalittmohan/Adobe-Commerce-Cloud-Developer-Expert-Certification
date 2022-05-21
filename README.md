
Adobe Commerce Cloud Developer Expert Certification  ["AD0-E706 Adobe Commerce Cloud Developer Expert Exam"](https://express.adobe.com/page/34U3DEjqG3G4Q/).
### Information
[Exam Guide](https://express.adobe.com/page/GrkbPktpWMkkb/)


## TOPICS

1. **Commerce Cloud Fundamentals (13%)**
   1. Describe the features and functions of Magento Commerce Cloud
      - What is Magento Cloud?
      - Cloud platform overview and features
   2. Determine how to locate settings with Cloud Admin UI
      - Locate project settings, user management, and project variables pages
      - Locate environments, access links, and logs
      - Locate environment settings
   3. Demonstrate the ability to manage users
      - Add SSH key
      - Add users to a project and manage their roles
   4. Determine the difference between Magento Cloud plans
      - Starter plan vs. Pro differences
   5. Determine how different environment types operate
      - Determine differences in environment types: Integration, staging, production 

2. **Local Environment (9%)**
    1. Demonstrate ability to set up local development
       - Software you need to have locally for developing a Magento Cloud project
    2. Given a scenario, demonstrate ability to use the Magento-cloud CLI tool
       - Install Magento-cloud CLI. Retrieve project info
       - Manage project and environments
       - Connect to database and SSH
       - Build the project locally

3. **Cloud Configuration (13%)**
    1. Determine how to configure Cloud
       - How to configure different redirects in this file, which types of redirects should not be configured here
       - How to add these configurations to Staging or Production environments. Magento On-Premises installation migration
       - How to migrate an existing Magento installation into Magento Cloud: Code base, database, media migration
    2. Determine how to configure a planned service
       - How to configure a service that is planned to be added to the environment
    3. Demonstrate ability to add to your environment
       - Which configurations you can add to your environment and how to do it
       - What to configure in this file, on which environments these configurations are applied, how to add these configurations to environments where this file is not read
    
4. **Service Configuration (5%)**
    1. Demonstrate ability to create service configurations
        - How to add system services: MySQL, Redis, Elasticsearch, RabbitMQ
    2. Demonstrate ability to use Slave connections
        - How to leverage slave connections to MySQL, Redis

5. **Deployment Process (10%)**
    1. Determine the processes during deployment
       - Describe all processes that are running during deployment: Build, deploy and post-deploy phases. Explain why downtime occurs on your project
       - What role every process/phase plays and how to impact every process
       - How Magento Cloud deploys Magento. What every script does on every deployment phase
       - How to extend these scripts and best practices for doing so
       - Describe the ways to retrieve logs for phases and its scripts
    2. Demonstrate the ability to create Magento Cloud script configurations
       - Which configurations you can set in .magento.env.yaml, and Cloud environment configurations that are not described in the units about SCD and service configurations
   
6. **Static Content Deployment (10%)**
    1. Demonstrate ability to move SCD to build phase
       - Describe the default process of generating SCD and how it impacts downtime
       - Describe the reason for moving generation static content to the build phase. 
         Consider the way to do this and show the result (timeline)
       - Determine additional configuration that helps decrease deployment time (SKIP_HTML_MINIFICATION)
       - Display time measurements
       
    2. Demonstrate ability to avoid SCD on both phases
       - What are causes for avoiding SCD
       - Describe the way to do this in all cases, and the expected result
      
    3. Describe how to generate static content on demand
       - Describe the default Magento behavior in Production mode and why the new "mode" was added
       - How does Magento behave when it is set to this "mode"?
       - Know when users can use this configuration and how it works from the Cloud side
       - Display time measurements
   
7. **Development (20%)**
   1. Demonstrate ability to change configurations
      - What are the sources of Magento configuration, and which priorities have different sources of Magento configuration?
   2. Demonstrate ability to change a locale
      - Know how to change a locale on Cloud
   3. Demonstrate ability to add extensions
      - Know how to install Magento extensions and themes (limitations, read-only filesystem, etc.)
   4. Demonstrate ability to enable / disable a module
      - Know how to enable or disable a module on Cloud
   5. Demonstrate ability to set up a multisite configuration
      - Know how to setup multisite configuration: Adding and configuring new websites in Magento; Nginx configuration through the .magento.app.yaml for multisite setup; how to route websites through the magento- vars.php
   6. Demonstrate ability to use variables
      - When do you need to use variables; which configurations you can change using variables
      - What is the difference between variables and environment variables
      - What is the difference between project and environment level variables

8. **Troubleshooting (10%)**
   1. Demonstrate ability to locate and use logs
      - Locate the Magento application logs
      - Locate system services logs on integration and Starter environments
      - Locate system services logs on Pro environments
   2. Demonstrate ability to create snapshots and backups
   3. Demonstrate ability to debug
      - How to use XDebug on Cloud
   4. Demonstrate ability to apply Magento fixes in patches
   5. Describe branch synchronization
      - Describe branch synchronization and merge

9. **Go Live and Maintenance (10%)**
   1. Demonstrate ability to configure DNS
      - DNS configuration when you're going live
   2. Demonstrate ability to set up and configure Fastly
   3. Demonstrate ability to upgrade to a new version
      - Upgrade of Magento and ece-tools to newer versions
   4. Demonstrate ability to upsize
      - How to upsize the environment

# References
+ [Adobe Magento Exam Guide](https://express.adobe.com/page/34U3DEjqG3G4Q/)
+ [Magento at GitHub](https://github.com/magento/magento2/tree/2.4.3)
+ [Magento DevDocs](https://devdocs.magento.com/)
+ [Glossary](https://glossary.magento.com/)
+ [Adobe Commerce (Magento Stack Exchange)](https://magento.stackexchange.com/questions)

## Links
+ [Cloud Project](https://cloud.magento.com/cloud/project/view/)
+ [Integration Environment](https://magento.cloud)
+ [Help center / Support](https://support.magento.com/hc/en-us/requests)
+ [Status](https://status.magento.cloud/)
+ [CLA](https://magento.com/legal/terms/cloud-sla)
+ [Magento Cloud Repository](https://github.com/magento/magento-cloud)
+ [Ece-Tools Repository](https://github.com/magento/ece-tools)
+ [Ece-Tools / .magento.env.yaml sample](https://github.com/magento/ece-tools/blob/2002.0.17/dist/.magento.env.yaml)
+ [Fastly tester](https://magento-tester.global.ssl.fastly.net/magento-tester/)
+ [magento-cloud list](https://gist.github.com/simpleadm/69c3ef764fdd637a109bbaed8420d714)

## Credits