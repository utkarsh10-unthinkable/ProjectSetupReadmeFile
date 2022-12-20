# **Documentation For Project Setup(Xdock And TransloadPro)BackEnd**

### 1. Project Tools Requirement:
```
A.Visual Studio 2022
B.Net Version 6.0 and above 
C.Microsoft SQL Server Management Studio 18
D.SSL VPN Client
```
### 2. Prerequisite Knowledge:

```
A.Basic Understanding of Visual Studio Such as how to Build Solution,Open File and Solution Explorer.
B.Some basic Understanding of .net core to Understand code flow and Syntax.
C.Understanding of how to write sql command,Create Stored Procedures.
```
### 3. Tools Installation:

  - [Install Visuals Studio 2022](https://visualstudio.microsoft.com/vs/)
  - After Setup Visual Studio,[install the .net version 6.0](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)
  - [Install Microsoft SQL Server Management Studio 18](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)
  - [Install SSL VPN Client](https://drive.google.com/file/d/13mqiTjCki64WW23lRzyPYaHJWkwov4hg/view?ts=5dee7254)


### 4.Project Setup Steps:

  - Connect the Database with the credentials provide By Client and before connecting check wheather 
  you have an active connection with SSL VPN Client
  - Clone the project from Bitbucket.
  - Checkout to the development branch.
  - Take pull from the development branch.
  - Check git status,It should be already up to date.
  - Open Visual Studio click **"Continue without code ->"**
  - In Menu Section Click on **"File->Open->Web Site"**
  - Open the project directory (Cloned in Step-1)
  - Starting the project, it will give an error "Solution is not saved. Please save your solution before 
  managing NuGet packages."
  - Close Visual Studio without closing the project. It will ask to save the solution.
  - Save the solution outside the Cloned project directory.
  - Now go to the Solution directory, and click on solution. It will open the project in Visual Studio.
  - Start project, continue with the last successful build.


