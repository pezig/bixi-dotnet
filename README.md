# bixi-dotnet

## Prerequisites

Ensure you have an environment variable called **ASPNETCORE_Environment** with a value of Development. On Windows (in non-PowerShell prompts), run `SET ASPNETCORE_Environment=Development`. On Linux or macOS, run `export ASPNETCORE_Environment=Development`.

## Setup

Run `dotnet build` to verify the app builds correctly. On the first run, the build process restores npm dependencies, which can take several minutes. Subsequent builds are much faster.

## Run

Run `dotnet run` to start the app. A message similar to the following is logged:

````
Now listening on: http://localhost:\<port\>
````

Navigate to this URL in a browser.


Warning |
:------------ | 
The app starts up an instance of the Angular CLI server in the background. A message similar to the following is logged: NG Live Development Server is listening on localhost:<otherport>, open a browser to http://localhost:\<otherport\>/. Ignore this message—it's not the URL for the combined ASP.NET Core and Angular CLI app. | 
