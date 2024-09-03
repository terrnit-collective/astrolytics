# Astrolytics 📈

_A collection of Astro components for popular web analytics tools_

Supported services:

<table>
    <tr>
        <td>Service</td>
        <td>Logo</td>
        <td>Website</td>
        <td>Live Demo</td>
        <td>GitHub</td>
        <td>Script.js</td>
        <td>Additional Info</td>
        <td>Status</td>
    </tr>
    <tr>
        <td>Fantom</td>
        <td><img src="docs/fathom.webp"  alt="docs/fathom.webp" width="50" width="50"/> </td>
        <td>https://usefathom.com</td>
        <td>https://app.usefathom.com/demo</td>
        <td></td>
        <td>5,95 KB</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Google Analytics</td>
        <td><img src="docs/ga.webp"  alt="docs/ga.webp" width="50" width="50"/> </td>
        <td>https://developers.google.com/analytics</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Metrical</td>
        <td><img src="docs/metrical.webp"  alt="docs/metrical.webp" width="50" width="50"/> </td>
        <td>https://metrical.xyz</td>
        <td>https://app.metrical.xyz/demo</td>
        <td></td>
        <td>2,48 KB</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Plausible</td>
        <td><img src="docs/plausible.webp"  alt="docs/plausible.webp" width="50" width="50"/> </td>
        <td>https://plausible.io</td>
        <td>https://plausible.io/plausible.io</td>
        <td>https://github.com/plausible/analytics</td>
        <td>1,30 KB</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Simple Analytics</td>
        <td><img src="docs/simpleanalytics.webp"  alt="docs/simpleanalytics.webp" width="50" width="50"/> </td>
        <td>https://simpleanalytics.com</td>
        <td>https://simpleanalytics.com/simpleanalytics.com</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Umami</td>
        <td><img src="docs/umami.webp"  alt="docs/umami.webp" width="50" width="50"/> </td>
        <td>https://umami.is</td>
        <td>https://app.umami.is/share/8rmHaheU/umami.is</td>
        <td>https://github.com/umami-software/umami</td>
        <td>2,75 KB</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Amplitude</td>
        <td><img src="docs/amplitude.webp"  alt="docs/amplitude.webp" width="50" width="50"/> </td>
        <td>https://amplitude.com</td>
        <td>https://analytics.amplitude.com/login/my-demo</td>
        <td>https://github.com/amplitude</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Matomo</td>
        <td><img src="docs/matomo.webp"  alt="docs/matomo.webp" width="50" width="50"/> </td>
        <td>https://matomo.org</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Minimalanalytics</td>
        <td>🌱</td>
        <td>https://minimalanalytics.com</td>
        <td></td>
        <td>https://gist.github.com/DavidKuennen/443121e692175d6fc145e1efb0284ec9</td>
        <td>1.56 KB</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Vercel Analytics</td>
        <td><img src="docs/vercel.webp"  alt="docs/vercel.webp" width="50" width="50"/> </td>
        <td>https://vercel.com/docs/analytics/quickstart</td>
        <td></td>
        <td>https://github.com/vercel/analytics</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>


## Installation

```bash
npm install astrolytics
# or
pnpm install astrolytics
# or
yarn add astrolytics
```

## Usage

```js
import { Fathom } from '@astrolytics/analytics;
```

```html
<Fathom site="ABCDEF" src="https://youdomain.com/script.js" /> (if no src is set it will fallback to https://cdn.usefathom.com/script.js)
<GoogleAnalytics id="UA-156492295-1" />
<Metrical app="j5gZ1K26a" />
<Plausible domain="yourdomain.com" src="https://youdomain.com/yoursript.js" /> (if no src is set it will fallback to https://plausible.io/js/script.js)
<SimpleAnalytics />
<Umami id="4fb7fa4c-5b46-438d-94b3-3a8fb9bc2e8b" src="https://your-umami-app.com/umami.js" />
<Amplitude apiKey="<YOUR API KEY>" />
<Matomo id="1" src="https://yourdomain.com" />
<MinimalAnalytics id="UA-156492295-1" />
```


### Inspiration
- https://github.com/Destiner/astro-analytics
- https://github.com/gurkz-oss/astroutils
- https://github.com/MauricioRobayo/nextjs-google-analytics