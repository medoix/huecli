# Hue CLI

Command line tool to control the Phillips Hue lights via the Phillips Hue Bridge.

## Instructions
### Build
```
git clone https://github.com/medoix/huecli.git
cd huecli
go build
```

### Run
List connected lights
```
HUE_URL=<bridge URL with API key> huecli lights
```

Turn room lights on or off
```
HUE_URL=<bridge URL with API key> huecli office on
```

## Planned Features
- Better Bridge URL Handling
- Control Colors of Lights
