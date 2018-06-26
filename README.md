# ng5aspnetcore-booksapi
# Deploying Angular 5.2.2 with ASP.NET Core 2.0 Web API Application To Microsoft Azure using Github

Create a ASP.NET Core 2.0 Web API application, inside the project, created a Angular application with name ClientApp. In the .angular-cli.json, changed the outDir to wwwroot folder of Web API application. Once build the application, Angular CLI will build the application and generate index.html page, which will be deployed to wwwroot folder, which is the main entry point of the application. Modified Startup class code to handle the Angular routing. 

Ref. : https://dotnetthoughts.net/deploying-your-angular-app-to-azure/
