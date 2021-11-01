## Logical View ## 

The Family Farmacy solution contains the following parts:

- **FamilyFarmacy platform** - which is used by Transactional Customers to become Engaged Customers, by Engaged Customers to manage their details, consent and subscribe/un-subscribe and by Dieticians to manage their details and account.
- **FamilyFarmacy CustomerSegments platform** -  which is a system used by FamilyFarmacy Campaign Managers to define Customer Segments and administer trends and other statistics.
- **Forum and Blog solution** - which is a solution based on joomla (open source Content Management System), delivering functionality for managing digital content, but also allowing users to engage via Forums and Blogs.
- **Class Management solution** - which is a solution based on moodle (learning platform designed to provide educators, administrators and learners with a single robust, secure and integrated system to create personalised learning environments), allowing Engaged Customers and Dieticians to participate in classes and events.
- **Campaign Management solution** - which is a solution based on autopilot used by FarmacyFoods Campaign Managers to define and execute Marketing Campaigns to convince Transactional Customers to become Engaged Customers and then later engage into Course, Events, etc.
- **IAM solution** - based on AWS IAM (and AWS Cognito) to ensure all FamilyFarmacy solutions are placed under the same SSO umbrella, with robust authentication and authorization processes.
- **Event Data Consumers** - these are small scalable worker applications, with the responsibility of consuming different Event data and persisting it into the database layer of the FamilyFarmacy solution. As there are different types of Events (Customer actions in FoodFarmacy, Customer reactions to Campaign, sentiment analysis results, medical profile information changes etc) and there are also different ways of accessing that data (either via messaging queues or via API calls), there will be several types of Event Data Consumers, to accommodate this variation.
- **Campaign Execution Worker** - these are small scalable worker applications, with the responsibility of executing a Marketing Campaing, either via Social Media or via Email. There will be several types of Campaign Execution Worker, to accommodate this variation.
- **Search Engine** - this is an Amazon CloudSearch service, used to index data from different sources (Classes, Events, Forums, Blogs and FamilyFarmacy platform) so that an Engaged Customer (or a Dietician) would be allowed to performed a unified search for such content.

 

For future extensions:
- **Sentiment Analysis solution** - to make campaigns more efficient, it would be beneficial to include in the Customer profile an evaluation of the Customer’s sentiment on certain topics. This will be done via a sentiment analysis solution (based on Amazon Comprehend).

![image](../files/FarmacyFamilyLogicalView.drawio.svg)
