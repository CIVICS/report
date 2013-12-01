####State of Nevada

Nevada’s business one-stop portal initiative has been implemented. The service is delivered through a website branded SilverFlume (https://www.nvsilverflume.gov/). The principals interviewed were able to provide a good history of the efforts surrounding the site.  The SilverFlume initiative was led by the Secretary of State who worked with Nevada’s legislature to pass NRS 75A.100, et.seq that charge the Secretary with establishing a state business portal, along with the standards and requirements to support it (See http://legiscan.com/NV/bill/AB63/2013).  The initial effort to build the business one-stop was driven by outreach to the business community via focus groups to understand their needs.  The Secretary of State’s office then partnered with the state Taxation agency and made use of an RFP that was developed with a consultant to contract with CapGemini to build the site.  The RFP phase went from November 2009 through June of 2010 (7 months), with the implementation project running from July 2010 through October 2011 (15 months) until the vendor was deemed unsuccessful in implementing the project.  The state took over the project and implemented it using an agile methodology over the following seven (7) months, going live in June 2012. The original budget of the project was around $6.5M, with the state implementing the system using about $375K of remaining budget.  

The site primarily automates the business formation process, although the overarching goal of the site is to provide integration with other state agencies and local government.  As a basic building block, the state has established a set of Common Business Registration (CBR) data and also a common identifier across agencies for each business. At present, two of the three conceptual “tiers” of integration are available – the first is very basic, where another agency makes use of the information in the system to print and attach the page containing the common information to the front of another agency form as input to avoid duplication. The second enables an agency to take a data feed of this information via web service. The third, just now being developed, would be to integrate local government or other parties into the wizard and processes related to the site.

Priorities on initiatives for day-to-day operations are set by the Secretary of State’s office, where support for SilverFlume has been set up as its own division. Agencies participate in governance as it relates to their data and functions.  They noted during the interview that, to some extent, prioritization was driven by statutory deadlines for changes. The technical solution is a custom one built on Oracle using standard interfaces. During the project, it was intended that Oracle’s Identity Management tool would be leveraged, but due to obstacles, the system does not use this. Instead, “quasi-federated” identity is enabled via linkages across Oracle databases.  The current plan is to subscribe to the statewide enterprise Identity Management (IDM) solution when it becomes available because “true SSO is a gap” in the current system. Analytics were also initially handled through a purchase of an Oracle Business Intelligence tool, but obstacles encountered resulted in a move to custom web-based reports to pull cross-agency statistics captured by the SilverFlume solution. The technical solution supporting SilverFlume is hosted at the central state IT facility. Ongoing maintenance and new development for SilverFlume is handled by three internal technical and functional staff, two contract developers, and a contract for DBA services. Including ongoing annual software licensing of $300K, the total budget for operations is about $1M per year.

Lessons Learned. In our interview with the Nevada Secretary of State’s office, they offered several lessons learned from the project.  

•	Lay out your project to power the highest business value/lowest complexity features first.  
•	They chose to focus on a subset of agencies, as priorities and sponsors change over time in a political environment – seemed best to “take small bites”.  
•	Focus on short sprints or release cycles to introduce new high-business value features on a regular, near-term basis.  
•	Where there is an important business objective, don’t let stakeholders of existing legacy business processes and systems talk you out of pursuing the vision (“it can’t be done” often equals “I don’t know how.”)  
•	Make sure that executives have access to change management training and tools, and be prepared to support all stakeholders with training and other support to weather the change.  

Two notable features of the SilverFlume initiative are also worth highlighting. First is their focus on delivery of web-based training on how to make use of the service. The training is delivered via video and documentation available for download and hosted at www.box.com.  The aspect is their customer survey process, where they have contacted over 8,000 users from the business community to measure their satisfaction with the site and services.  They reported that the initial number of those finding it difficult to use was 11% - in a subsequent survey this shrunk to 8%.

####Highlights  
#####Nevada SilverFlume  

Stage: Operational  
Scope: Business Formation  
Implementation Cost: $6.5M*  
Operational Cost: ~$1M /yr  
Duration: 22 months (after RFP)  
Governance: Participating agencies have input, but run primarily by Secretary of State’s office  

Notes:  
•	System allows sharing of Common Business Registration Data  
•	Has a shared common Business Identifier code in place  
•	Custom software solution  
•	Single sign-on accomplished on backend via database connections.  

   *Unclear how much of this investment was reused in eventual site implementation

