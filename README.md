# ds-account-and-contact-exp-api


                                                          **DataStream Integration**

**UseCase :** Data management for Accounts and Contacts

**Overview**

The DataStream project enables real-time data exchange between your MuleSoft Experience API and Salesforce, streamlining data management for Accounts and Contacts. This documentation offers a overview of the project, including use case details.

**Objective**

The primary objective of this project is to facilitate real-time data interactions through the Experience API, catering to the following scenarios:

1. **Integration Services:** Internal integration services and applications within your organization can call the Experience API to access Salesforce data securely (calls the Experience API to retrieve and create Account and Contact information).

**Components**

The DataStream project follows the API-led connectivity approach, an architectural framework that enhances the modularity, scalability, and reusability of APIs. The approach is organized into three distinct layers:

1. **System APIs:** This layer is responsible for connecting to Salesforce. System APIs expose the specific capabilities and interactions with the external system.
   Code repo link - https://github.com/duddukuri-md/ds-account-and-contact-sys-api 
2. **Process APIs:** Process APIs contain the business logic. It serve as intermediaries between the System APIs and the Experience API.
   Code repo link - https://github.com/duddukuri-md/ds-account-and-contact-proc-api
3. **Experience API:** The Experience API acts as the front-end, providing user-friendly and well-structured APIs for external applications, such as the Customer Portal and internal services.
  Code repo link - https://github.com/duddukuri-md/ds-account-and-contact-exp-api
4. **Salesforce Custom Fields** - Custom fields in Salesforce have been created  to complement this project. These custom fields capture and store data and help in enhancing Salesforce data management capabilities.
5. **MuleSoft Common Error Handling** - A unified error handling strategy is consistently applied across the project to ensure uniform error handling and response. This strategy covers various error types, logs error details, and configures suitable HTTP status codes for responses.
