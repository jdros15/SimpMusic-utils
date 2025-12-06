# SimpMusic Utils

A Chrome extension that extracts cookies from YouTube Music and specifically the `sp_dc` parameter from Spotify for SimpMusic client

## Features

- Extract all cookies from YouTube Music
- Extract only the `sp_dc` cookie from Spotify
- Copy extracted cookies to clipboard with a single click

## Installation

### Method 1: Download Pre-built Release
1. Go to the [Releases](https://github.com/jdros15/SimpMusic-utils/releases) page.
2. Download the `simpmusic-utils-extension.zip` file.
3. Extract the zip file to a folder.
4. Open Chrome and navigate to `chrome://extensions/`.
5. Enable **Developer mode** in the top right corner.
6. Click **Load unpacked**.
7. Select the folder you just extracted.

### Method 2: Build from Source
If you want to build the extension yourself:
1. Clone the repository:
   ```bash
   git clone https://github.com/maxrave-dev/utils.git
   cd utils
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Build the project:
   ```bash
   npm run build
   ```
4. Load the extension in Chrome:
   - Go to `chrome://extensions/`
   - Click **Load unpacked**
   - Select the `dist` folder directly (do NOT select the root project folder).

## Usage

1. Click on the extension icon in your Chrome toolbar
2. Click "Extract Cookies" for YouTube Music or Spotify
3. Once cookies are displayed, use the "Copy to Clipboard" button to copy them
4. You can now use these cookies in your applications

## License

```md
MIT License

Copyright (c) 2025 Nguyễn Đức Tuấn Minh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Support & Donations 
#### Special thanks to all supporter ❤️    
<div align="left"> 
<a href="https://simpmusic.org/"><img alt="Visit the website" height="50" src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/documentation/website_vector.svg"></a> &nbsp;        
<a href="https://discord.gg/Rq5tWVM9Hg"><img alt="Discord Server" height="50" src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/social/discord-plural_vector.svg"></a> &nbsp;        
<br> <a href="https://www.buymeacoffee.com/maxrave"><img alt="Buy me a Coffee" height="50" src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/donate/buymeacoffee-singular_vector.svg"></a> &nbsp;        
<a href="https://liberapay.com/maxrave/"><img alt="liberapay" height="50"        
src="https://raw.githubusercontent.com/liberapay/liberapay.com/master/www/assets/liberapay/logo-v2_black-on-yellow.svg"></a> 
</div>

### MOMO or Vietnamese banking    
<p float="left">        
<img src="https://github.com/maxrave-dev/SimpMusic/blob/dev/asset/52770992.jpg?raw=true" width="300"> 
</p>

## SimpMusic is sponsored by:
<a href="https://www.digitalocean.com/?refcode=d7f6eedfb9a9&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge"><img src="https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg" width="300" alt="DigitalOcean Referral Badge" /></a>
<br>
<a href="https://crowdin.com">
<img src="https://support.crowdin.com/assets/logos/plate/png/crowdin-logo-with-plate.png" width="300"/>
</a>
<br>
<a href="https://sentry.io">
<img src="https://github.com/maxrave-dev/SimpMusic/blob/dev/asset/sentry.svg?raw=true" width="300"/>
</a>
<br>

Get free $200 credit over 60 days on DigitalOcean: [GET NOW](https://www.digitalocean.com/?refcode=d7f6eedfb9a9&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)

Crowdin and Sentry both have a free enterprise plan for Open-source projects. Follow the URLs:
- [Open Source License Request Form | Crowdin](https://crowdin.com/page/open-source-project-setup-request)
- [Sentry for Open Source | Sentry](https://sentry.io/for/open-source/)

*This project is a part of SimpMusic.org Open-source project by me [maxrave-dev](https://github.com/maxrave-dev)*
