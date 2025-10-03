# Backend Parser Power BI 

This project parses the saved SemanticModel and Report files when you connect Power BI to GitHub. This is a solution I architected for my Data Science team to make reviewing the contents of our dashboards faster. To run this, you need a PAT from GitHub as well as the name of the repository, the branch the files are located on, the organization the repository is saved under, and the repository name itself. The function returns a series of tables that a reviewer can play around with to better understand the data feeding a dashboard. 
