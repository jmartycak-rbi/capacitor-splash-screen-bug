## Capacitor splash screen bug

Code reproduction for https://github.com/ionic-team/capacitor-plugins/issues/1856

### STR
1. Run the android app on a device
2. Background the app when the splash screen is still visible
3. Wait for the `SplashScreen.hide()` call
4. Observe the error

### Running this example

To run the provided example, you can use `npm start` command.

```bash
npm start
```
