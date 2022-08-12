# Knowledge Wiki
A repo to store references for various technologies. For AWS visit here, for AWS ML visit here, and for Deep Learning, visit here.

## File Tree
find . -type f \( -name '*.md' -o -name '*.pkl' -o -name '*.csv' -o -name '*.sql' -o -name '*.py' -o -name '*.png' \) | sort -t '/' -k 1 -k 2 | awk -v base=https://github.com/Shavvimal/personal_wiki/blob/main/ -f ./scr.bash >> README.md

 * 1_Environment_Setup/
     + [1.1_Pre_Work.md](https://github.com/Shavvimal/personal_wiki/blob/main/1_Environment_Setup/1.1_Pre_Work.md)
     + [1.2_MacOS_Setup.md](https://github.com/Shavvimal/personal_wiki/blob/main/1_Environment_Setup/1.2_MacOS_Setup.md)
     + [1.3_Windows_Setup.md](https://github.com/Shavvimal/personal_wiki/blob/main/1_Environment_Setup/1.3_Windows_Setup.md)
     + [1.4_Linux-and-WSL-Setup.md](https://github.com/Shavvimal/personal_wiki/blob/main/1_Environment_Setup/1.4_Linux-and-WSL-Setup.md)
 * 2_HTML_CSS/
     + [2.1_Warm-Up-Week.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.1_Warm-Up-Week.md)
     + [2.10_Basic-AWS-Setup.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.10_Basic-AWS-Setup.md)
     + [2.11_Deploy-101.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.11_Deploy-101.md)
     + [2.12_CSS-Selectors-Cheatsheet.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.12_CSS-Selectors-Cheatsheet.md)
     + [2.13_git-CLI-Cheatsheet.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.13_git-CLI-Cheatsheet.md)
     + [2.14_Writing-READMEs.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.14_Writing-READMEs.md)
     + [2.15_Pnpm.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.15_Pnpm.md)
     + [2.2_HTML-Basics.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.2_HTML-Basics.md)
     + [2.3_CSS-Basics.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.3_CSS-Basics.md)
     + [2.4_Site-Planning-and-Layout.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.4_Site-Planning-and-Layout.md)
     + [2.5_Frameworks.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.5_Frameworks.md)
     + [2.6_Responsive-Design.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.6_Responsive-Design.md)
     + [2.7_Just-Enough-JavaScript.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.7_Just-Enough-JavaScript.md)
     + [2.8_Intro-to-TDD.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.8_Intro-to-TDD.md)
     + [2.9_JS-Unit-Testing-with-Jest.md](https://github.com/Shavvimal/personal_wiki/blob/main/2_HTML_CSS/2.9_JS-Unit-Testing-with-Jest.md)
 * 3_JavaScript/
     + [3.1_LAP-1.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.1_LAP-1.md)
     + [3.10_Object-Orientation-in-JavaScript.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.10_Object-Orientation-in-JavaScript.md)
     + [3.11_JavaScript-as-a-Backend.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.11_JavaScript-as-a-Backend.md)
     + [3.12_JavaScript-API-Frameworks.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.12_JavaScript-API-Frameworks.md)
     + 3.13_Testing/
         - [3.13.1_JS-Unit-Testing-with-Jest.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.13_Testing/3.13.1_JS-Unit-Testing-with-Jest.md)
         - [3.13.2_JS-Unit-Testing-with-Mocha-and-Chai.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.13_Testing/3.13.2_JS-Unit-Testing-with-Mocha-and-Chai.md)
         - [3.13.3_DOM-Testing.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.13_Testing/3.13.3_DOM-Testing.md)
         - [3.13.4_API-Endpoint-Testing-with-Supertest.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.13_Testing/3.13.4_API-Endpoint-Testing-with-Supertest.md)
         - [3.13.5_Mocking-Functions-and-Modules-for-Testing-with-Jest.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.13_Testing/3.13.5_Mocking-Functions-and-Modules-for-Testing-with-Jest.md)
         - [3.13.6_Mocking-Fetch-Requests-for-Testing-with-Jest.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.13_Testing/3.13.6_Mocking-Fetch-Requests-for-Testing-with-Jest.md)
     + [3.14_Publishing-an-NPM-package.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.14_Publishing-an-NPM-package.md)
     + [3.15_Browserify.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.15_Browserify.md)
     + [3.16_Watchify-Simple-Client-Side-Dev-Server.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.16_Watchify-Simple-Client-Side-Dev-Server.md)
     + [3.17_Deploying-an-Express-API-to-Heroku.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.17_Deploying-an-Express-API-to-Heroku.md)
     + [3.18_AWS-Lambda.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.18_AWS-Lambda.md)
     + [3.19_Deploying-a-Full-Stack-Application.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.19_Deploying-a-Full-Stack-Application.md)
     + [3.2_Principles-of-Programming.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.2_Principles-of-Programming.md)
     + [3.20_Call-vs-Apply-vs-Bind.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.20_Call-vs-Apply-vs-Bind.md)
     + [3.21_Intro-to-Socket.IO.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.21_Intro-to-Socket.IO.md)
     + [3.3_Programming-Languages-Q&A.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.3_Programming-Languages-Q&A.md)
     + [3.4_Data-in-JavaScript.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.4_Data-in-JavaScript.md)
     + [3.5_Logic-in-JavaScript.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.5_Logic-in-JavaScript.md)
     + [3.6_Actions-in-JavaScript.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.6_Actions-in-JavaScript.md)
     + [3.7_JavaScript-in-the-Browser.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.7_JavaScript-in-the-Browser.md)
     + [3.8_Forms-and-APIs.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.8_Forms-and-APIs.md)
     + [3.9_Asynchronous-Processes-and-Promises.md](https://github.com/Shavvimal/personal_wiki/blob/main/3_JavaScript/3.9_Asynchronous-Processes-and-Promises.md)
 * 4_Databases_Cyber_Security_and_Architecture/
     + [4.1_LAP-2.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.1_LAP-2.md)
     + [4.10_Intro-to-Cybersecurity.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.10_Intro-to-Cybersecurity.md)
     + [4.11_PRG-Pattern.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.11_PRG-Pattern.md)
     + [4.12_AWS-Deployment.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.12_AWS-Deployment.md)
     + [4.13_Deploying-a-Database.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.13_Deploying-a-Database.md)
     + [4.14_Postgres_Docker_timescaledb.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.14_Postgres_Docker_timescaledb.md)
     + [4.15_psql_cheatsheet.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.15_psql_cheatsheet.md)
     + [4.2_Intro-to-System-Architecture.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.2_Intro-to-System-Architecture.md)
     + [4.3_Intro-to-Databases.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.3_Intro-to-Databases.md)
     + [4.4_Internet-Protocols-&-API-Design.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.4_Internet-Protocols-&-API-Design.md)
     + [4.5_NoSQL.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.5_NoSQL.md)
     + [4.6_SQL.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.6_SQL.md)
     + [4.7_Connecting-Webapps-to-Databases.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.7_Connecting-Webapps-to-Databases.md)
     + [4.8_Authentication-and-Authorisation.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.8_Authentication-and-Authorisation.md)
     + [4.9_Performance.md](https://github.com/Shavvimal/personal_wiki/blob/main/4_Databases_Cyber_Security_and_Architecture/4.9_Performance.md)
 * 5_React_TDD_Environment_Management/
     + [5.1_LAP-3.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.1_LAP-3.md)
     + [5.10_React-useEffect.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.10_React-useEffect.md)
     + [5.11_React-Navigation.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.11_React-Navigation.md)
     + [5.12_React-Advanced-Hooks.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.12_React-Advanced-Hooks.md)
     + [5.13_Redux.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.13_Redux.md)
     + [5.14_Intro-to-DevOps.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.14_Intro-to-DevOps.md)
     + [5.15_React-Deploy-with-Netlify.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.15_React-Deploy-with-Netlify.md)
     + [5.16_Using-dotenv-with-webpack.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.16_Using-dotenv-with-webpack.md)
     + [5.17_React-Component-Lifecycle-Methods.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.17_React-Component-Lifecycle-Methods.md)
     + [5.18_React-Navigation-RRv5.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.18_React-Navigation-RRv5.md)
     + [5.2_Intro-to-Module-Bundlers-and-Webpack.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.2_Intro-to-Module-Bundlers-and-Webpack.md)
     + [5.3_Intro-to-React.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.3_Intro-to-React.md)
     + [5.4_Testing_React_Jest_and_React_testing_library.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.4_Testing_React_Jest_and_React_testing_library.md)
     + [5.5_Testing-React_Jest_and_Enzyme.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.5_Testing-React_Jest_and_Enzyme.md)
     + [5.6_CDD-&-Storybook-JS.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.6_CDD-&-Storybook-JS.md)
     + [5.6_Intro-to-React-Hooks.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.6_Intro-to-React-Hooks.md)
     + [5.7_React-State-and-Eventing-(Class-Components).md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.7_React-State-and-Eventing-(Class-Components).md)
     + [5.8_React-State-and-Eventing-(Functional-Components).md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.8_React-State-and-Eventing-(Functional-Components).md)
     + [5.9_React-Props.md](https://github.com/Shavvimal/personal_wiki/blob/main/5_React_TDD_Environment_Management/5.9_React-Props.md)
 * 6_Python_Data_Science_Intro/
     + [6.1_LAP-4.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.1_LAP-4.md)
     + [6.10_Virtual-Environment.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.10_Virtual-Environment.md)
     + [6.11_Django-Class-Based-Views.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.11_Django-Class-Based-Views.md)
     + [6.12_Django-REST-Framework.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.12_Django-REST-Framework.md)
     + [6.13_MongoDB-Atlas.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.13_MongoDB-Atlas.md)
     + [6.2_Intro-to-Python.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.2_Intro-to-Python.md)
     + [6.3_Procedural-Python.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.3_Procedural-Python.md)
     + [6.4_OO-Python.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.4_OO-Python.md)
     + [6.5_Flask.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.5_Flask.md)
     + [6.6_Django.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.6_Django.md)
     + [6.7_Testing-with-Pytest.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.7_Testing-with-Pytest.md)
     + [6.8_Data-Manipulation.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.8_Data-Manipulation.md)
     + [6.9_Intro-to-Data-Science.md](https://github.com/Shavvimal/personal_wiki/blob/main/6_Python_Data_Science_Intro/6.9_Intro-to-Data-Science.md)
 * 7_Docker/
     + [7.1_Setting-up-Containers-with-VS-Code.md](https://github.com/Shavvimal/personal_wiki/blob/main/7_Docker/7.1_Setting-up-Containers-with-VS-Code.md)
     + [7.2_Docker-101-Cheatsheet.md](https://github.com/Shavvimal/personal_wiki/blob/main/7_Docker/7.2_Docker-101-Cheatsheet.md)
     + [7.3_Docker-Compose-101.md](https://github.com/Shavvimal/personal_wiki/blob/main/7_Docker/7.3_Docker-Compose-101.md)
     + [Docker-&-AWS-EC2-Deployment.md](https://github.com/Shavvimal/personal_wiki/blob/main/7_Docker/Docker-&-AWS-EC2-Deployment.md)
 * 8_AWS/
     + [Deployment-101-with-AWS-S3.md](https://github.com/Shavvimal/personal_wiki/blob/main/8_AWS/Deployment-101-with-AWS-S3.md)
 * 9_README/
     + [9.1_Markdown-Cheatsheet.md](https://github.com/Shavvimal/personal_wiki/blob/main/9_README/9.1_Markdown-Cheatsheet.md)
     + [9.2_Markdown-Here-Cheatsheet.md](https://github.com/Shavvimal/personal_wiki/blob/main/9_README/9.2_Markdown-Here-Cheatsheet.md)
     + [9.3_Other-Markdown-Tools.md](https://github.com/Shavvimal/personal_wiki/blob/main/9_README/9.3_Other-Markdown-Tools.md)
 * [README.md](https://github.com/Shavvimal/personal_wiki/blob/main/README.md)
