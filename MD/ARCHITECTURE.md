[kgrzybek/sample-dotnet-core-cqrs-api: Sample .NET Core REST API CQRS implementation with raw SQL and DDD using Clean Architecture.](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api)

> # Sample .NET Core REST API CQRS implementation with raw SQL and DDD using Clean Architecture.
>
> ## CI
>
> [![](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api/workflows/Build%20Pipeline/badge.svg)](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api/workflows/Build%20Pipeline/badge.svg)
>
> ## Give a Star! ![star](https://github.githubassets.com/images/icons/emoji/unicode/2b50.png)
>
> If you like this project, learn something or you are using it in your applications, please give it a star. Thanks!
>
> ## Description
>
> Sample .NET Core REST API application implemented with basic [CQRS](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/cqrs) approach and Domain Driven Design.
>
> ## Architecture [Clean Architecture](http://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
>
> [![projects_dependencies](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api/raw/master/docs/clean_architecture.jpg)](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api/blob/master/docs/clean_architecture.jpg)
>
> ## CQRS
>
> Read Model - executing raw SQL scripts on database views objects (using [Dapper](https://github.com/StackExchange/Dapper)).
>
> Write Model - Domain Driven Design approach (using Entity Framework Core).
>
> Commands/Queries/Domain Events handling using [MediatR](https://github.com/jbogard/MediatR) library.
>
> ## Domain
>
> [![projects_dependencies](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api/raw/master/docs/domain_model_diagram.png)](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api/blob/master/docs/domain_model_diagram.png)
>
> ## Validation
>
> Data validation using [FluentValidation](https://github.com/JeremySkinner/FluentValidation)
>
> Problem Details for HTTP APIs standard implementation using [ProblemDetails](https://github.com/khellang/Middleware/tree/master/src/ProblemDetails)
>
> ## Caching
>
> Using Cache-Aside pattern and in-memory cache.
>
> ## Integration
>
> Outbox Pattern implementation using [Quartz.NET](https://github.com/quartznet/quartznet)
>
> Related blog articles
> 
> 
> [Architecture Weekly #74 - 9th May 2022 - by Oskar Dudycz](https://www.architecture-weekly.com/p/architecture-weekly-74-9th-may-2022)

> I think that’s at least worth checking if you like it. If you do, here are some decent articles to start:
>
> -   [Ted Neward - Speaking Tips](https://blogs.newardassociates.com/speaking-tips/)
>
> -   [Hadi Hariri - Public Speaking - Should I speak?](https://hadihariri.com/2018/09/04/public-speaking-should-i-speak/)
>
>
> Last week, I wrote the article [Persistent vs catch-up, EventStoreDB subscriptions in action](https://event-driven.io/en/persistent_vs_catch_up_eventstoredb_subscriptions_in_action/). The split is confusing not only for newbies. If you’re using EventStoreDB or thinking about using it, check that.
>
> If you’re searching for knowledge rabbit holes, grab the whole conference recordings:
>
> -   [Citus Con: An Event for Postgres - All Recorded Talks](https://www.citusdata.com/cituscon/2022/schedule/#all-videos)
>
> -   [React Miami 2022 - Talks recordings](https://www.youtube.com/playlist?list=PL02pdjMT4gWxC3sYlCBzPBPptb6eUvIZv)
>
>
> Remember the embarrassing Jira accident? There’s a Post-Mortem already. I’m not convinced, are you?
>
> -   [Atlassian Engineering - Post-Incident Review on the Atlassian April 2022 outage](https://www.atlassian.com/engineering/post-incident-review-april-2022-outage)
>
>
> Check also other links!
>
> Cheers  
> Oskar
>
> **p.s.** I [invite you to join](https://www.architecture-weekly.com/subscribe?utm_source=menu&simple=true&next=https%3A%2F%2Fwww.architecture-weekly.com%2F) the **paid version of Architecture Weekly**. It already contains the exclusive Discord channel for subscribers (and my [GitHub sponsors](https://github.com/sponsors/oskardudycz)). Soon we’ll have the first live meeting. This is a great space for knowledge sharing. Don’t wait to be a part of it! On Friday, we’ll have the next webinar.
>
> **p.s.2. Ukraine is still under brutal Russian invasion. A lot of Ukrainian people are hurt, without shelter and need help.** You can help in various ways, for instance, directly helping refugees, spreading awareness, and putting pressure on your local government or companies. You can also support Ukraine by donating, e.g. to [Red Cross](https://redcross.org.ua/en/), the [Ukraine humanitarian organisation](https://savelife.in.ua/en/donate/). You may also consider joining [Tech for Ukraine](https://techtotherescue.org/tech/tech-for-ukraine) initiative.
>
> ### Architecture
>
> -   [Atlassian Engineering - Post-Incident Review on the Atlassian April 2022 outage](https://www.atlassian.com/engineering/post-incident-review-april-2022-outage)
>
> -   [T. Winters, T. Manshreck, H. Wright - Software Engineering at Google](https://abseil.io/resources/swe-book)
>
> -   [Derek Comartin - Real-World Event Driven Architecture! 4 Practical Examples](https://codeopinion.com/real-world-event-driven-architecture-4-practical-examples/)
>
> -   [Sophie Weston - How to optimize for speed and flow - insights from QCon London 2022](https://confluxdigital.net/news/how-to-optimize-for-speed-and-flow-insights-from-qcon-london-2022)
>
> -   [Rich Hickey - Persistent Data Structures and Managed References](https://www.youtube.com/watch?v=toD45DtVCFM)
>
> -   [Eric Siegel - Why Ice Cream Is Linked to Shark Attacks – Correlation/Causation Smackdown](https://www.kdnuggets.com/2019/01/dr-data-ice-cream-linked-shark-attacks.html)
>
>
> ## Databases
>
> -   [Oskar Dudycz - Persistent vs catch-up, EventStoreDB subscriptions in action](https://event-driven.io/en/persistent_vs_catch_up_eventstoredb_subscriptions_in_action/)
>
> -   [Citus Con: An Event for Postgres - All Recorded Talks](https://www.citusdata.com/cituscon/2022/schedule/#all-videos)
>
> -   [T. Kersten, V. Leis, A. Kemper, T. Neumann, A. Pavlo, P. Boncz - Everything You Always Wanted to Know About Compiled and Vectorized Queries But Were Afraid to Ask](https://www.vldb.org/pvldb/vol11/p2209-kersten.pdf)
>
>
> ## Frontend
>
> -   [React Miami 2022 - Talks recordings](https://www.youtube.com/playlist?list=PL02pdjMT4gWxC3sYlCBzPBPptb6eUvIZv)
>
> -   [Una Kravets - You might not need JavaScript](http://youmightnotneedjs.com/)
>
>
> ## AWS
>
> -   [Yan Cui - AWS Lambda: function URL is live!](https://lumigo.io/blog/aws-lambda-function-url-is-live/)
>
>
> ## Java
>
> -   [xalgord - Multi-Threaded Programming in Java](https://xalgord.in/multi-threaded-programming-in-java/)
>
> -   [Evgeniy Khyst - Event Sourcing with EventStoreDB](https://github.com/evgeniy-khist/eventstoredb-event-sourcing)
>
>
> ## .NET
>
> -   [.NET Blog - Microsoft Graph’s Journey to .NET 6](https://devblogs.microsoft.com/dotnet/microsoft-graph-dotnet-6-journey/)
>
> -   [Nicholas Blumhardt - The semantics of ILogger.BeginScope()](https://nblumhardt.com/2016/11/ilogger-beginscope/)
>
> -   [Tess Ferrandez - Debugging Labs - .NET and WinDbg](https://github.com/TessFerrandez/BuggyBits)
>
> -   [Jimmy Bogard - You Probably Don't Need to Worry About MediatR](https://jimmybogard.com/you-probably-dont-need-to-worry-about-mediatr/)
>
>
> ## TypeScript
>
> -   [Melvin George - How to convert an array into string literal union type in TypeScript?](https://melvingeorge.me/blog/convert-array-into-string-literal-union-type-typescript)
>
>
> ## Coding Life
>
> -   [Jeremy D. Miller - Why I hate the word “Pragmatic” and other rants](https://jeremydmiller.com/2014/06/19/pragmatic-and-other-rants/)
>
>
> ## Management
>
> -   [Anton Stöckl - 4 reasons why 4 is the perfect team size for (agile) software development](https://medium.com/@TonyBologni/4-reasons-why-4-is-the-perfect-team-size-for-agile-software-development-8597d33f3cfe)
>
>
> ## Product Design
>
> -   [John Cutler - TBM 20/54: "You're Making This Too Complicated"](https://cutlefish.substack.com/p/tbm-2054-youre-making-this-too-complicated?s=w)
>
>
> ## Industry
>
> -   [CNET - Google Revamps Employee Review System Following Criticism](https://www.cnet.com/tech/google-revamps-employee-review-system-following-criticism/)
>
> -   [Apple Together - Thoughts on Office-bound Work](https://appletogether.org/hotnews/thoughts-on-office-bound-work)
>
>
> ## Trivia
>
> -   [Ted Neward - Speaking Tips](https://blogs.newardassociates.com/speaking-tips/)
>
> -   [Hadi Hariri - Public Speaking - Should I speak?](https://hadihariri.com/2018/09/04/public-speaking-should-i-speak/)
>
> -   [Michael Liendo - The in-depth guide to selling digital products with AWS Amplify and Stripe](https://blog.focusotter.com/the-in-depth-guide-to-selling-digital-products-with-aws-amplify-and-stripe)
>
[Fortinet Training Institute](https://training.fortinet.com/)

> # Free Cybersecurity Training
>
> **Advanced training** for security professionals.  
> **Technical training** for IT professionals.  
> **Awareness training** for teleworkers.
>
> # Information Security Awareness and Training Service
>
> Create a cyber-aware workforce
>
> [Enroll Your Organization Today](https://www.fortinet.com/training/security-awareness-training)
>
> document.querySelector(".block\_carousel").classList.remove("pt-3","px-3"); document.querySelector(".card-body").style.padding = "0"; document.querySelector(".card-text").classList.remove("mt-3"); window.onload = function() {document.getElementById("region-main").children\[0\].style.minHeight = "0";}
>
> ![library-icon](https://training.fortinet.com/theme/kifer/pix/home/library-icon.jpg)
>
> # Library
>
> Browse courses across an array of topics and certification levels. The program includes a wide range of self-paced and instructor-led courses, as well as practical, experiential exercises that demonstrate mastery of complex network security concepts.
>
> [Browse Library»](https://training.fortinet.com/course/index.php)
>
> # Schedule
>
> Browse the online public training schedule and book a spot in an in-person or virtual class. In public training sessions, you share the learning experience with diverse Fortinet employees, business partners, and customers from all over the world.
>
> [Check Schedule»](https://training.fortinet.com/calendar/view.php)
>
> ![library-icon](https://training.fortinet.com/theme/kifer/pix/home/schedule-icon.jpg)
>
> ![library-icon](https://training.fortinet.com/theme/kifer/pix/home/certifications-icon.jpg)
>
> # Certifications
>
> NSE certifications serve as an objective indicator of the candidate’s technical knowledge and skills, which are valuable assets to the individual, as well as to current and future employers.
>
> [Explore Certifications»](https://training.fortinet.com/local/staticpage/view.php?page=nse)
>
> # Authorized Training Centers (ATC)
>
> Fortinet ATCs provide a global network of training centers that deliver expert-level training in local languages, in more than a hundred countries.
>
> [Find an ATC»](https://www.fortinet.com/support/training/learning-center.html)
>
> ![library-icon](https://training.fortinet.com/theme/kifer/pix/home/atc-icon.jpg)
>
> ![library-icon](https://training.fortinet.com/theme/kifer/pix/home/fnsa-icon.jpg)
>
> # Academic Partner Program
>
> The Academic Partner program provides institutions, such as K-12, higher education, and non-profit businesses that are focused on career readiness, with the resources to facilitate the Fortinet industry-recognized certification curriculum.
