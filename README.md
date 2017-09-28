# c9.io app

This is created to use cloud 9 service as a single application.

```bash
$ git clone https://github.com/novemberde/c9-app.git
$ cd c9-app
$ npm install -g electron electron-packager
$ npm install
$ electron-packager . c9-app --platform=win32 --arch=x64
$ cd c9-app-win32-x64
```

Finally, Execute "c9-app.exe".

## License

[The MIT License (MIT)](LICENSE.md)
