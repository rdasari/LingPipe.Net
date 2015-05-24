Developers Guide to LingPipe on .NET
===============================

This project is a simple wrapper around the very excellent Java Library [LingPipe](http://alias-i.com/lingpipe/) which is used for processing text and computational linguistics.



##Steps for building lingpipe-app  .NET Assembly##

1. Downloaded [IKVM](http://www.ikvm.net/). 
2. Extracted the zip file to IKVM Directory
3. From the command prompt executed the following command
ikvmc.exe -target:library -assembly:lingpipe-app -classloader:ikvm.runtime.AppDomainAssemblyClassLoader lingpipe-4.1.0.jar
4. The resultant is .net Assembly and referenced in my Visual Studio Solution for Demo Application

##Description Of Folders##
1. IKVM - IKVM Runtime Used to Generate .NET Assembly
2. Lib - Generated .NET Assembly and the version of Jar file used 
3. LingPipeOnDotNetDemos - Visual studio solution containing Examples 
4. RequiredFilesForDemo - Files Required(data/models) to Run the Visual studio solution	

##Demo Application##

I have Included Number of Examples in [Visual Studio Demo Application](https://github.com/sunilpottumuttu/LingPipe.Net/tree/master/LingPipeOnDotNetDemos)

