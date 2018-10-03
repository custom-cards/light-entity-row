# Light Entity Row

## Usage

For use in an `entites` card. You can specify an array of extra
buttons to add with an `action_name` and `service_data` to send to
`light.turn_on` for the supplied entity. If not supplied, only the
temperature buttons show up.

```
- type: entities
  title: Lights
  entities:
    - type: "custom:adjustable-light-entity-row"
      entity: light.lamp
      icon: mdi:lamp  # optional
      name: Lamp      # optional
      buttons:        # optional
        action_name: Red
        service_data:
          color_name: red
```

