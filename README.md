# readme-generator 
Using npm install to create prompt with many inputs, checkbox, and list, for user to answer the questions to generate a  README file. This README file contains basic information such as GitHub user name, email, project titles, description, and some of the technology used. 
## Site Picture
![Site]()

# Table of Contents 
[Tittle](#readme-generator)

[Site Picutre](#Site-picture)

[Table of Contents](#Table-of-Content)

[Description of Page Building ](#Description-of-Page-Building)

[Code Snippet](#Code-Snippet)

[Technologies Used](#Technologies-Used)

[Deployed Link](#Deployed-Link)

[Author](#Author)

[License](#License)


## Description of Page Building 
* Install npm init and npm install inquire 
  
* In index.js file  
  <ul> 
  <li> Create consts that require node's file system, util, and inquirer dependency
  <li> Add inquirer promt questions
  <li> Then apply temperlate literals that contains basic readme structure and get the values from userinput 
  <li> Write file using Node file system generate a Readme 
  <li> Make sure to use a call back function to catch err 
  </li>
  </ul>
    
* In README.md file 
  <ul>
  <li> Create title 
  <li> Add description 
  <li> Add author's name and email address
  <li> Include Technologies used 
  <li> Provide license 
  </li>
  </ul>



## Code Snippet
Install npm package 
 
npm install init 
npm install inquirer
Required consts 
``` Javascript
const inquirer = require("inquirer");
const fs = require("fs");
const util = require("util");
```

Template Literals 
``` Javascript
`
#${response.project}
${response.description}
## Description of Page Building 
- Command to install dependencies: ${response.command}
- Command to run test:  ${response.test}
## Technologies Used
-${response.usesage} - gives interacticve elements to web pages
-${response.contributing} - contribute to the repo
## Author
- [Github](${response.username})
- [Email](${response.email})
## License ${response.license}
`
```

## Technologies Used
- Node- whhat the heck is node
  * []()
- Git - version control system to track changes to source code
  * [Git](https://git-scm.com/)
- GitHub - hosts repository that can be deployed to GitHub Pages
  * [Github](https://github.com/)


## Deployed Link

* [See Live Site](https://vubao2303.github.io/weather-dashboard/)


## Author

* **B Tram Vu** 

- [Link to Portfolio Site](https://github.com/vubao2303)
- [Link to Github](https://github.com/vubao2303)
- [Link to LinkedIn](https://www.linkedin.com/in/tram-vu-866250121/)

## License

© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.