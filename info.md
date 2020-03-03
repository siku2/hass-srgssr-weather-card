# SRG SSR Weather Card

## Configuration

After you've added the plugin to your Lovelace resources configuration you can add a card with the custom type `custom:srgssr-weather-card`.

```yaml
- type: custom:srgssr-weather-card
  entity: weather.yourweatherentity
  name: Optional name
```

Note that the entity needs to point to a [SRG SSR Weather](https://github.com/siku2/hass-weather-srgssr) entity.
The icons won't work with any other entity.
