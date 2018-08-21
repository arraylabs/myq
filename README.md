## MyQ component for Home Assistant.

Platform for the MyQ cover component.
For more details about this platform, please refer to the documentation
https://www.home-assistant.io/components/cover.myq/


Initial code provided by user MisterWil on the Home Assistant Forum. His initial code can be found at http://pastebin.com/qVszax1t.

In your configuration.yaml file use an entry similar to:

```
cover:
  - platform: myq
    username: email@email.com
    password: password
    type: chamberlain //liftmaster,chamberlain,craftsman,merlin
```
