###Technology

The underlying technical architecture and technologies used on the site might be evaluated in terms of cost and ability to support them, extensibility to other agencies (which could also include a brief assessment of the technologies, architecture and other capabilities of systems that might be required to be rewritten or “plug-in” to the architecture), and similar aspects.  We were not able to gain access to the technical infrastructure for this report, although some limited work (see previous section) was done to provide context. The Recommendations and Next Steps section includes guidance on possible next steps.

A comprehensive review of the technical architecture of the services provided through the Kansas Business Center is beyond the scope of this report.  Also, absent access to the underlying code, it is difficult to conjecture about the general supportability and extensibility of the services currently offered. The Technology portion of the preceding section provides limited information about the technologies used on the site.  However, based on this information and a review of the site, the following observations appear relevant:

####Robust Reporting/Analytics lacking

From the high-level traffic reports reviewed, it does not appear that a software layer (logging, reporting, data export) has been created to view analytics about the activity, as well as analyze/correlate and report on activity conducted within the functionality of the Kansas Business Center, especially across the two agencies currently participating – or with Network Kansas or other partners.  That is, while some limited web traffic reports are generated, the activity within the applications, for example, shopping cart abandonment does not appear to be tracked, nor is there a focus on analytic information about the formation of businesses to provide a consolidated view of the level of filing occurring through the site.

####Integrated granular Authentication/Authorization processes lacking.

While the Kansas Business Center does have its own registration and sign-on process, it appears that there are levels of transactions that either could be added to the KBC, or already exist there, that could benefit from a higher level of proof of identity.  At present, the custom sign-on provides only one basic level of credentials, which could be a constraint moving forward to expand the number and type of transactions included. It is also not clear that the ability to delegate authorization to perform transactions is available, or that the authentication for the site could be easily ported to services at other agencies or the local level.

####Web Services lacking.

From the outside, it is not clear whether or not the applications are making use of web services. Other than for interaction with a payment engine, there do not appear to be any published application programming interface standards (SOAP, REST) for third parties to “mash up” or interact with publicly available data captured or created as part of the operation of the KBC, nor does this technology appear to be delivered in a way for other government organizations (vertical, horizontal) to “plug-in” to the KBC functionality.
