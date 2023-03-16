# DasKeyboard QClient.NET
TODO

Forked from [DasKeyboardQClient](https://github.com/wedge206/DasKeyboardQClient)

____

QClient.NET is a lightweight and easy to use .Net client for the DasKeyboard Q API

## Usage
### Create a Local Client
Note: Limited endpoints available on local client
```c#
var client = new LocalQClient();
```

You can also optionally specify a custom hostname and/or custom port number:
```c#
var client = new LocalQClient("myhostname", 27302);
```

### Create an Authenticated Cloud Client
All authentication and token handling is automatic
```c#
var client = new CloudQClient("CLIENTID", "SECRET");
```

### Create an UnAuthenticated Cloud Client
Note: Limited endpoints available when not authenticated
```c#
var client = new CloudQClient();
```
