# Server data

These endpoints are for getting certain data about a specific server

### `/weather.json` - Get server weather

```json
{
  "time_remaining": 1497, // Time in seconds until next weather change
  "current_weather": "drizzling" // The current weather on the
}
```

### `/airline.json` - Get airline info

```json
{
  "875": [ // source id?
    "Velum", // vehicle model / vehicle name
    {
      "z": 20.51197052002,
      "y": 6583.7412109375,
      "x": 2777.1384277344,
      "airport": "MGA", // airport id
      "name": "Mount Gordo Terminal 3" // airport name
    },
    false, // at terminal
    434297 // vRP id
  ]
}
```

### `/players.json` - Get simple player info

```json
{
  "players": [
    [
      "xxxxxx", // user name
      895, // source id
      434912 // vRP id
    ],
  ]
}
```

### `/map/positions.json` - Get map positions

```json
{
  "players": [
    [
      "Gino", // player name
      820, // source id
      377664, // vRP id
      {
        "z": 16.24852180480957,
        "y": 5180.30029296875,
        "x": -2179.143798828125
      },
      {
        "vehicle_type": "helicopter",
        "vehicle_name": "Maverick",
        "vehicle_label": "MAVERICK",
        "vehicle_class": 15,
        "vehicle_spawn": "maverick",
        "owned_vehicles": {
          "trailer": "drybulktr",
          "cab": "urnext",
          "car": "rc350"
        },
        "vehicle_model": -1660661558, // model hash
        "trailer": "",
        "has_trailer": false
      },
      {
        "group": "firefighter",
        "name": "Firefighter"
      }
    ]
  ],
  "caches": 6648,
  "requests": 6834
}
```

### `/widget/players.json` Get advanced player info

```json
{
  "server": {
    "number": "1",
    "dxp": [
      true, // dxp active
      "Ander 🇳🇴", // dxp host
      27576791, // time remaining
      0 // 
    ],
    "limit": 128, // player limit
    "region": "OS",
    "uptime": "14h 25m",
    "beta": "",
    "motd": "",
    "name": ""
  },
  "players": [
    [
      "jorgius13", // username
      895, // source id
      434912, // vRP id
      "img", // avatar url
      false, // staff
      "", // job
      false // donator
    ]
  ]
}
```

### `/advanced/` Get HTML data of users, alongisde wealth + discord name
