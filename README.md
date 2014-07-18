CoAppDemoPackage
================

Demo package to explore proper way to publish C++ content

To use the demo:

1. Install CoApp tools
2. cd into the root directoy of this package
3. From powershell run "Write-NugetPackage PackageWithContent.autopkg
4. In another directory create a simple C++ project that contains a single source file that prints out hello world.
5. Point VSIDE's nuget to the directory where you build the nuget package with the Write-NuGetPacakge command
6. Import the package.
7. Build the app
8. Note that the dll is correctly copied to the output directory, but the etc files are not. Despite being in the unpacked redist package.
