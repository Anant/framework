# Assessment for Candidates

This is an assessment we use to see what your level of aptitude is with industry tools that are freely available on the internet. 
We send this assessment to candidates we feel are good at the basic knowledge and are able to communicate. The goal is to see how you can use existing
documentation to achieve this or to figure something out. A big part of our company's work is to learn new tools, teach it internally, and communicate it to clients. 

What we're looking for is how well you reviewed the links, did additional research as needed, and how far you were able to go. Pick one track and let us know how far you get in 24-48 hours. You can take longer but we are making decisions soon so we're looking for folks who can quickly get started with instructions like this and start to figure things out.

- ## Customer Experience Engineer
  - Demonstrate basic knowledge of modern dev ops tooling
    - [Bring up Wallabag on Docker](https://doc.wallabag.org/en/admin/installation/installation.html#installation-with-docker) 
    - Demonstrate working Wallabag Front End without any CSS Issues
    - Demonstrate working Wallabag API via Postman
  - [Demonstrate knowledge of using REST API to send Data](https://doc.wallabag.org/en/developer/api/readme.html)
    - [Authenticate external front end or back end application](https://doc.wallabag.org/en/developer/api/oauth.html)
    - Create a front end or back end tool in any language or using an [existing API wrapper](https://doc.wallabag.org/en/developer/api/resources.html)
    - Tool should be able to take a copied /pasted text
    - Tool should parse out all the links (http , https) 
    - Tool should parse any other text as "tags"
    - [Tool should import the links into the API using the URL and the Tags](https://doc.wallabag.org/en/developer/api/methods.html)
  - Demonstrate knowledge of using REST API to retrieve Data
    - [Authenticate external front end or back end application](https://doc.wallabag.org/en/developer/api/oauth.html)
    - [Given a "tag" retrieve and display URL, Tags, and if Applicable the Image Preview](https://doc.wallabag.org/en/developer/api/methods.html)
- ## Enterprise Customer Experience Engineer
    - Demonstrate Basic Knowledge of Sitecore
      - Install Sitecore on Premise
      - Install Sitecore in the Cloud [ AWS | Azure ]
      - Develop and Deploy a View Rendering 
      - Develop and Deploy a Control Rendering 
      - Basic Understanding of Sitecore Packagaes 
      - Basic Understanding of Unicorn
      - Basic Understanding of TDS
  - Demonstrate Advanced Knowledge of Sitecore
    - Sitecore CICD CM & CD Deployment 
    - Personalization
    - Search
    - xDB installation, maintenance, personalization integration 
- ## Data & Analytics / Engineer
  - [Demonstrate basic knowledge of dev ops tooling](https://docs.datastax.com/en/docker/doc/index.html)
    - [Bring up DSE on Docker](https://docs.datastax.com/en/docker/doc/docker/dockerQuickStart.html) 
    - Demonstrate working DSE OpsCenter Front End
    - Demonstrate working DSE Studio Front End w/ Spark, SparkSQL, Graph
    - Demonstrate working CQLSH/Nodetool commands in Docker exec
  - [Demonstrate knowledge of using basic Spark to Import Data](https://docs.datastax.com/en/dse/6.7/dse-admin/datastax_enterprise/spark/usingDSESpark.html)
    - Find a data set online or use Datastax Examples
    - Create a schema of use Datastax Example schema
    - Create a Spark Script (Python or Scala) OR Spark Job to import data into DSE
  - Demonstrate knowledge of using basic Spark or SparkSQL to get counts
    - Using imported data set show how to use Spark to do basic aggregations/ filtering
    - Can use Spark or Spark SQL
  - Demonstrate knowledge of using an external tool to use CQL and SQL  
    - Use an external tool like DBeaver or otherwise to show how to query data via CQL
    - [Start AlwaysOnSQL in DSE](https://docs.datastax.com/en/dse/6.7/dse-admin/datastax_enterprise/spark/alwaysOnSql.html)
    - [Use an external tool like DBeaver or otherwise to connect via JDBC and query data via SQL](https://docs.datastax.com/en/dse/6.7/dse-admin/datastax_enterprise/spark/simbaJdbcDriver.html)
    
- ## Information Systems / Business Analyst / Engineer
  - Demonstrate basic knowledge of cloud systems
    - Identify and sign up for a software as a service which has a developer API (CRM, Project Management, etc.)
     - Salesforce, Hubspot, etc. 
     - Jira, Asana, [Trello](http://leaves.anant.us/leaves/#!/?tag=trello)
    - Identify and sign up for a platform as a service on which you can deploy front end, back end code
     - Heroku, Zeit, AWS Lambda
     - [Netlify](http://leaves.anant.us/leaves/#!/?tag=netlify), Zeit, AWS CloudFront
    - Identify and signup for a infrastructure as a service on which you can manage virtual machines
     - DigitalOcean, AWS, Azure
  - Demonstrate basic knowledge general rapid prototyping no code platform as a service(https://www.g2.com/categories/no-code-development-platforms)
    - [Using a rapid prototyping platform create a form to collect data from a potential job seeker (name, email, LinkedIn, GitHub, address, zip)](http://leaves.anant.us/leaves/#!/?tag=nocode)
     - [Airtable](http://leaves.anant.us/leaves/#!/?tag=airtable), Google Forms, etc. 
     - Zoho App Creator, etc.
  - Demonstrate basic knowledge general automation platform platforms as a service
    - Using a general automation platform take data from a source system when data is entered and send it to a destination system in real-time
     - [Zapier](http://leaves.anant.us/leaves/#!/?tag=zapier), Tray.io
     - Microsoft Flow, Zoho Flow
  - Demonstrate basic knowledge of general integration platforms platforms as a service
    - Using a general automation platform take data from a source system, transform it, and then import it into a database
     - StitchData, XPlenty, Databox
  - Demonstrate basic knowledge of general business intelligence platforms as a service
    - Using a general business integration platform as a service retrieve data from an outside source such as an API or a database and visualize it in some way 
     - Domo, Tableau, Redash, Metabase
