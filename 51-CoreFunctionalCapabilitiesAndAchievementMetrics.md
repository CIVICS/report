###Core Functional Capabilities and Achievement Metrics

The following high level capabilities and success metrics represent a synthesis of the recommended approach and components:

Identity as a Service for Login/Account Identifier Management
Metric: Accept externally issued credentials and tokens to access KBC Account

User Managed Profile for Account/Directory Data Update
Metric: User Updated Address Modifies Account and Updates Subscribed Endpoints

User Granted Authorizations for Personal/Protected Data Sharing
Metric: Protected Resource Access Token Issued According to Scope and Grant

Partner Provisioned Apps/Services for Extended Functional Capabilities
Metric: Manual or Dynamic Registration of OAuth2 Client to KBC Platform 

KBC Provisioned Access for Big/Open Data Analytics
Metric: Data-Set Catalog and REST API for Active Query/Subscribe or Bulk Download

User Account Systems 

This component provides user accounts and identity federation services.

User Authorized Forms Filling or Other User Granted Permission
The protected resources comprising a user’s account data, such as address, name, email, telephone and other information, can be re-used to seed the automatic pre-fill of forms.  In addition, the same capability enables use-granted authorization to access other protected resources, potentially including copies of previous filings, registrations or account history for use by a tax preparer or regulatory compliance professional.  

Extensible Login With User’s Native Identity Credentials
Login with LinkedIn, Google Business Apps etc.  Essentially the same technology enables login with larger company Active Directory tickets or Kerberos tickets.  

Admin Dashboard, Account History and Permissions Management
User managed settings and transactional information. 

Apps and Services Adaptors and Bus

Simple OAuth2 manual and dynamic client registration platform capability.  Authorization, Access and Resource server functions (see Mule, 

Agency Applications 
This component is comprised of the filing, forms, licensing and other transactions between businesses and state agencies.  The agency applications are not part of the shared service layer of the Kansas Business Center re-design concept, but are intended to be different and tailored to each interaction type, agency, program or transaction as appropriate.  

Initial Agency Applications 
The initial applications proposed for development in the scope of this project will enable a user to start a new business with the Secretary of State’s office. In addition, as part of the process of starting a new business, an application with the Kansas Department of Revenue is proposed that will – at a minimum – complete the business tax license application functions available in the current Kansas Business Center. Finally, it will allow businesses to manage their annual report and make amendments to filings with the Secretary of State’s office.

External Apps and Services:  This component provides integration with external third party applications and services such as available through the Apple or Android Mobile Apps marketplaces, or the constellations of desktop and browser business apps available through Google Business Apps and Salesforce marketplaces.  The MIT MODIS open architecture approach, leveraging federated user grants of authorization with the same OAuth2 technical developer and business process integration path commonly used by business app markets enables major amplification of value.  The value to Individual User Account holders is clear, based upon ease of use and leveraging the tools and services they already rely upon.  In addition, there are many opportunities for value to agencies and administrators as well.

