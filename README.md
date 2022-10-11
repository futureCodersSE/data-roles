# data-roles
A data collection and analysis project.  Finding the data roles being advertised across Kent.  Linking job roles to companies and identifying who hires data staff.

## Understanding data roles that exist locally
### Terms of reference:
#### Skills gap

It is widely accepted that there is a mismatch between the skills needed for a thriving, knowledge based economy and the skills present in the general UK population.  This has resulted in large numbers of job vacancies with a real lack of people with the right skills to fill those roles.  At the same time, the economy is predominantly made up of Small to Medium sized businesses (SMEs) who often don’t have the capacity to manage training on a large scale and can’t bring talent into their company unless someone else has put that training in place.  Government backed apprenticeships were introduced to try to address this problem, and to replace the work done by the large corporations of the past.  However, there is a mismatch between the demands of an apprenticeship, the level of training offered and the take up by people who are steered heavily towards university education as an alternative.  We think that this problem is acute in the field of data and software.

#### Data roles

Data analytics have always been an important part of a business’s function.  Knowing how many items are sold, what customers think, what is changing, where new markets or services are needed, is all part of business development, strategy, continuous improvement, etc.  Consequently, all businesses (including charitable businesses) will have a person, a team, a department, or a service provider, managing their data and performing a level of data analytics.

#### Investigation

We want to find out which companies, in Kent, employ people specifically in data roles.  These might include:
Data entry personnel
Data collectors
Data analysts
and others

#### Out of scope


## Requirements

To create a dataset containing all companies in Kent identified as having at least one person working in a data role.
For each company: 
The data roles that exist in each of these companies
Contact details for the company
Industry sector (from Companies House)

Criteria for inclusion:
Company must be based in Kent  or have a presence in Kent even if head office is elsewhere
Roles must contain the word ‘data’ 

Analysis required:
Roles grouped by role function (difficult to do - need to look at job descriptions)
Companies grouped by a particular role
Sectors grouped by particular role
Overall numbers (number of companies with a particular role in place, number of companies with 
Bar charts to visually represent a range of statistics (to be defined)
Use cases

AS a work experience/apprenticeship co-ordinator user
WHEN I need to contact companies to discuss placing a learner/apprentice
THEN I will be able to enter a role category to search for
AND I will see a list of Kent-based companies who have someone in that role
SO THAT I can create a mailing list

AS a content or bid writer user
WHEN I am writing an article about the skills gap in data roles
THEN I will be able to access statistics and charts generated from the data role dataset
AND I will be able to copy these into my article
SO THAT I have statistics to back up my arguments

AS a learner of data analysis/coding for data
WHEN I am looking for a placement or an apprenticeship
OR I am wanting to find out about the job roles available around me, in Kent
THEN I will be able to enter a role category to search for
AND I will see a list of Kent-based companies who have someone in that role
AND I will be able to choose a company and access a link to their website
SO THAT I can look further into the company to see if I might want to contact them


Data models
Data sources model v1:
Source and  
Search criteria
Link (url)
Date last accessed
Notes
E.g. Reed
E.g.
What: Data
Where: Kent
E.g. https://www.reed.co.uk/
E.g. 11/10/2022
E.g. Aggregates job listings from a range of other job sites.

Data roles model v1:

Role title
Advertiser
Employer ID
Employer name
Date seen
Min Salary















