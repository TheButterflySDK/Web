# The Butterfly Button plugin for web

[![License: MIT](https://img.shields.io/badge/License-Apache-yellow.svg)](https://github.com/TheButterflySDK/Web/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web-white.svg)](https://github.com/TheButterflySDK/Web)

[The Butterfly SDK](https://github.com/TheButterflyButton/About/blob/main/README.md) helps your website to take an active part in the fight against domestic violence.

## Installation

### 🔌 & ▶️

### WiX websites?

Go To: https://www.wix.com/app-market/the-butterfly-button

[![image](https://user-images.githubusercontent.com/100164625/217179086-03d4cf3c-d0d1-4403-9943-cf88816ff525.png)](https://www.wix.com/app-market/the-butterfly-button)


### Other websites?

#### Embed tags in your HTML code

```javascript
<script src="https://butterfly-button.web.app/cdn/butterfly-plugin.js"></script>
<img onclick="bf_ReporterPlugin.toggleButterflyReporter('your API key');" src="https://butterfly-button.web.app/img/butterfly-logo-200.png" style="width: 50px; cursor: pointer;" alt="The Butterfly Button" />
```

#### Using WordPress?

![image](https://user-images.githubusercontent.com/100164625/205072953-f883a1e4-83f4-49ef-801a-892dc6113787.png)

Simply put this in the HTML code inside WordPress:
```javascript
<script src="https://butterfly-button.web.app/cdn/butterfly-plugin.js"></script>
<img onclick="bf_ReporterPlugin.toggleButterflyReporter('your API key');" src="https://butterfly-button.web.app/img/butterfly-logo-200.png" style="width: 50px; cursor: pointer;" alt="The Butterfly Button" />
```

#### Using the same country / language in your website?

Use `[override country code]` / `[override language]` in order to override our automatic detection of language and country.

```javascript
<script src="https://butterfly-button.web.app/cdn/butterfly-plugin.js"></script>
<img onclick="bf_ReporterPlugin.toggleButterflyReporter('your API key', [override country code], [override language]);" src="https://butterfly-button.web.app/img/butterfly-logo-200.png" style="width: 50px; cursor: pointer;" alt="The Butterfly Button" />
```

#### Manual usage in JavaScript

```javascript
  // Import
  <script src="https://butterfly-button.web.app/cdn/butterfly-plugin.js"></script>

  // Call
  <script>
      function toggleButterfly() {
          bf_ReporterPlugin.toggleButterflyReporter("your-api-key");
      }
  </script>
```

## Use an API key 🔑

To join us, visit [our website](https://butterfly-button.web.app).

To recognize your app in our servers you'll need an application key. You can set it via code, as demonstrated above.

## Demo in our website
[ynet.co.il](https://www.ynet.co.il/) already operate with our button, simply click our logo.


### Enjoy and good luck ❤️
