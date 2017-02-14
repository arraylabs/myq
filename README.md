### Beginning in Home Assistant 0.39 this will be an official component. Users using this custom component will need to remove it and also make a simple change to their config. Changing "brand" to "type". The documentation on the HA site will have a simple example.

# myq
## MyQ custom component for Home Assistant.

Initial code provided by user MisterWil on the Home Assistant Forum. His initial code can be found at http://pastebin.com/qVszax1t.

Place the myq.py file in the /path/to/homeassistant_config/custom_components/cover/

> Note: "/path/to/homeassistant_config" should be the path to where your configuration.yaml file is.

In your configuration.yaml file use an entry similar to:

```
cover:
  - platform: myq
    username: email@email.com
    password: password
    brand: chamberlain //liftmaster,chamberlain,craftsman,merlin
```
