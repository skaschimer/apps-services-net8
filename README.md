> **IMPORTANT!** [Information for Technical Reviewers](docs/reviewers.md)

[Common Mistakes, Improvements, and Errata aka list of corrections](docs/errata/README.md)

# Apps and Services with .NET 8, Second Edition

Repository for the Packt Publishing book titled "Apps and Services with .NET 8" by Mark J. Price

This book is expected to publish in December 2023.

My author page on Amazon: https://www.amazon.com/Mark-J-Price/e/B071DW3QGN/ 

All of my books on my publisher Packt's website: https://subscription.packtpub.com/search?query=mark+j.+price

## Code solutions for Visual Studio 2022 and Visual Studio Code

Visual Studio Code now has an extension named C# Dev Kit that includes a Solution Explorer so it can better work with Visual Studio 2022 solution files. All three Microsoft code editors/IDEs, Visual Studio 2022 for Windows, Visual Studio 2022 for Mac, and Visual Studio Code + C# Dev Kit can now use the same code solution files and projects for each chapter: [/code](/code). 

> **For Visual Studio Code:** To use the chapter solution files with Visual Studio Code, install the **C# Dev Kit** extension. Then open the `ChapterNN` folder that contains a `ChapterNN.sln` solution file and wait for the **SOLUTION EXPLORER** pane to appear at the bottom of the **EXPLORER**. You can drag and drop to reorder the panes to put **SOLUTION EXPLORER** at the top. Learn more about the C# Dev Kit at the following link: https://devblogs.microsoft.com/visualstudio/announcing-csharp-dev-kit-for-visual-studio-code/

> **Warning!** If you use both Visual Studio 2022 and Visual Studio Code to open these solutions, be aware that the build process can conflict. This is because Visual Studio 2022 has its own non-standard build server that is different from the standard build server used by .NET SDK CLI. My recommendation is to only have a solution open in one code editor at any time. You should also clean the solutions between opening in different code editors. For example, after closing the solution in one code editor, I delete the `bin` and `obj` folders before then opening in a different code editor.

## Chapters

**Introduction**
- Chapter 1 Introducing Apps and Services with .NET

**Data**
- Chapter 2 Managing Relational Data Using SQL Server
- Chapter 3 Building Entity Models for SQL Server Using EF Core
- Chapter 4 Managing NoSQL Data Using Azure Cosmos DB

**Specialized Libraries**
- Chapter 5 Multitasking and Concurrency
- Chapter 6 Implementing Popular Third-Party Libraries
- Chapter 7 Handling Dates, Times, and Internationalization

**Services**
- Chapter 8 Building and Securing Web Services Using Minimal APIs
- Chapter 9 Caching, Queuing, and Resilient Background Services
- Chapter 10 Building Serverless Nanoservices Using Azure Functions
- Chapter 11 Broadcasting Real-Time Communication Using SignalR
- Chapter 12 Combining Data Sources Using GraphQL
- Chapter 13 Building Efficient Microservices Using gRPC

**Apps**
- Chapter 14 Building Web User Interfaces Using ASP.NET Core
- Chapter 15 Building Web Components Using Blazor
- Chapter 16 Leveraging Open-Source Blazor Component Libraries
- Chapter 17 Building Mobile and Desktop Apps Using .NET MAUI
- Chapter 18 Implementing Model-View-ViewModel for .NET MAUI
- Chapter 19 Integrating .NET MAUI Apps with Blazor and Native Platforms
- Chapter 20 Introducing the Survey Project Challenge

## Extra content to download

The appendix and color figures are available to download as PDFs:

- Appendix A, Answers to the Test Your Knowledge Questions: coming December 2023.
- Color images of the screenshots/diagrams used in this book: coming December 2023.

## Important
Corrections for typos and other mistakes and improvements like refactoring code. Useful links to other related material. 
- [Command-Lines](docs/command-lines.md) page lists all commands as a single line that can be copied and pasted to make it easier to enter commands at the prompt.
- [Book Links](docs/book-links.md)
- [Common Mistakes, Improvements, and Errata aka list of corrections](docs/errata/README.md)
- [Second edition's support for .NET 9](docs/dotnet9.md)

## Microsoft Certifications
Microsoft used to have exams and certifications for developers that covered skills like C# and ASP.NET. Sadly, they have retired them all. These days, the only developer-adjacent exams and certifications are for Azure or Power Platform, as you can see from the certification poster: https://aka.ms/traincertposter

## Microsoft .NET community support
- [.NET Developer Community](https://dotnet.microsoft.com/platform/community)
- [.NET Tech Community Forums for topic discussions](https://techcommunity.microsoft.com/t5/net/ct-p/dotnet)
- [Q&A for .NET to get your questions answered](https://docs.microsoft.com/en-us/answers/products/dotnet)
- [Technical questions about the C# programming language](https://docs.microsoft.com/en-us/answers/topics/dotnet-csharp.html)
- [If you'd like to apply to be a reviewer](https://authors.packtpub.com/reviewers/)

## Interviews with me
Podcast interviews with me:
- [The .NET Core Podcast - March 3, 2023](https://dotnetcore.show/episode-117-our-perspectives-on-the-future-of-net-with-mark-j-price/)
- [Yet Another Podcast with Jesse Liberty - December 2022](https://jesseliberty.com/2022/12/10/mark-price-on-c-11-fixed/)
- [The .NET Core Podcast - February 4, 2022](https://dotnetcore.show/episode-91-c-sharp-10-and-dotnet-6-with-mark-j-price/)
- [Yet Another Podcast with Jesse Liberty - May 2021](http://jesseliberty.com/2021/05/16/mark-price-on-c9-and-net-6/)
- [The .NET Core Podcast - February 7, 2020](https://dotnetcore.show/episode-44-learning-net-core-with-mark-j-price/)
- [Yet Another Podcast with Jesse Liberty - February 2020](http://jesseliberty.com/2020/02/23/mark-price-c-net-core/)
- [Packt Podcasts](https://soundcloud.com/packt-podcasts/csharp-8-dotnet-core-3-the-evolution-of-the-microsoft-ecosystem)

Written interviews with me:
- [C# 9 and .NET 5: Book Review and Q&A](https://www.infoq.com/articles/book-interview-mark-price/?itm_source=infoq&itm_campaign=user_page&itm_medium=link)
- [Q&A with Episerver's Mark J. Price, author of C# 9 and .NET 5 - Modern Cross-Platform Development](https://www.episerver.com/articles/q-and-a-with-mark-price)
