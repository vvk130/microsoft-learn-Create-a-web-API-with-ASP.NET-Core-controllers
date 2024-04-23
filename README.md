Microsoft Learn: Create a web API with ASP.NET Core controllers

https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/9-summary

In this module, you created an ASP.NET Core web API running on .NET. The web API creates, reads, updates, and deletes pizzas from an in-memory cache.

You learned that creating a web API with ASP.NET Core entails:

    Creating a new application by using the ASP.NET Core Web API template.
    Creating classes that inherit from the ControllerBase class and that contain methods that respond to HTTP requests.

Because this pattern allows you to focus on a single controller action at a time, you can create functional web APIs fairly quickly with a little practice.

In this module, you used an in-memory cache. This approach helped you to focus on learning web API concepts, but it has some obvious limitations for real-world applications. If the application stops, all your changes are lost!

In a real-world application, you would store your data in a backing store, like a database. You can learn how to persist and retrieve relational data by using Entity Framework Core in this tutorial.
