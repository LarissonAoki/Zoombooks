### Instalar NodeJS, e depois Ionic e Cordova

npm install -g ionic cordova

### Para rodar o código:

npm install

ionic serve

#### Outros comandos úteis:

ionic start NomeDoApp blank (ou tabs ou sidemenu)

ionic generate page NomeDaPagina



ionic cordova platform add browser --save

ionic cordova plugin add phonegap-plugin-barcodescanner

npm install @ionic-native/barcode-scanner

ionic cordova plugin add cordova-plugin-camera

npm install --save @ionic-native/camera

ionic cordova run browser (para testar câmera)


#### Gerar apk para Android:

ionic cordova build android