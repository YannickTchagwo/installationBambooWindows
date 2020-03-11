# installationBambooWindows
this repository show how we can install Bamboo on Windows

## 1. Download Bamboo
Download the executable file of Bamboo on the site https://www.atlassian.com/software/bamboo/download

## 2. Installation
Run the file in administrator mode to avoid possible authentication problems. Accept all the predefined configuration.

<strong>Caution</strong>: Please don't use such Admin directory (c:programm file) as directory for Bamboo. They may need authentication access to process each time.

## 3. Start Bamboo
To start bamboo
  - Execute cmd as administrator
  - Navigate to the bamboo file Installation
  - Execute ```bin\start-bamboo.bat```
  - Bamboo is now running on port 8085
  - Open a Web Browser and give ```127.0.0.1:8085```
  - Enter the License Key to activate your bamboo instance and choose custom installation
  - Fill the form to Setup your bamboo instance
    - For the Database:
      - choose the Embeeded one
    - For the Admin User you can create a generic user for the group
  -Bamboo is now working - Well done!
