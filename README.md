See https://github.com/mguinness/IdentityManagerUI for the main project.

## getting started

* clone
* open in visual studio. Ensure you have .net 6, asp net core 6 and identity components added (might all be from the C#/net core 6 web development workload).
  * the project is also configured to use MSSQL, via localdb for testing. This should be installed with visual studio. Change if required
* allow it to restore dependencies
* Tools > Package Manager > Console
* Run `Update-Database` to apply the migrations
* `F5` to run the project
* Navigate to `/IdentityManager/Home/Users` and `IdentityManager/Home/Roles` to see it in action

## notes

* Like the original project, all non-logged-in users are admin for development. Edit in `Program.cs`