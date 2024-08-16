# Shared library 🚀
In microservices, there are a common things that you'll need to repeat over and over again.
By creating a shared library, we try to limit `DRY` problems. You do that by putting all the most reccuring content in a single library.

In a production level we will convert the library into a nuget package that will be accessed by all services that need it ✨.

## Creating the project 🏗️
We will be using clean architecture to create our solution:
1. Create a blank solution and name it `DemoECommerce.SharedLibrarySolution` then click `Create`:

//image1

2. After creating the solution, add a `c#` class  library by right click on the solution, then select **add**:

//image2

3. The click **New Project**:

//image3

4. Search for **class library** then select the `c# class library` template, then click `Next`:

//image4

5. Click `Create`:

//image5

