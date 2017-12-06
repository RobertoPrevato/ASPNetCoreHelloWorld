# NET Core 2.0 ASP.NET Core test application
Test application using ASP.NET Core web framework and NET Core 2.0.

This application has been used to compare its performance, when deployed:
* using Windows hosting in Azure Application Service Plan.
* using Linux hosting with Docker, in Azure Application Service Plan.

# Visual Studio Web Performance Tests
Using the included Visual Studio solution with Web Performance tests requires a Ultimate version of the IDE. To run these tests, it is necessary to provision owned web applications and change urls configured in tests.

## Note
The tests were originally written to compare the performance of a Dockerized ASP.NET Core application hosted in Linux, with the same application hosted in Windows, like described above. Additional tests were added later, to test different technology stacks.
