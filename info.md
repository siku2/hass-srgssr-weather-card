# SRG SSR Weather Card

## Installation

You need to add the following to your Lovelace `resources` config.

```yaml
- type: module
  url: /community_plugin/weather-card/hass-srgssr-weather-card.js
```


## Configuration

Add a card with the custom type `custom:srgssr-weather-card`.

```yaml
- type: custom:srgssr-weather-card
  entity: weather.yourweatherentity
  name: Optional name
```

Note that the entity needs to point to a [SRG SSR Weather](https://github.com/siku2/hass-weather-srgssr) entity.
The icons won't work with any other entity.
