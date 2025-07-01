# Savvy Publisher Ad Integration

This repository contains documentation for integrating the Savvy Insurance iframe ad into your website using HTML and iframe-resizer.

## Overview

The Savvy Insurance iframe ad is a dynamic insurance quote widget that can be embedded into any website to kickstart your visitors' shopping journey. The ad is hosted at:

**CDN URL:** `https://cdn.savvy.insure/publisher/v1.0/index.html`

## Prerequisites

This integration assumes you have [iframe-resizer](https://github.com/davidjbradshaw/iframe-resizer) enabled on your page to handle responsive design automatically.

## Quick Start

### Basic Integration

Add the following HTML code to your webpage where you want the ad to appear:

```html
<iframe 
  src="https://cdn.savvy.insure/publisher/v1.0/index.html"
  style="width: 100%"
  frameborder="0">
</iframe>
```

## Tracking via URL Parameteres


You can pass relevant data to the iframe by adding a `txn` URL parameter:

```html
<iframe 
  src="https://cdn.savvy.insure/publisher/v1.0/index.html?txn=12345678"
  style="width: 100%"
  frameborder="0">
</iframe>
```

## License

This integration guide is provided under the MIT License. The Savvy Insurance iframe ad service is subject to Savvy Insurance's terms of service.

## Changelog

### v1.0.0
- Initial release
- HTML iframe integration
- URL parameter support
