# Vue3_.netAPI

You will need postgres installed on your machine or you can change the DB provider ef core is using following their docs https://learn.microsoft.com/en-us/ef/core/providers/?tabs=dotnet-core-cli

Before running project, go to the vue-client folder and run "yarn install" to install the front end dependencies for the application. 

# Run DB Migrations
You will also have to run Update-Database from the package manager console or the equivalent dotnet ef database update from the command line when in the root of the same directory as the csproj file.  

# Start the application
After that you can open up a terminal and run "dotnet run" in the same directory as the csproj file, or simply run from visual studio, up to you. 

The csproj file has the configuration to run the vue app when it starts up.

Enjoy
