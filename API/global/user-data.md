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
    "biz_vespucci_masks": 14, // level
  },
  "user_id": 41306
}
```