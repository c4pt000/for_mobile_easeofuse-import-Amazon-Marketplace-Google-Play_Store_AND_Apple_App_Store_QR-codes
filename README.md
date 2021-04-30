google play, amazon store listings, -> QR code generator javascript, -> grab current URL -> pipe through QR code generator.js -> place by .css X,Y location of store object

simple project intermediate or advanced programmer maybe 3 or 4 hours tops

done -> 04-30-2021 might build a template if i am not too busy

# AMAZON marketplace TEMPLATE

![s1](https://raw.githubusercontent.com/c4pt000/Google-Play_Store_AND_Apple_App_Store_QR-codes/main/amazon-marketplace-example.png)

run a local side server to test functionality (grabs current href url and paints the QR code for the current market item listing)

 /usr/bin/web-server-simple 
python -m http.server 8888 --directory .

# see example template files here
https://github.com/c4pt000/Google-Play_Store_AND_Apple_App_Store_QR-codes/blob/main/QR-html-template-amazon.tar.gz

<br>
<br>
<br>
<br>
<br>

# local side only if the code lives on the server side it will generate a QR code based on location of href url for QR current page for the client's browser side
```
wget https://github.com/c4pt000/Google-Play_Store_AND_Apple_App_Store_QR-codes/blob/main/QR-html-template-amazon.tar.gz

cd QR-html-template-amazon

"requires python3"

python -m http.server 8888 --directory .
```
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>



see source of qrcode generator -> https://github.com/c4pt000/QR-Code-generator not my original code its a fork I kept to utilize
requires node js and build.sh to generate node modules based on .js and .ts


# Google-Play_Store_QR-codes and apple ios App store
# QR code should be generated for every google play store app and google play store app should have a camera import button to find and import apps easier
<br>
<br>
<br>
<br>
<br>


# GOOGLE PLAY TEMPLATE
![s1](https://raw.githubusercontent.com/c4pt000/Amazon-Marketplace-Google-Play_Store_AND_Apple_App_Store_QR-codes/main/Google-Play-Store-QR-code-open-template.png)

```
wget https://github.com/c4pt000/Amazon-Marketplace-Google-Play_Store_AND_Apple_App_Store_QR-codes/blob/main/Google-Play-template-example.tar.gz

cd Google-Play-template-example

"requires python3"

python -m http.server 8888 --directory .

```
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


![s1](https://raw.githubusercontent.com/c4pt000/Google-Play_Store_QR-codes/main/QR-app-store-install.png)

# camera button icon with a listen event opens camera app on phone

![s1](https://raw.githubusercontent.com/c4pt000/Google-Play_Store_QR-codes/main/camera-import-link-button-listen-to-camera-app.png)
<br>
<br>
<br>
<br>
<br>
<br>

#  QR code should be generated for every apple app store app and apple App store app should have a camera import button to find and import apps easier

requires recompiling apple app store macOS desktop source for QR code generator for macOS desktop, and apple ios app store ios client

![s1](https://raw.githubusercontent.com/c4pt000/Google-Play_Store_QR-codes/main/binance-example.png)

same here camera icon lower left hand corner with a listen event for a button click opens iphone camera app for QR code import

![s1](https://github.com/c4pt000/Google-Play_Store_QR-codes/blob/main/apple-app-store-QR-camera-import-crudge.png)
