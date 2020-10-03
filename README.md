# Instalation

``npm install tracker.gg``

---

# Example

```js
import { TrackerClient } from 'tracker.gg'
const client = new TrackerClient({ apiKey: process.env.APIKEY })

let data = await client.getOverwatchStats("psn", "SomeRandomUsername")
console.log(data)
```
---
# Methods

| Method | Description |
| ----------- | ----------- |
| getCSGOPlayerStats(identifier) | Returns the CSGO stats for the specified user |
| getSplitPlayerStats(identifier) | Returns the Splitgate stats for the specified user |
| getOverwatchPlayerStats(platform, identifier) | Returns the Overwatch stats for the specified user, optional platforms: psn, xbl |
| getApexPlayerStats(platform, identifier) | Returns Apex stats for the specified user |
