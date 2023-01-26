# Restreamer-UI

The user interface of the Restreamer for the connection to the [Antonio Bento](https://github.com/bentoti/iptv-fullstack.git)application.

- React
- Material-UI (MUI)

## Development

### For the Restreamer interface:

```
$ git clone https://github.com/bentoti/iptv-fullstack/tree/main/client
$ cd rclient
$ yarn install
$ npm run start
```

Connect the UI with a [Antonio Bento](https://github.com/bentoti/iptv-fullstack.git):
http://localhost:3000?address=http://core-ip:core-port

### To add/fix translations:
Locales are located in `src/locals`
```
$ npm run i18n-extract:clean
$ npm run i18n-compile
```

## License
See the [LICENSE](./LICENSE) file for licensing information.
