# Demo Barcode Scanner Ionic 7

## Instalar barcode
##### npm i phonegap-plugin-barcodescanner

### Luego
##### npm install @awesome-cordova-plugins/barcode-scanner

### Importar en app.module.ts
#### import {BarcodeScanner} from '@awesome-cordova-plugins/barcode-scanner/ngx'
#### ....
#### providers: [{ provide: RouteReuseStrategy, useClass: IonicRouteStrategy }, BarcodeScanner],

### En la página Home import
#### import {BarcodeScanner} from '@awesome-cordova-plugins/barcode-scanner/ngx'


### CONFIGURAR RUTA ANDROID STUDIO EN CETECOM DUOC
#### C:\Users\CETECOM\AppData\Local\Android\Sdk 

### Para evitar el error de carga en android studio
### cambiar en package.json
#### "Phonegap-plugin-barcodescanner":"git+https://github.com/StarleyDev/barcodescanner-sdk31.git";

### En ANDROID STUDIO
Una vez generada la app, cambiar gradle.properties desde gradle scripy y agregar:
android.enableJetifier=true
