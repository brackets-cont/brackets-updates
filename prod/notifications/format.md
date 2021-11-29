## How to update
update en.json for english notifications.
```json
{
  "notifications": [
    {
      "sequence": 1630434600000, // A unix timestamp which is the start time in which the notification is effective
      "silent": false,
      "filters": {
        "platforms": [],
        "version": "1.14",
        "locales": [],
        "builds": [],
        "lastUsed": ""
      },
      "html": "<div style='display: block;height: auto;font-size: 16px;'><div style='display: inline-block;float: left;padding: 7px 65px 7px 5px;font-weight: 500;'><a class='actionable' href='https://brackets.io' style='text-decoration: none;font-weight: 500;'>Go Brackets!</a></div></div>",
      "actionables": ".actionable",
      "expiry": 1662036585000 // A unix timestamp to end showing the notification
    },
    {
      "sequence": 1614450600000,
      "silent": false,
      "filters": {
        "platforms": [],
        "version": "1.14",
        "locales": [],
        "builds": [],
        "lastUsed": ""
      },
      "html": "<div style='display: block;height: auto;font-size: 16px;'><div style='display: inline-block;float: left;padding: 7px 65px 7px 5px;font-weight: 500;'>Hello users</div>",
      "actionables": ".actionable",
      "expiry": 1630434600000
    }
  ]
}
```
