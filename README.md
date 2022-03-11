# Create ASP.NET-App
1. Clone or download source files.
2. Open the project with Visual Studio.
3. Build your project.
4. Publish project.

# Run with IIS On Microsoft machine
1. Open IIS
2. Add new Application Pool.
3. Add new website, enter port 5100.
4. transfer file from bin\Release\net5.0\publish to C:\inetpub\wwwroot\<projectName> at windows machine using RDP.
5. enter IIS and click " Browse *:5100 ".
6. Browse to http://localhost:5100/ from your windows machine.
