# ContosoPizza

web API project tutorial C#
1. create/restore project: dotnet new webapi --no-https --force
2. Running the API: dotnet run
3. Usage .NET REPL: httprepl http://localhost:5000 ->  `exit`
4.  

Notes:
1. If run into error `error NU1100: Unable to resolve 'Swashbuckle.AspNetCore (>= 5.6.3)' for 'net5.0'.`:
  run this in cmd: dotnet nuget add source --name nuget.org https://api.nuget.org/v3/index.json
