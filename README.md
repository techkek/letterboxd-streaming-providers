# Letterboxd Streaming Providers ![Logo](./extension/icons/logo_final_48.png) 

## What?
This is a extension for common web browsers coded using the WebExtensions API.

## Main Features
This extension adds a filter for some streaming providers (e.g. Netflix, Amazon Prime) to [Letterboxd](https://letterboxd.com/), so that you can see, which movies are included in your streaming flat rate.

### How?
The extension uses the TMDb API for assigning the original movie titles to the english ones. Furthermore the JustWatch API is used for providing the streaming information.

### Which browser to use?
The extension can be added into Chrome, Firefox and Opera.

### Which countries are supported?
Actually streaming providers of following countries are supported: Austria, Canada, France, Germany, Japan, Mexico, Spain, Switzerland, USA, United Kingdom 

Coming soon: Australia, India, Ireland, Italy, Russia, Netherlands, Norway, Sweden

### Important Notice
This is a third party extension and is not related to the Letterboxd developer team in any way.

## Contributing

### Developing
- `npm install` - Installs all dependencies
- `npm run dev` - Builds the Firefox (.xpi) and the Chrome/Opera (.zip) builds

### How to test?
1. Run `npm install` once at the beginning of your development.
2. Load the extension in your browser.

In Chrome: 
- go to `chrome://extensions`
- activate developer mode 
- then
    - click `load unpacked extension` 
    - load the `/extension` folder 
- or
    - drag & drop the Chrome build file from `/builds` into the tab.
    
In Firefox:
- go to `about:debugging`
- then
    - load `extension/manifest.json`
- or
    - load the Firefox build file from `/builds`.



### Donations
If you like my work, you can support me via [PayPal](https://www.paypal.me/ChristianZei/5). Thank you!

## Acknowledgements
Thanks to everyone using, supporting and contributing to the extension. Phillip Emmer is especially mentioned for the idea behind this extension.

## What's new?

##### v1.0
- Filter /watchlist, /films and /likes of Letterboxd for your favorite streaming providers
- Choose between streaming providers from Austria, Canada, Germany, Mexico, USA and United Kingdom 