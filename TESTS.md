# Is .NET 6 better than .NET Framework?
* Modern .NET is modularized compared to the legacy .NET Framework, which is monolithic. 
* It is open source and Microsoft makes decisions about improvements and changes in the open. 
* Microsoft has put particular effort into improving the performance of modern .NET.
* It is smaller than the last version of .NET Framework due to the removal of legacy and non- cross-platform technologies.
* NET 6 has a single BCL and two CLRs: CoreCLR is optimized for server or desktop scenarios like websites and Windows desktop apps, and the Mono runtime is optimized for mobile and web browser apps that have limited resources

# What is .NET Standard and why is it still important?
In 2019 was that there were three forked .NET platforms controlled by Microsoft, as shown in the following list: 
• .NET Core : For cross-platform and new apps 
• .NET Framework : For legacy apps 
• Xamarin : For mobile apps

Each had strengths and weaknesses because they were all designed for different scenarios. This led to the problem that a developer had to learn three platforms, each with annoying quirks and limitations.
Because of that, Microsoft defined .NET Standard – **a specification for a set of APIs that all .NET platforms could implement to indicate what level of compatibility they have**. For example, basic support is indicated by a platform being compliant with .NET Standard 1.4. 
With .NET Standard 2.0 and later, Microsoft made all three platforms converge on a modern minimum standard, which made it much easier for developers to share code between any flavor of .NET.

# Why can a programmer use different languages, for example, C# and F#, to write applications that run on .NET? 

# What is the name of the entry point method of a .NET console application and how should it be declared? 
It's the Main() method.

# What is a top-level program and how do you access any command-line arguments? 
It's a program without the definition of the Program class.

# What do you type at the prompt to build and execute C# source code? 
dotnet run

# What are some benefits of using .NET Interactive Notebooks to write C# code? 

# Where would you look for help for a C# keyword? 

# Where would you look for solutions to common programming problems?