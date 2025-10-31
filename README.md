Challenge 3 – Import Set

In ServiceNow, Import Sets are used when we want to bring data from another source, like an Excel file or an external system,
into ServiceNow. For example, if our HR team gives us a spreadsheet of all employees, we can upload that into an Import Set table first.
This table acts as a temporary place to hold the data. Then, using a Transform Map, we tell ServiceNow how to move that data into the correct target table,
such as the User table. During this process, we can also clean or adjust the data. For instance, if some department names are written differently, 
we can make them uniform before saving them. This makes sure our data is correct and organized.

Challenge 4 – Common Service Data Model (CSDM)

The Common Service Data Model, or CSDM, is like a guide that shows how all the parts of a company’s services fit together in ServiceNow. 
It helps us connect business services to the technical parts that support them, such as applications, servers, and databases.
For example, if we have a “Student Portal” service, CSDM helps link that service to the web application and the database that runs it.

CSDM is very useful because it helps everyone in the organization see the big picture — from business leaders to IT teams. 
It improves how we track services, manage incidents, and plan changes. The model is built in layers: Foundation, Design, Manage Technical Services,
and Deliver/Operate. Each layer shows a different stage in how a service is designed, built, and managed. Overall, CSDM helps keep our CMDB organized, 
accurate, and aligned with the business.

Challenge 5 – Security Center & Shared Responsibility Model

The Security Center in ServiceNow helps administrators check how secure their instance is. It shows if there are any risks,
like users with too many permissions or outdated configurations. For example, if someone has admin access but no longer needs it,
the Security Center can highlight that. It helps us fix issues quickly to keep our data safe.

The Shared Responsibility Model means that both ServiceNow and the customer share security duties.
ServiceNow is responsible for keeping the platform and data centers secure, while the customer must take care of user access,
data protection, and configuration settings in their own instance. This way, both sides work together to keep the system safe and reliable.
