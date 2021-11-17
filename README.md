# Hacky Home assistant support for Xiaomi vacuum Viomi SE (V-RVCLM21A)

_Original code by [@nqkdev](https://github.com/nqkdev/home-assistant-vacuum-styj02ym), then it was forked by[@KrzysztofHajdamowicz](https://github.com/KrzysztofHajdamowicz/home-assistant-vacuum-styj02ym), then I forked it and added V-RVCLM21A support based around [@marotoweb](https://github.com/marotoweb/home-assistant-vacuum-viomise) fork._  
## This is for V-RVCLM21A (apparently EU version) with 4.0.9_0017 firmware

### Install

- Install it with HACS
- Add the configuration to configuration.yaml, example:

### Usage

Add to `configuration.yaml`:

```yaml
vacuum:
  - platform: miio2
    host: 192.168.68.105
    token: !secret vacuum
    name: Mi hihi
```
