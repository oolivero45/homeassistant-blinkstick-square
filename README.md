# homeassistant-blinkstick-square
Home Assistant component for controlling a BlinkStick Square

Original module copied from https://github.com/home-assistant/core/tree/dev/homeassistant/components/blinksticklight, with modifications to allow it to support BlinkStick devices which have more than one LED, such as the BlinkStick Square.

## Configuration

```yaml
# Example configuration.yaml entry for an 8-LED BlinkStick Square
light blinkstick:
  - serial: BS030781-3.0
    platform: blinksticksquare
    index: 0
    name: Blinkstick 0
  - serial: BS030781-3.0
    platform: blinksticksquare
    index: 1
    name: Blinkstick 1
  - serial: BS030781-3.0
    platform: blinksticksquare
    index: 2
    name: Blinkstick 2
  - serial: BS030781-3.0
    platform: blinksticksquare
    index: 3
    name: Blinkstick 3
  - serial: BS030781-3.0
    platform: blinksticksquare
    index: 4
    name: Blinkstick 4
  - serial: BS030781-3.0
    platform: blinksticksquare
    index: 5
    name: Blinkstick 5
  - serial: BS030781-3.0
    platform: blinksticksquare
    index: 6
    name: Blinkstick 6
  - serial: BS030781-3.0
    platform: blinksticksquare
    index: 7
    name: Blinkstick 7
```
