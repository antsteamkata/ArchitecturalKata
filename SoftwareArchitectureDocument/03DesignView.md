##User Profile
The following chapter offers an overview of the data design for creating the user profile, also used in customer segmentation and campaigns.

### Goals
1. Have a 360 degree view of the customer in order to provide relevant and seamless content to targeted users on different channels of engagement
2. Nurturing the transactional customer in order to become an engaged customer through automated workflow based campaigns
3. Generating engagement scores for the customers
4. Farmacy Family to become a digital lifestyle provider for the communities

### Assumptions
- The forum is not a closed community
- The forum offers an engagement score and rating for an user
- Facebook Login is available
- There will be a Farmacy Family Instagram/Facebook page

### Profile Data
| Source | Data | Method | Mapping | Scoring
|----------------|-------------------------------|-------|-------|------------|
|Farmacy Food|Transactional Customer Data<br/><ul><li>First name, last name</li><li>Email Address</li><li>Age</li><li>Addresses e.g. Work, Home, etc.</li><li>Preferred SmartFrdige Location/Addresses</li><li>Order history</li><li>Income</li><li>Household (no. of people in family)</li></ul> |push |email
|Forum|Engagement Score<br/><ul><li>Forum User Rating</li><li>Subscribed topics - Conversation threads</li></ul> |pull |email |Sentiment analysis based on conversation threads
|Social Media|Facebook Login<br/><ul><li>Likes</li><li>Interest</li><li>Photo</li><li>Facebook Id</li></ul>Social Engagement (Family Food Page)<br/><ul><li>Likes</li><li>Comments</li></ul>|push |email |Compute social engagement score
|Planning System||pull | email |
|Partner Clinics| Medical Record History<br/><ul><li>Records containing the medical evaluation results (and range)</li><li>National Provider Identifier</li></ul>Consent|pull|MRN (medical record number)|Health score
|Partner Dieticians||pull | MRN (medical record number)|
|Farmacy Food|Topics Consent||||
|Farmacy Food|Associated Customer segments||||
|Farmacy Food|Active nurturing workflow||||
|Farmacy Food|Associated campaigns||||

| Further Extensions |
|----------------|
|Tracking the engagement also for anonymous users → important for the customer acquisition (new Clients)|
