# Marketing-Analytics---Apprenda


## Business Context
Apprenda is a software company that provides a platform-as-a-service (PaaS) solution to other companies to help them manage their applications. They sell their service to many clients in order to generate revenue. The biggest client of theirs, JPMorgan Chase, has the largest platform-as-a-service in the world with over 3,000 applications which makes Apprenda one of the biggest platform-as-a-service providers in the world. Their main competitors include Red Hat and Pivotal. These three companies are leaders in the platform-as-a-service industry. Apprenda tends to sell to companies with 10,000 plus employees and companies with revenues over 2 billion. 

## Problem Understanding
To characterize the factors that can help turn a lead to an opportunity, we are dealing with a supervised learning problem. This step is crucial because it increases exposure to Apprenda as a PaaS. An opportunity can be focused closer down the pipeline and given individual attention due to a growing sales team in Apprenda. Potential clients are divided into four hierarchies from Lead, MQL (Marketing Qualified Lead), SQL (Sales Qualified Lead) to Opportunity a shown in the image below.The marketing team tracks and records each potential client as they move through the funnel. Clients that enter Sales department are divided into more segments than in marketing. The supervised classification will identify whether a lead turns to an opportunity or not. 

## Machine Learning Plan
- split the data set with a set of input objects and corresponding outputs collected from client (Apprenda) into training data and testing data
- create some features by transforming input objects
- select the most appropriate ones based on the structure of the learned function
- evaluate models using testing data
- choose the optimal model with the highest degree of business use and implement it for mapping new examples in Apprenda’s case

## Conclusions
Some key variables found that impact leads turning into an opportunity include:
- Company size by employee - the threshold of 100,000 employees and over will make it more likely for the lead to turn to an opportunity.
- Leads- Each additional lead you know in the prospective company will make it 1.15 times more likely to close to an opportunity.
- Technical employees- knowing a technical employee in the company makes it 2 times more likely to turn to an opportunity.
- Pardot scores are extremely good predictors and should be used and modified to take into account new activities or campaigns.
- Business employees- not very helpful in turning leads into opportunities deal.
- Chief (C-suite) or Director- knowing these leads will make it 3-4 times likely to close to an opportunity.
- Each additional campaign/activity make it less likely to turn to an opportunity. (The leads don’t want to be barraged by marketing emails)

