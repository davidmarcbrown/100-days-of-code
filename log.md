# 100 Days Of Code - Log

### Day 1: June 2, 2017
**Today's Progress**: Created new projects, read through a pair of tutorials and watched a channel 9 video. The focus is ASP.Net Core authentication. I'd like to be able to use the API I'm building with a Xamarin mobile app. I'd also like a web front end because nothing annoys me more than those apps that have horrible/useless websites (I'm looking at you, Pinterest and Uber).

**Thoughts:** It wasn't really that difficult to set up individual accounts and authenticate users when I built [RubberCat](http://www.rubbercat.info). Why does dotnet seem like it's so much more complicated to set up? Looking to use JWT tokens, which should be fine for both web and native mobile clients.

**Links:**
[The Channel9 Video](https://channel9.msdn.com/Events/dotnetConf/2016/Building-Secure-Web-APIs-with-ASPNET-Core)
[ASP.NET Core Token Auth Guide](https://stormpath.com/blog/token-authentication-asp-net-core)

### Day 2: June 3, 2017
**Today's Progress**: Returning to the stable dotnet framework. Which means, fortunately, that I have a project already started. Opening the TarefinhasAPI project in VS 2017 required some kind of migration to a new project format. But even though the migration results indicated the migration was a success it hung VS. I think I'll just start a new project from scratch. Sticking with VS 2017 just because.

Sifted through the SPA template and I think I can use this as a base, and modify it for my use.

**Thoughts:** Trying to build this with Core was a mistake. It's just not ready yet. Core web api templates with individual accounts are not expected until the 2.0 version, and the current version is 1.1, I believe. I'll use the .NET framework for now and host on Azure.

**Links:**

### Day 3: June 4, 2017
**Today's Goal:** I want to take a closer look at the authentication in the SPA template. Can this be used on non-web clients? I'd also like to create the models and set up the code first migrations.

**Today's Progress:** I didn't change the user model or create any other models. Looking for a thorough explanation of individual *local* accounts on web api 2. Found this.

**Thoughts:** It looks like having an identity server as part of the app might be what is needed to implement tokens on individual accounts. The tut below should have a hint.

 **Links:**
 [](https://docs.microsoft.com/en-us/aspnet/web-api/overview/security/individual-accounts-in-web-api_)