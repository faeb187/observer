# Observer

JS Observer Pattern

```coffee
# @REQUIRE module:
obs = require './path/to/obs'

# 'l'isten: registrate a callback
# for a custom event name
obs.l 'event-name', fn

# 'f'ire: from another module or universe
obs.f 'event-name', optionalParam

# 'r'emove: deletes registrated callbacks by event name
obs.r 'event-name'
```
