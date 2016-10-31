# Hangfire.Dashboard.Dark

![Build status](https://ci.appveyor.com/api/projects/status/b57hb7438d7dvxa2/branch/master?svg=true&passingText=master%20%u2714)
[![NuGet](https://img.shields.io/nuget/v/Hangfire.Dashboard.Dark.svg)](https://www.nuget.org/packages/Hangfire.Dashboard.Dark/)

Hangfire.Dashboard.Dark shows the hangfire dashboard in a beautiful dark theme. 

## Features

 - [Darkly](http://bootswatch.com/darkly/)

## Setup

In .NET Core's Startup.cs:
```c#
public void ConfigureServices(IServiceCollection services)
{
    services.AddHangfire(config =>
    {
        ...
        config.UseDarkDashboard();
    });
}
```

Otherwise,
```c#
GlobalConfiguration.Configuration
    ...
    .UseDarkDashboard();
```
