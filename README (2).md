
## DOOT BOT OVERVIEW
The bot integration addressed key use cases by delivering secure transactions, tailored financial services, personalized support, and a smooth banking platform, all designed to improve user experience and accessibility in core banking operations.



![Screenshot1](https://github.com/Gauravgesture/Pythonencrypt/blob/334587f5a3aea19f88bd3d335f8029a6ddf1c576/screenshot1.png)
## Features

- **The Secure and Hassle-Free Transactions** emphasises the platform's commitment to safeguarding users' financial data while ensuring a seamless user experience. It reassures customers that all transactions, whether they are transfers, payments, or other financial operations, are conducted in a highly secure environment. 

- **Financial Solutions Tailored to Your Needs** The focus of this section is on customization and flexibility in financial services. It highlights that the platform offers tailored solutions, meaning that the financial products can be personalised to fit different customer profiles or needs.

- **Personalized Customer Support** ,This section reassures users that they have access to round-the-clock customer service that is tailored to individual needs. The emphasis is on personalized and 24/7 support, ensuring that users can always get help when needed.

- **The Seamless Banking Platform** offers a comprehensive suite of features designed to enhance user experience and accessibility in core banking services. It provides real-time account access, allowing users to monitor account balances, view transaction history, and customise account settings. Fund operations are streamlined with account-to-account transfers, external bank transfers, instant money movement, and scheduled transfers. 






## Arm template
**ARM (Azure Resource Manager) templates** are JSON-based files used to define and deploy resources in Microsoft Azure. They allow you to automate the creation, configuration, and deployment of Azure services by defining resources, dependencies, and configurations in a single, declarative template.

To meet these challenges, you can automate deployments and use the practice of infrastructure as code. In code, you define the infrastructure that needs to be deployed. The infrastructure code becomes part of your project. Just like application code, you store the infrastructure code in a source repository and version it. Anyone on your team can run the code and deploy similar environments.

## Features
- Declarative Syntax: Define infrastructure without scripting deployment order.

- Idempotency: Ensures consistent results on repeated deployments.

- Modularity: Supports linked templates for reusability and maintainability.

- Automation: Can be integrated into CI/CD pipelines for continuous deployment.

- Extensive Azure Resource Support: Deploys and configures most Azure services.



## 🔗 Links
[![Link])](Link to arm template/)

## System Architecture Flowchart

![](https://github.com/Gauravgesture/Pythonencrypt/blob/bd9a84dd23d7fba07ec97c1a3a28bdfa222beb3d/Screenshot%202024-10-24%20151042.png)


## Steps to follow
- Go to edit the template section
  <br/>
  ![](https://github.com/Gauravgesture/Pythonencrypt/blob/d1720755e16a93f9b6bc408ba13f783b6381c5be/Screenshot%202024-10-25%20104824.png)
 <br/>
- You can see the Arm template code here
   <br/>
  ![](https://github.com/Gauravgesture/Pythonencrypt/blob/d1720755e16a93f9b6bc408ba13f783b6381c5be/Screenshot%202024-10-25%20104848.png)
 <br/>

  - Here you have to select your resource group as well as the region and resource prefix name
    <br/>
    ![](https://github.com/Gauravgesture/Pythonencrypt/blob/d1720755e16a93f9b6bc408ba13f783b6381c5be/Screenshot%202024-10-25%20104933.png)
  <br/>
  - Provide the administrative password for credentials
     <br/>
    ![](https://github.com/Gauravgesture/Pythonencrypt/blob/d1720755e16a93f9b6bc408ba13f783b6381c5be/Screenshot%202024-10-25%20104943.png)
     <br/>

    - Provide the bot id and Ms app id which you will get after running the script and attach it
       <br/>

    ![](https://github.com/Gauravgesture/Pythonencrypt/blob/d1720755e16a93f9b6bc408ba13f783b6381c5be/Screenshot%202024-10-25%20104952.png)
     <br/>

    - Click on create and it will start Custom deploying your application services
       <br/>
   ![](https://github.com/Gauravgesture/Pythonencrypt/blob/9975750d9a8deb8c715d2dfa37b9d1c50f45d9d3/Screenshot%202024-10-25%20101550.png)
 <br/>

   




##  Resources Created
- __Front end web app__
Azure Web App Service is a fully managed platform designed for building, deploying, and scaling web applications across multiple programming languages such as .NET, Node.js, and Python. Additionally, the service provides robust monitoring and diagnostics capabilities through Azure Monitor and Application Insights, enabling developers to efficiently manage application performance and troubleshoot issues.

- __Backend Web app__
 Azure Web App,the siteConfig specifies application settings retrieved from the backendappSettings parameter, sets the runtime to Python 3.9, and defines the command to run the application using Gunicorn with specific parameters for binding, worker class, and timeout. Additionally, it specifies that GitHub Actions will be used for deployment, with a personal access token provided through the backendgithubToken parameter to authenticate the integration.

- __Postgress Db__
Using Azure Database for PostgreSQL Flexible Server provides a fully managed, scalable, and customizable database solution that reduces operational overhead by automating tasks like backups and patching. It allows for flexible configurations, enabling adjustments to compute and storage based on application needs, thus optimizing cost and performance. The service offers built-in security features, such as firewall rules and virtual network integration, enhancing data protection and access control.



- __Bot service__
The Azure Bot Service is utilized in this bot to create and manage intelligent bots that can interact with users through various channels, enhancing user engagement and automating tasks. By integrating with the Azure infrastructure, the Bot Service leverages cloud capabilities for scalability, reliability, and security. The service allows for the seamless deployment of conversational agents with features like natural language processing and the ability to connect to other Azure services. Additionally, the use of a managed identity facilitates secure communication between the bot and other Azure resources, ensuring that sensitive information is protected while simplifying authentication processes.


- __Azure search service__
This service is Azure's managed search solution, organizations can implement full-text search, faceted navigation, and filtering features without the complexity of maintaining search infrastructure. The service supports powerful search functionalities such as ranking, scoring, and custom relevance tuning, enhancing user experience and engagement. Additionally, its integration with other Azure services allows for seamless data indexing and retrieval, making it ideal for applications that require fast and accurate search results, thereby driving operational efficiency and improving user satisfaction.

- __Text Analytics__
Utilizing this service, organizations can perform tasks such as sentiment analysis, entity recognition, key phrase extraction, and language detection, enhancing their ability to understand and respond to user feedback and interactions effectively. The system-assigned identity provides secure access to the service without managing credentials manually, simplifying authentication processes. Enabling public network access ensures that applications can easily connect to the service from various environments. Overall, the Text Analytics service empowers businesses to extract valuable insights from text, improve customer engagement, and drive data-informed decision-making.

- __Open ai acc for embedding__
Azure OpenAI Service is utilized in ARM template to provide advanced AI capabilities, specifically for generating embeddings and facilitating natural language processing tasks. By integrating this service, organizations can leverage powerful models like GPT for tasks such as text generation, summarization, and conversational agents, enhancing the overall functionality and user experience of their applications.


-  __open ai acc for gpt4o__
The Azure OpenAI Service is incorporated in this is to facilitate the deployment of advanced AI models for various applications, specifically for generating and managing embeddings and supporting natural language processing tasks. By utilizing the service, organizations can access powerful AI capabilities, such as language generation, summarization, and more, enhancing their applications with intelligent features.

-  __open ai acc for gpt4o-mini__
The Azure OpenAI Service is included in this ARM template to deploy advanced AI capabilities, specifically targeting the use of the GPT-4 model for applications that require natural language understanding and generation. By utilizing this service, organizations can implement sophisticated features such as conversational agents, content generation, and text summarization, enhancing user interactions and automating complex tasks. The S0 SKU represents a standard pricing tier, suitable for various applications needing access to powerful AI resources

- __AAD scripts__
Azure deployment script that automates the registration of an application in Azure Active Directory (AAD). It specifies the resource type as Microsoft.Resources/deploymentScripts with an API version of 2020-10-01, and the script is named aadAppRegistrationScript. The script runs in the specified location and utilizes the Azure CLI (kind: AzureCLI) to execute the necessary commands for AAD registration. It employs a user-assigned managed identity for authentication, which enhances security by allowing the script to run with specific permissions without hardcoding credentials.his deployment script streamlines the AAD application registration process, making it efficient and secure while minimizing manual intervention.

