# The Butterfly Button plugin for web

[![License: MIT](https://img.shields.io/badge/License-Apache-yellow.svg)](https://github.com/TheButterflySDK/Web/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web-white.svg)](https://github.com/TheButterflySDK/Web)

[The Butterfly SDK](https://github.com/TheButterflySDK/About/blob/main/README.md) helps your website to take an active part in the fight against domestic violence.

## Installation

### 🔌 & ▶️

#### Embed tags in your HTML code

```javascript
<script src="https://butterfly-button.web.app/cdn/butterfly-plugin.js"></script>
<img onclick="bf_ReporterPlugin.toggleButterflyReporter('your API key');" src="https://butterfly-button.web.app/img/butterfly-logo-200.png" style="width: 50px" alt="The Butterfly Button" />
```

#### Using the same country / language in your website?

Use `[override country code]` / `[override language]` in order to override our automatic detection of language and country.

```javascript
<script src="https://butterfly-button.web.app/cdn/butterfly-plugin.js"></script>
<img onclick="bf_ReporterPlugin.toggleButterflyReporter('your API key', [override country code], [override language]);" src="https://butterfly-button.web.app/img/butterfly-logo-200.png" style="width: 50px" alt="The Butterfly Button" />
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

To recognize your app in our servers you'll need an application key. You can set it via code, as demonstrated above.

## Demo in our website
[Our simple website (pure HTML with JS)](https://butterfly-button.web.app/) already operate with our button, simply click our logo.


### Enjoy and good luck ❤️
