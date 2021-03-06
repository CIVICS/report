####State of Oregon

Interviews with the Oregon Secretary of State’s office showed that their approach to a business “one-stop” is really divided into two parts.  
#####Part I:
The newest - and award-winning – part is called Business Xpress. This site, located at http://www.oregon.gov/business/, is considered the central gateway and navigation aid to “resources for starting, expanding and operating a business in Oregon or relocating a business within or to Oregon.” The Business Xpress site was built as an outcome of an effort led by the Oregon Secretary of State. In 2011, legislation was passed (HB 3247) that established the Secretary of State as the responsible party for implementation of the site. The legislation directs “all agencies of state and local government that have functions related to business registration, licensing, permitting or taxation (along with business relocation) to cooperate with and assist in executing these duties.”  The bill also outlined the scope and functions of the site, which made the success factors clear. They began work with a core set of nine agencies by prototyping, then reached out to the business community.  The overall effort from design through implementation took about 11 months (August 2011 prototype, October 2011 kickoff, June 2012 go-live).  The total cost for the project was $485K. It was built by the Oregon affiliate of the National Information Consortium. The site was built in Microsoft SharePoint 2010 and incorporates responsive design using CSS3 and HTML5 technologies and won awards from both Computerworld and the National Association of Chief Information Officers (NASCIO). In summary, this site is really a navigation guide that links to other resources, including the Central Business Registry below.

#####Part II:
While the most recent and most visible activity was around Business Xpress, since 2006 Oregon has had an online Central Business Registry (CBR) – a list of services included is provided at: http://www.filinginoregon.com/cbr/services.htm - and includes those agencies who are part of the Business Formation process.  This site is linked to from Business Xpress, but is not integrated with it.  The CBR began in 2004 with implementing the DBA (doing business as) application out of the Secretary of State’s office, expanding incrementally to add the taxation and employment agency functionality (their Department of Revenue and their Employment Department). The expansion phase occurred between April 2007 and February 2008. While there were challenges related to data sharing across agencies, legislation was passed to allow sharing of specific data elements related to business registration. Governance was established in the form of a committee to oversee the effort composed of a technical executive manager and one business leader from each of the participating agencies, with one vote given to each agency. Technology and security standards were developed by a separate technical committee composed of agency technical experts that reported in to a project team made up of project managers from each agency involved, overseen by an enterprise project manager responsible for the overall project (Source: NASCIO 2006 Award Nomination). 

The project made use of web services to exchange needed information, following the principle that agencies should not have to reengineer processes or develop new systems to participate. The system was built using Oracle, with Oracle Identity Manager as a shared sign-on solution. Upon submission, there is a workflow engine with rules that route the document for approvals.  They make use of APIs in this system.

One lesson learned related to an upgrade the system is currently undergoing to change approach to more of a “hub and spoke” architecture, so that things are less tightly coupled.  The problem they ran into with the tightly integrated approach is that there were conflicting timelines and schedules across the participants for when changes needed to be done (driven by statute, say, for something to be in at the beginning of a fiscal year, vs. that being a busy time for another agency that had no resources to devote to testing). The new approach will allow agencies to only have to deal with changes that affect them. In addition, the CBR architecture is such that minimal data is kept in a shared layer.  If a user wants to pull up a record of previous activity, it is retrieved from the existing agency systems.

The project has its own help desk and has actually included features in the application that help the staff address issues, like a button that can be used to survey their PC.

In nominating the project for a NASCIO award, the State highlighted the following success factors:


•	The ability to quickly obtain critical but vital legislation;  
•	Strong executive management support and sponsorship for all participants;  
•	Steering committee commitment with involvement in crucial roles by the necessary people;  
•	Strong common vision, scope and methodology;  
•	Strong project discipline without rigidity;  
•	Sole executive sponsorship;  
•	A small but empowered number of participants from each agency. Each agency participant must be empowered to make binding decisions on behalf of their respective agency. 

####Highlights
#####Oregon Business Xpress and Central Business Registry (CBR)
Stage: Operational (both)  
Scope:  
Business Xpress: Navigation to other available sites, resources  
Central Business Registry: Business Formation.  
Implementation Cost:  
Business Xpress: 485K  
Central Business Registry: $4-5M (est.- over time)  
Operational Cost:  
Business Xpress: 38K/yr  
Central Business Registry:$200-300K/yr  
Project duration:  
Business Xpress: 11 months  
Central Business Registry: 24-36 months (two phases)  
Governance:  
Business Xpress: 9 agencies  
Central Business Registry: 3 agencies involved in business formation  

Notes  
•	Statute passed specifying Business One-Stop effort to be responsibility of Secretary of State.  
•	Has Common Business Identifier across agencies.  
•	There have been several attempts to implement the CBR since the 80’s.  
•	Minimal amount of data is shared.  
