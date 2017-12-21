# ASPNET-VueJS-Webpack-BoilerPlate
A boiler plate for creating SPA applications using VueJS/webpack and ASP.NET.

  Begin a new project with a basic starting point of a new VueJS project created from the Vue CLI tool while also utilizing ASPNET-Webpack and Microsoft SPA services to accomplish hot-reloading and compiling from within ASP.NET.
  
  How to start (assuming the use of vsCode):
    
    1. Open vscode and run git clone https://github.com/ZPDreamTeam/ASPNET-VueJS-Webpack-BoilerPlate.git from the command line.
    2. Open the ASPNET-VUEJS-WEBPACK-BOILERPLATE folder and change BoilerPlate.csproj to "yourprojectname".csproj.
    3. Open startup.cs and highlight the word "BoilerPlate" as in namespace BoilerPlate and click f2 and in the box type "yourprojectname".
    4. After you hit enter it will repalce all instances of BoilerPlate with "yourprojectname".
    5. Open client\package.json and change the desctiption, author, and name if you would like.
    
    
  Now you can run the following commands:
    
    1. 'dotnet restore' in the base directory of the project
    2. 'cd client'
    3. 'npm install'
    4. 'cd ..'
    5. 'dotnet watch run'
    
 Now your all set.  use dotnet watch run to run the server and watch for changes.  You can edit your client in the client/src folder and when you are ready to deploy the final version run the following commands:
 
    1. 'cd client'
    2. 'npm run build' (this is configured to copy the static files to /wwwroot folder).
    3. 'cd ..'
    4. 'dotnet publish -c release'

Your published files will be in bin\release.

Enjoy and let us know what we can do better!
