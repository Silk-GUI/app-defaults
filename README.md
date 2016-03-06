# App Defualts

App to handle default app for opening file.

This is generally used by window managers, but an app's client could also access the methods. 

## Methods

__Silk/appDefaults__

params: mime

returns: 
```
{
  default: name of default app
  available: [array of apps that can open the mime]
}
```

__Silk/setDefault__

param: data 
```
{
  mime: mime,
  app: name of app
}
```

## Override

If you want a different implementation, you can remove this app and create your own that provides these two methods.
