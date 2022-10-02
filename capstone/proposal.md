# Proposal

## Business Problem

- Describe your project
    The idea is to figure out a way to classify with tagging different topics that bring more traffic to the site. The plan is to leverage [LDA](myLib/LDA_Unsupervised_Learning_Topic_Models.ipynb) or other models to classify the topics that are more successful 
- What business will it support?
    Platea PR
- What is the problem you are trying to solve?
    Getting more insight on the topics that make more impact in the way of more sessions or authenticated users.
- What has been the existing work to try to solve this problem?
    Getting social network reports weekly and getting a perception of what topics are better compared to the past. 

## Data
- What data will be required to solve this problem?
    The articles from WordPress. 
- Number sessions and authentication number from the warehouse we have available
- What types of features will be available to you?  
    - Articles (title and content)
    - Approximate count of sessions/login/signups per article
- What databases, tables contain the data you are concerned about?  
    1. WordPress [API](myLib/WP_.ipynb) 
        - Article Title
        - Article content
    2. CDW - Data Warehouse
        - Approximate count of sessions/login/signups per article
- Are there experts at RV that can help to describe the data you are concerned about?
    - Analysts that are familiar with these sources but the work of the anysis on this team is split.

## Approach

- How do you plan to collect the data?  
        WordPress through their [API](myLib/WP_.ipynb) 
        Data Warehouse. Via directly with Query and exporting what We care about.
- How will you visualize the information?  
        The minimum would be barchart that can measure sessions/authentication/logins vs topic
- What will you be looking for?
        The main goal is to identify what are the topics that are driving more traffic.
        Would be great if there is an article that was really successful but there is one or only a few that would be great since it identifies an area of opportunity that can be explored.

## Deliverables

- What are your intended deliverables? 
    Jupyter notebook.
    1-2 page final paper
    5 slide deck  5-minute presentation.
- Who is your intended audience?
    Platea Team more important content team.
- What action do you expect them to take?
    Being informed of which topics are more effective driving sessions and integrate that knowledge to the decisions on content strategy

## Impact and Evaluation
- How will you know if your project is successful or not?
    If we can find the topics that bring more traffic
- What metrics or change in behavior might you use to evaluate your impact?
    If the content team changes content strategy based on the results, and as result we see an increase in traffic.