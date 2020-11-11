# User data

### `/snowflake2user/[discordId]` - Get vRP id from discord id

```jsonc
{
  "code": "200",
  "user_id": 41306,
  "discord_id": 138725221749358592,
  "type": "linked"
}
```

### `/inventory/[vRPid]` - Get user inventory formatted as HTML

### `/skills/[vRPid]` - Get user skills formatted as HTML

### `/getuserbiz/[vRPid]` - Get user businesses

```jsonc
{
  "code": "200",
  "businesses": {
    "biz_vespucci_masks": 14 // level
  },
  "user_id": 41306
}
```

### `/ownedvehicles/[vRPid]` - Get user owned vehicles

```jsonc
{
  "code": "200",
  "vehicles": {
    "trailers2": ["trailer", 2750], // model: array[class, inventory_size]
    "vestra": ["aircraft", 30],
    "bmx": ["bicycle", 10],
    "neon": ["car", 10],
    "hakuchou": ["bike", 10],
    "hauler2": ["cab", 10]
  },
  "user_id": 41306
}
```

### `/getuserfaq/[vRPid]` - Get user faction

```jsonc
{
  "code": "200",
  "is_in_faction": true,
  "user_id": 41306,
  "faction_id": 56
}
```

### `/data/[vRPid]` - Get user data

```jsonc
{
  "code": "200",
  "data_type": "data_offline",
  "user_id": 41306,
  "data": {
    "inventory": {
      "group_card|mechanic|Mechanic": {
        "amount": 10
      }
    },
    "gaptitudes": {
      "trucking": {
        "garbage": 10,
        "postop": 10,
        "mechanic": 10,
        "trucking": 5668.536999999991
      },
      "train": {
        "train": 447.273,
        "bus": 10
      },
      "physical": {
        "strength": 2325
      },
      "ems": {
        "ems": 10,
        "fire": 10
      },
      "hunting": {
        "skill": 10
      },
      "police": {
        "police": 10
      },
      "casino": {
        "casino": 255.63700000000029
      },
      "business": {
        "business": 3672.934999999995
      },
      "farming": {
        "mining": 171.248,
        "animals": 0,
        "farming": 161.248,
        "fishing": 10
      },
      "player": {
        "player": 3786.923999999957,
        "racing": 19.989
      },
      "piloting": {
        "cargos": 10,
        "heli": 10,
        "piloting": 45.177
      }
    },
    "position": {
      "z": 40.98773193359375,
      "y": 4775.8984375,
      "x": 2145.220947265625
    },
    "gaptitudes_v": {
      "trucking": {
        "garbage": 10,
        "postop": 10,
        "mechanic": 10,
        "trucking": 5668.536999999991
      },
      "train": {
        "train": 447.273,
        "bus": 10
      },
      "ems": {
        "ems": 10,
        "fire": 10
      },
      "hunting": {
        "skill": 10
      },
      "physical": {
        "strength": 5509.179
      },
      "casino": {
        "casino": 255.63700000000029
      },
      "business": {
        "business": 3672.934999999995
      },
      "farming": {
        "fishing": 10,
        "farming": 161.248,
        "mining": 171.248
      },
      "player": {
        "player": 3786.923999999957,
        "racing": 19.989
      },
      "piloting": {
        "cargos": 10,
        "heli": 10,
        "piloting": 45.177
      }
    },
    "health": 200,
    "thirst": 0.03334595522503148,
    "groups": {
      "patreon_tier1": true,
      "trucker_commercial": true,
      "license_beta_p2w": true,
      "user": true,
      "license_driver": true,
      "godmode": true,
      "discord_linked": true,
      "discord_was_linked": true,
      "license_faq_bonus_exp_5": true,
      "trucker": true,
      "corp2.collinsco.tier1": true,
      "license_patreon_beta": true,
      "license_premium": true,
      "license_transfer": true
    },
    "customization": {
      // Character model data
      "9": [29, 0, 0],
      "8": [41, 0, 0],
      "7": [0, 0, 0],
      "6": [90, 0, 0],
      "5": [45, 0, 0],
      "4": [108, 8, 0],
      "3": [0, 0, 0],
      "h1": [255, 0, 0, 0, 1.0],
      "h7": [255, 0, 0, 0, 1.0],
      "h9": [255, 0, 0, 0, 1.0],
      "h3": [255, 0, 0, 0, 1.0],
      "h5": [255, 0, 0, 0, 1.0],
      "2": [0, 0, 0, 0, 0],
      "1": [144, 0, 0],
      "0": [0, 0, 0],
      "19": [0, 0, 0],
      "15": [0, 0, 100],
      "p3": [-1, 0],
      "13": [5376, 0, 0],
      "p5": [-1, 0],
      "12": [0, 0, 0],
      "p2": [-1, 0],
      "10": [0, 0, 0],
      "p0": [-1, 0],
      "modelhash": 1885233650,
      "p1": [27, 0],
      "h10": [255, 0, 0, 0, 1.0],
      "h2": [255, 0, 0, 0, 1.0],
      "11": [286, 0, 0],
      "h0": [255, 0, 0, 0, 1.0],
      "p9": [-1, 0],
      "h8": [255, 0, 0, 0, 1.0],
      "p10": [-1, 0],
      "h12": [255, 0, 0, 0, 1.0],
      "h4": [255, 0, 0, 0, 1.0],
      "17": [0, 0, 0],
      "h6": [255, 0, 0, 0, 1.0],
      "h11": [255, 0, 0, 0, 1.0],
      "18": [0, 0, 0],
      "p8": [-1, 0],
      "p7": [-1, 0],
      "20": [0, 0, 27],
      "p4": [-1, 0],
      "16": [8, 0, 1],
      "p6": [-1, 0],
      "14": [0, 0, 255]
    },
    "AcceptingPlayerEms": true,
    "hunger": 0.01667297761251574,
    "licenses": {
      "muted_2d": 0,
      "exp_day": 0,
      "helicopter": 0,
      "exp_15": 0,
      "premium3": 0,
      "patreon_premium": 0,
      "discord_voice": 0,
      "freefuel_p2w": 0,
      "driver": 1549576712,
      "exp_week": 0,
      "commerce_beta": 0,
      "exp_ee": 0,
      "nofood_p2w": 0,
      "pristine": 0,
      "muted_perm": 0,
      "premium2": 0,
      "patreon_beta": 1603926158,
      "firearm": 0,
      "premium_p2w": 0,
      "transfer": 1605722201,
      "premium": 1607708368,
      "notrap_p2w": 0,
      "transfer_p2w": 0,
      "muted_week": 0,
      "faq_bonus_exp_5": 1605179481,
      "notoll_p2w": 0,
      "plane": 0,
      "nofuel_p2w": 0,
      "commerce_premium": 0,
      "beta_p2w": 1603926204,
      "police": 0,
      "corp_cooldown": 0,
      "commerce_transfer": 0,
      "faq_bonus_exp_15": 0,
      "muted_suggestions": 0,
      "patreon_transfer": 0
    },
    "ironman": false,
    "vehicle": {
      "vehicle_type": "foot",
      "vehicle_name": "None",
      "vehicle_label": "NULL",
      "vehicle_model": -1,
      "trailer": "",
      "owned_vehicles": {
        "cab": "hauler2",
        "trailer": "trailers2"
      },
      "vehicle_class": -1,
      "vehicle_spawn": "",
      "has_trailer": false
    },
    "chat_title": "CORP2"
  }
}
```

### `/dataadv/[vRPid]` - Get user data with more item detail (weight, name, etc...)

difference is only in inventory items:

```jsonc
"sandwich": {
  "amount": 185,
  "weight": 0.0,
  "name": "<span style=\"color:lawngreen\">Sandwich</span>"
},
```
