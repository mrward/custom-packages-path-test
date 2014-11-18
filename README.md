Sample that shows three solutions each sharing the same packages directory.

Directory structure:

    /packages
    
    /ProjectA/ProjectA.sln
    /ProjectA/.nuget/NuGet.Config
    /ProjectA/ProjectA/ProjectA.csproj
    
    /ProjectB/ProjectB.sln
    /ProjectB/.nuget/NuGet.Config
    /ProjectB/ProjectB/ProjectB.csproj
    
    /Tests/ProjectC/ProjectC.sln
    /Tests/ProjectC/.nuget/NuGet.Config
    /Tests/ProjectC/ProjectC/ProjectC.csproj

Each solution has its own .nuget/NuGet.Config file which specifies where the packages directory is.

ProjectB.sln contains two projects: ProjectA and ProjectB

ProjectC.sln contains three projects: ProjectA, ProjectB and ProjectC.
