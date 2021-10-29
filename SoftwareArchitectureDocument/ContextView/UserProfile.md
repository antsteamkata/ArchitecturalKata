## User Profile

# Goals
1. Have a 360 degree view of the customer in order to provide relevant and seamless content to targeted users on different channels of engagement
2. Nurturing the transactional customer in order to become an engaged customer through automated workflow based campaigns
3. Generating engagement scores for the customers
4. Farmacy Family to become a digital lifestyle provider for the communities

# Assumptions
- The forum is not a closed community
- The forum offers an engagement score and rating for an user
- Facebook Login is available
- There will be a Farmacy Family Insta/Facebook page

# Profile Data
| Source | Data | Method | Mapping | Scoring
|----------------|-------------------------------|-------|-------|------------|
|Farmacy Food|Transactional Customer Data  |push |email
|Forum|Engagement Score |pull |email |Sentiment analysis based on conversation threads
|Social Media|Facebook Login|push |email |Compute social engagement score
|Planning System||pull | email |
|Partner Clinics| Medical Record History|pull|MRN (medical record number)|Health score
|Partner Dieticians||pull | MRN (medical record number)|
|Farmacy Food|Topics Consent||||
|Farmacy Food|Associated Customer segments||||
|Farmacy Food|Active nurturing workflow||||
|Farmacy Food|Associated campaigns||||

| Extensions |
|----------------|
|Tracking the engagement also for anonymous users → important for the customer acquisition (new Clients)|

# Open Points
- how to capture consent from Customer and fetch later the medical record? can be done via SSN/MRN (medical record number) captured in onboarding? 