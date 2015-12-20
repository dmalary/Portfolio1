# Portfolio1


Personal Portfolio
--
Links:

- Project:
    - GitHub
        - https://github.com/madhat5/Portfolio1
    - Github.io link
    	- http://madhat5.github.io/Portfolio1/
    - Wireframes
        - 
    - Trello link
        - 

--
Deployment flow:

- Create development & gh-pages branch
    - from master
        - git checkout -b development
        - git checkout -b gh-pages
- Pull @ beginning of day
    - from development
        - git pull origin master
- Create 1 branch per file feature
    - from development
        - git checkout -b file_feature
- By end of day 
    - from branch
        - git add .
        - git commit -m "update details"
        - git push origin file_feature
        - (gitHub
            - Pull request)
        - OR
        - (git push origin development)
        - git checkout development
    - from development
    - (gitHub
        - Pull request)
    - OR
    - (git push origin master)
    - from gh-pages
    	- git pull origin master


