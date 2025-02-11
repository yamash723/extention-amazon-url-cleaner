# Amazon URL Cleaner

Amazon URL Cleaner is a browser extension that removes unnecessary strings from Amazon product page URLs.

## Features

It removes unnecessary query parameters and paths from Amazon product page URLs.

## Installation Steps

1. Clone or download this repository.
2. Open the Chrome browser and go to `chrome://extensions/`.
3. Turn on "Developer mode" in the upper right corner.
4. Click on "Load unpacked" and select the downloaded folder.

## Usage

1. Access an Amazon product page.
2. The URL will be automatically redirected to a clean format.

### Before

```text
https://www.amazon.co.jp/%E3%82%A2%E3%83%94%E3%82%AB-%E3%83%AC%E3%82%A4%E3%83%B3%E3%82%AC%E3%83%BC%E3%83%89%E3%83%A1%E3%83%A2-SW59BN-A7-%E9%9D%92/dp/B003T9C93A/
```

### After

```text
https://www.amazon.co.jp/dp/B003T9C93A/
```
