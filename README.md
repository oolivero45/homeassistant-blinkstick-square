# homeassistant-blinkstick-square
Home Assistant component for controlling a BlinkStick Square

Original module copied from https://github.com/home-assistant/core/tree/dev/homeassistant/components/blinksticklight, with modifications to allow it to support BlinkStick devices which have more than one LED, such as the BlinkStick Square.

## Configuration

```yaml
# Example configuration.yaml entry for an 8-LED BlinkStick Square
light:
  - serial: BS000795-1.1
    platform: blinksticksquare
    index: 0
  - serial: BS000795-1.1
    platform: blinksticksquare
    index: 1
  - serial: BS000795-1.1
    platform: blinksticksquare
    index: 2
  - serial: BS000795-1.1
    platform: blinksticksquare
    index: 3
  - serial: BS000795-1.1
    platform: blinksticksquare
    index: 4
  - serial: BS000795-1.1
    platform: blinksticksquare
    index: 5
  - serial: BS000795-1.1
    platform: blinksticksquare
    index: 6
  - serial: BS000795-1.1
    platform: blinksticksquare
    index: 7
```
