# IONIC- Weather App
- List daily temperatures in your area using the DarkSky.net API.
- View weather details for a specific day chosen from the daily temperatures list.

## Getting Started

* Clone master repository

* Install Ionic, cordova and node_modules

    ```bash
    $ npm install -g ionic cordova
    $ npm install
    ```
* Get weather API key from DarkSky - https://darksky.net
  * Replace API_KEY in `src/pages/providers/constants.ts`

* Get google API key from Google Developers Console - https://console.developers.google.com/apis/credentials
  * Replace key in `src/index.html`
  ```html
  <script src="https://maps.googleapis.com/maps/api/js?v=3&key=AIzaSyAZL0jdvdtBV_DmzLZ8yW53GHnhlRrbIAY&libraries=places">
  </script>
  ```

### Browser testing
```bash
    $ npm install @ionic/lab
    $ ionic serve --lab (wait for the terminal to finish loading)
```

### Make sure all required variables are added correctly to your path for Android and IOS testing

### Android testing
```bash
    $ ionic cordova platform add android
    $ ionic cordova build android
    $ ionic cordova emulate android
    $ ionic cordova run android (install to device)
```

### iOS testing
```bash
    $ ionic cordova platform add ios
    $ ionic cordova build ios
    $ ionic cordova emulate ios
    $ ionic cordova emulate ios -- --buildFlag="-UseModernBuildSystem=0" (if emulator fails)
    $ ionic cordova run ios (install to device)
```    

### Screenshots
* Phone

  <img src="screenshots/phone1.png" alt="phone1" width="250"/>
