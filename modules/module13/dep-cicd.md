# Module 13 - CI/CD

**Continuous integration** (**CI**) and **continuous delivery** (**CD**) embody a culture, set of operating principles, and collection of practices that enable application development teams to deliver code changes more frequently and reliably. The implementation is also known as the **CI**/**CD** pipeline. 

**Continuous integration** is a coding philosophy and set of practices that drive development teams to implement small changes and check in code to version control repositories frequently. Because most modern applications require developing code in different platforms and tools, the team needs a mechanism to integrate and validate its changes.

**Continuous delivery** picks up where continuous integration ends. **CD** automates the delivery of applications to selected infrastructure environments. Most teams work with multiple environments other than the production, such as development and testing environments, and **CD** ensures there is an automated way to push code changes to them.

You should focus on such themes:
* **CI/CD** overview in particulat;
* **CI/CD** tools and solutions:
  * **Azure DevOps Server**;
  * **Jenkins**;
  * **TeamCity**;

### Links to internet resources
* [CI/CD overview](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment) - here you can find basic information about CI/CD, what and where to choose, etc.; **(EN)**
* [Azure DevOps Server - Build, test, and deploy .NET Core apps](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/dotnet-core?view=azure-devops) - here you can find information how to setup basic **CI/CD** for **.NET Core** applications using **Azure DevOps Server**;
* [Jenkins - Build, test, and deploy .NET Core apps](https://medium.com/faun/net-core-projects-ci-cd-with-jenkins-ubuntu-and-nginx-642aa9d272c9) - here you can find information how to setup basic **CI/CD** for **.NET Core** applications using **Jenkins**;
* [TeamCity - Build, test, and deploy .NET Core apps](https://medium.com/monkii/how-to-deploy-asp-net-core-sites-using-teamcity-or-just-command-line-cf05fdee58f5) - here you can find information how to setup basic **CI/CD** for **.NET Core** applications using **TeamCity**;
* [CI/CD solutions comparison](https://blog.elmah.io/comparing-the-top-6-net-continuous-integration-build-servers/) - here you can find comparison of most common **CI/CD** solutions for **.NET Core** applications;