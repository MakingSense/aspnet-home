# AspNet-Home

The AspNet-Home repository is the starting point for people to learn about MakingSense ASP.NET 5 libraries. 

## Pre-release NuGet feed

<https://ci.appveyor.com/nuget/makingsense-aspnet> (authentincated)

Authentication: 
* user: `dtru+read@makingsense.com`
* password: `4@pdw@BlfpQn`

`NuGet.config` file example:

```xml
<?xml version="1.0" encoding="utf-8"?>
<configuration>
	<packageSources>
		<clear />
		<add key="api.nuget.org" value="https://api.nuget.org/v3/index.json" />
		<add key="aspnetrelease" value="https://www.myget.org/F/aspnetrelease/api/v2" />
		<add key="makingsense-aspnet" value="https://ci.appveyor.com/nuget/makingsense-aspnet" />
	</packageSources>
	<packageSourceCredentials>
		<makingsense-aspnet>
			<add key="Username" value="dtru+read@makingsense.com" />
			<add key="ClearTextPassword" value="4@pdw@BlfpQn" />
		</makingsense-aspnet>
	</packageSourceCredentials>
</configuration>
```

## Our ASP.NET 5 Open Source projects

* **aspnet-hypermedia-api-seed** - Hypermedia API Seed
    * [Sources](https://github.com/MakingSense/aspnet-hypermedia-api-seed)
* **aspnet-hypermedia-api** - Hypermedia API Helpers
    * [Sources](https://github.com/MakingSense/aspnet-hypermedia-api)
    * [CI](https://ci.appveyor.com/project/makingsense-aspnet/aspnet-hypermedia-api)
    * [Pre-release NuGet feed](https://ci.appveyor.com/nuget/aspnet-hypermedia-api)
* **aspnet-documentation-middleware** - Documentation Middleware
    * [Sources](https://github.com/MakingSense/aspnet-documentation-middleware)
    * [CI](https://ci.appveyor.com/project/makingsense-aspnet/aspnet-documentation-middleware)
    * [Pre-release NuGet feed](https://ci.appveyor.com/nuget/aspnet-documentation-middleware) 
* **aspnet-authentication-simpletoken** - Simple Authentication Middleware
    * [Sources](https://github.com/MakingSense/aspnet-authentication-simpletoken)
    * [CI](https://ci.appveyor.com/project/makingsense-aspnet/aspnet-authentication-simpletoken)
    * [Pre-release NuGet feed](https://ci.appveyor.com/nuget/aspnet-authentication-simpletoken)

