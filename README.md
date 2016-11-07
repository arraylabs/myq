# myq
## MyQ custom component for Home Assistant.

Initial code provided by user MisterWil on the Home Assistant Forum. His initial code can be found at http://pastebin.com/qVszax1t.

Place the myq.py file in the /path/to/homeassistant/custom_components/cover/

In your configuration.yaml file use an entry similar to:

```
cover:
  - platform: myq
    name: Garage Door
    username: email@email.com
    password: password
    brand: chamberlain //liftmaster,chamberlain,craftmaster
```
