# Shared library 🚀
In microservices, there are a common things that you'll need to repeat over and over again.
By creating a shared library, we try to limit `DRY` problems. You do that by putting all the most reccuring content in a single library.

In a production level we will convert the library into a nuget package that will be accessed by all services that need it ✨.

<kbd>
  <img src="https://github.com/MinenhleNkosi/eCommerse-Microservice-.NET8/blob/main/Notes/1/Images/0.png" height="auto" width="1000" />
</kbd>

## Creating the project 🏗️
We will be using clean architecture to create our solution:
1. Create a blank solution and name it `DemoECommerce.SharedLibrarySolution` then click `Create`:

    <kbd>
      <img src="https://github.com/MinenhleNkosi/eCommerse-Microservice-.NET8/blob/main/Notes/1/Images/1.png" height="auto" width="800" />
    </kbd>

2. After creating the solution, add a `c#` class  library by right click on the solution, then select **add**:

    <kbd>
      <img src="https://github.com/MinenhleNkosi/eCommerse-Microservice-.NET8/blob/main/Notes/1/Images/2.png" height="auto" width="800" />
    </kbd>

3. The click **New Project**:

    <kbd>
      <img src="https://github.com/MinenhleNkosi/eCommerse-Microservice-.NET8/blob/main/Notes/1/Images/3.png" height="auto" width="800" />
    </kbd>

4. Search for **class library** then select the `c# class library` template, then click `Next`:

    <kbd>
      <img src="https://github.com/MinenhleNkosi/eCommerse-Microservice-.NET8/blob/main/Notes/1/Images/4.png" height="auto" width="800" />
    </kbd>

5. Click `Create`:

    <kbd>
      <img src="https://github.com/MinenhleNkosi/eCommerse-Microservice-.NET8/blob/main/Notes/1/Images/5.png" height="auto" width="800" />
    </kbd>

