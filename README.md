# LocationSaver App

> - only android devices 
> - android 8 and above supported (may updated later (now: 2024/9/26))
> - default saver interval : 1 minute (can be edited)
> - 

auto save locations (from internet or your device clock (warning: have to be sync once a day for offset prevention)) with your own interval and your specific network conditions 
(such as your private network or public network or 4G even 5G with conditions from your handmade)

# pourquoi cette app - why this app ?

- very usefull for police when crimes are

# utilisation des données - Data usage

all data save on your device are accessible to you only and we are not collecting data from you, also your data are saved on your device as a json file
with a specific structure [see section here](#structure-des-fichiers---files-structure)

# structure des fichiers - files structure

<!-- json file of course but bad formatting we also use js formatting -->
```js
{
  systemUserName: "deviceNameHere",
  profile: "ObjectUserUnixSysProfile",
  startDate: "dateStampHere",
  endDate: "dateStampHere",
  data: [
    {
      date: "dateStampHere",
      id: UDouble,
      etc...      
    }
  ]
}
```

# maquette - model

no model yet

<!-- end page -->