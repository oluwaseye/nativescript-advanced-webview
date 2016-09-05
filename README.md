[![npm](https://img.shields.io/npm/v/nativescript-advanced-webview.svg)](https://www.npmjs.com/package/nativescript-advanced-webview)
[![npm](https://img.shields.io/npm/dt/nativescript-advanced-webview.svg?label=npm%20downloads)](https://www.npmjs.com/package/nativescript-advanced-webview)

# NativeScript-Advanced-Webview
An advanced webview using [Chrome Custom Tabs](https://developer.chrome.com/multidevice/android/customtabs#whatarethey) on Android (iOS support coming soon).

[Here is a video](https://youtu.be/LVseK_CZp5g) showing off Chrome CustomTabs in NativeScript.

### Perf Matters
[Android Comparison](https://developer.chrome.com/multidevice/images/customtab/performance.gif)

#### Android
[CustomTabs](https://developer.android.com/reference/android/support/customtabs/package-summary.html)

#### iOS
** coming soon **

## Installation
To install execute

```
tns plugin add nativescript-advanced-webview
```

## Usages

```typescript
import { openAdvancedUrl, AdvancedWebViewOptions } from 'nativescript-advanced-webview';
    //// or
import * as AdvancedWebView from 'nativescript-advanced-webview'

public whateverYouLike() {
    
    let opts: AdvancedWebViewOptions = {
        url: 'https://www.youtube.com/watch?v=dQw4w9WgXcQ'
        toolbarColor: '#ff4081',
        showTitle: false
    };
    
    openAdvancedUrl(opts);
}

```

## Example

