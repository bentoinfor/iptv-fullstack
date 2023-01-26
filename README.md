# BNTV FULLSTACK

The user interface of the BNTV for the connection to the [BNTV] (https://github.com/bentoti/iptv-fullstack.git)application.

- React
- Material-UI (MUI)

## Development

### For the BNTV interface:

```
$ git https://github.com/bentoti/iptv-fullstack.git
$ cd iptv-fullstack/client
$ yarn install
$ npm run start
```

Connect the UI with a [BNTV](https://github.com/bentoti/iptv-fullstack.git):
http://localhost:3000?address=http://core-ip:core-port

### To add/fix translations:
Locales are located in `src/locals`
```
$ npm run i18n-extract:clean
$ npm run i18n-compile
```

## License
See the [LICENSE](./LICENSE) file for licensing information.
