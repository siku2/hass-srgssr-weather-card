# Lovelace animated weather card for SRG SSR

This is a fork of the excellent [Weather Card](https://github.com/bramkragten/weather-card).
It's designed to be used with the (SRG SSR Weather Integration)[https://github.com/siku2/hass-weather-srgssr].

It uses the official icons provided by SRG SSR (Grab your own copy [here](https://developer.srgssr.ch/apis/srgssr-weather)) in order to cover the wide range of states reported by the API.
Of course this basically ruins the design of the card, but that's just how it is.


## Installation with HACS

1. Go to the HACS Settings and add the custom repository `siku2/hass-srgssr-weather-card` with category "Plugin".
2. Open the "Plugins" tab and search for "SRG SSR Weather".
3. Follow the instructions there to set the integration up.
