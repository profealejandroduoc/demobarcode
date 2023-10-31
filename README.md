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
