# SDKBasedProjects
Scripts for migrating .NET projects to the new SDK-based projects

Use this PowerShell script to migrate an existing .NET project that uses the "old"-tooling to the new SDK-based tooling in
Visual Studio 2017.

**WARNING**
Use these scripts at your own risk. They have not been thoroughly tested. Make sure you have a backup of your project or
use version control (Git, TFVC, etc.). Also note that after migrating these projects can only be opened with Visual Studio
2017.

# Usage
.\MigrateToNewTooling.ps1 -TargetFolder <folder-containing-solution> [-Verbose]
