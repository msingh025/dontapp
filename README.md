# dontapp
. deploye the .net application using zip file , 
. this application source is from microsoft document . 
https://learn.microsoft.com/en-us/azure/app-service/app-service-web-tutorial-rest-api

. this application is in .net9 , 
.  checkout the code from 
`git clone https://github.com/Azure-Samples/dotnet-core-api
cd dotnet-core-api`
### create build using command . 

 ### 
 `dotnet publish dotnet-core-api.sln -c release -o build/`

 create zip of build folder 

 `zip -r build.zip build/` 

 and copy to the Dontap root folder .
commit and push to main barnch . and then workflow pipe will execute. 
