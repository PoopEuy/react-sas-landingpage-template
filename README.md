Repository: poopeuy/react-sas-landingpage-template
Files analyzed: 105

Estimated tokens: 90.0k

Directory structure:
└── poopeuy-react-sas-landingpage-template/
    ├── README.md
    ├── LICENSE
    ├── package.json
    ├── public/
    │   ├── index.html
    │   ├── manifest.json
    │   ├── robots.txt
    │   └── images/
    │       ├── logged_in/
    │       └── logged_out/
    ├── src/
    │   ├── App.js
    │   ├── App.test.js
    │   ├── GlobalStyles.js
    │   ├── index.js
    │   ├── service-worker.js
    │   ├── serviceWorkerRegistration.js
    │   ├── setupTests.js
    │   ├── theme.js
    │   ├── logged_in/
    │   │   ├── components/
    │   │   │   ├── Main.js
    │   │   │   ├── Routing.js
    │   │   │   ├── dashboard/
    │   │   │   │   ├── AccountInformationArea.js
    │   │   │   │   ├── Dashboard.js
    │   │   │   │   ├── Settings1.js
    │   │   │   │   ├── Settings2.js
    │   │   │   │   ├── SettingsArea.js
    │   │   │   │   ├── StatisticsArea.js
    │   │   │   │   └── UserDataArea.js
    │   │   │   ├── navigation/
    │   │   │   │   ├── Balance.js
    │   │   │   │   ├── MessageListItem.js
    │   │   │   │   ├── MessagePopperButton.js
    │   │   │   │   ├── NavBar.js
    │   │   │   │   └── SideDrawer.js
    │   │   │   ├── posts/
    │   │   │   │   ├── AddPost.js
    │   │   │   │   ├── AddPostOptions.js
    │   │   │   │   ├── PostContent.js
    │   │   │   │   └── Posts.js
    │   │   │   └── subscription/
    │   │   │       ├── AddBalanceDialog.js
    │   │   │       ├── LazyLoadAddBalanceDialog.js
    │   │   │       ├── Subscription.js
    │   │   │       ├── SubscriptionInfo.js
    │   │   │       ├── SubscriptionTable.js
    │   │   │       └── stripe/
    │   │   │           ├── StripeCardForm.js
    │   │   │           ├── StripeIBANForm.js
    │   │   │           └── StripeTextField.js
    │   │   └── dummy_data/
    │   │       └── persons.js
    │   ├── logged_out/
    │   │   ├── components/
    │   │   │   ├── Main.js
    │   │   │   ├── Routing.js
    │   │   │   ├── blog/
    │   │   │   │   ├── Blog.js
    │   │   │   │   ├── BlogCard.js
    │   │   │   │   └── BlogPost.js
    │   │   │   ├── cookies/
    │   │   │   │   ├── CookieConsent.js
    │   │   │   │   ├── CookieRulesDialog.js
    │   │   │   │   └── fetchIpData.js
    │   │   │   ├── footer/
    │   │   │   │   └── Footer.js
    │   │   │   ├── home/
    │   │   │   │   ├── calculateSpacing.js
    │   │   │   │   ├── FeatureCard.js
    │   │   │   │   ├── FeatureSection.js
    │   │   │   │   ├── HeadSection.js
    │   │   │   │   ├── Home.js
    │   │   │   │   ├── PriceCard.js
    │   │   │   │   └── PricingSection.js
    │   │   │   ├── navigation/
    │   │   │   │   └── NavBar.js
    │   │   │   └── register_login/
    │   │   │       ├── ChangePasswordDialog.js
    │   │   │       ├── DialogSelector.js
    │   │   │       ├── LoginDialog.js
    │   │   │       ├── RegisterDialog.js
    │   │   │       └── TermsOfServiceDialog.js
    │   │   └── dummy_data/
    │   │       └── blogPosts.js
    │   └── shared/
    │       ├── components/
    │       │   ├── ActionPaper.js
    │       │   ├── Bordered.js
    │       │   ├── ButtonCircularProgress.js
    │       │   ├── CardChart.js
    │       │   ├── ColoredButton.js
    │       │   ├── ColorfulChip.js
    │       │   ├── ConfirmationDialog.js
    │       │   ├── ConsecutiveSnackbarMessages.js
    │       │   ├── DateTimePicker.js
    │       │   ├── DialogTitleWithCloseIcon.js
    │       │   ├── Dropzone.js
    │       │   ├── EmojiTextArea.js
    │       │   ├── EnhancedTableHead.js
    │       │   ├── FormDialog.js
    │       │   ├── HelpIcon.js
    │       │   ├── HighlightedInformation.js
    │       │   ├── ImageCropper.js
    │       │   ├── ImageCropperDialog.js
    │       │   ├── ModalBackdrop.js
    │       │   ├── NavigationDrawer.js
    │       │   ├── Pace.js
    │       │   ├── PropsRoute.js
    │       │   ├── SelfAligningImage.js
    │       │   ├── ShareButton.js
    │       │   ├── ShareButtons.js
    │       │   ├── VertOptions.js
    │       │   ├── VisibilityPasswordTextField.js
    │       │   ├── WaveBorder.js
    │       │   └── ZoomImage.js
    │       └── functions/
    │           ├── countWithEmojis.js
    │           ├── currencyPrettyPrint.js
    │           ├── getSorting.js
    │           ├── shadeColor.js
    │           ├── smoothScrollTop.js
    │           ├── stableSort.js
    │           ├── toArray.js
    │           ├── unixToDateString.js
    │           ├── useLocationBlocker.js
    │           └── useWidth.js
    └── .github/
        ├── dependabot.yml
        ├── gifs/
        └── workflows/
            └── nodejs.yml


================================================
FILE: README.md
================================================
# React SaaS Template
Remains of a SaaS business I once tried to build. Now transformed into a template for building an SaaS/admin application using React + Material-UI.

[**Check out the demo**](https://reactsaastemplate.com)

![Node.js CI](https://github.com/dunky11/react-saas-template/workflows/Node.js%20CI/badge.svg)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

[<img src="/.github/gifs/showcase.gif">](https://reactsaastemplate.com "Go to demo website")


## Getting Started

### Prerequisites

#### Node.js 12+ (versions below could work, but are not tested)

* Linux:

   ```
   sudo apt install nodejs npm
   ```

* Windows or macOS:

   https://nodejs.org/en/

### Installing

1. Clone the repository

   ```
   git clone https://github.com/dunky11/react-saas-template
   ```
2. Install dependencies, this can take a minute

   ```
   cd react-saas-template
   npm install
   ```
3. Start the local server

   ```
   npm start
   ```

Your browser should now open and show the app. Otherwise open http://localhost:3000/ in your browser. Editing files will automatically refresh the page.

### What to do next?

If you are new to React, you should watch a [basic React tutorial](https://www.youtube.com/results?search_query=react+tutorial) first.

If you know React, then most of the information you need is in the [Material-UI documentation](https://material-ui.com/getting-started/usage/).

You can go into [src/theme.js](/src/theme.js) and change the primary and secondary color codes at the top of the script to the values you like and some magic will happen.

## Deployment

If you are satisfied with the state of your website you can run:

```
npm run build 
```

It will create a folder named build with your compiled project inside. After that copy its content into your webroot and you are ready to go.

## Built With

* [Create-React-App](https://github.com/facebook/create-react-app) - Used to bootstrap the development
* [Material-UI](https://github.com/mui-org/material-ui) - Material Design components
* [React-Router](https://github.com/ReactTraining/react-router) - Routing of the app
* [Pace](https://github.com/HubSpot/pace) - Loading bar at the top
* [Emoji-Mart](https://github.com/missive/emoji-mart) - Picker for the emojis
* [React-Dropzone](https://github.com/react-dropzone/react-dropzone) - File drop component for uploads
* [Recharts](https://github.com/recharts/recharts) - Charting library I used for the statistics
* [Aos](https://github.com/michalsnik/aos) - Animations based on viewport
* [React-Cropper](https://github.com/roadmanfong/react-cropper) - Cropper for the image uploads
* [React-Stripe-js](https://github.com/stripe/react-stripe-js) - Stripes payment elements

## Contribute
Show your support by ⭐ the project. Pull requests are always welcome.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/dunky11/react-saas-template/blob/master/LICENSE) file for details.



================================================
FILE: LICENSE
================================================
MIT License

Copyright (c) 2020 Tim von Känel

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



================================================
FILE: package.json
================================================
{
  "name": "react-saas-template",
  "version": "1.0.0",
  "private": true,
  "homepage": "",
  "description": "Template for building an SaaS/admin application using React + Material-UI",
  "dependencies": {
    "@date-io/date-fns": "^1.3.13",
    "@emotion/react": "^11.8.1",
    "@emotion/styled": "^11.8.1",
    "@mui/icons-material": "^5.4.4",
    "@mui/lab": "^5.0.0-alpha.71",
    "@mui/material": "^5.4.4",
    "@mui/styles": "^5.4.4",
    "@stripe/react-stripe-js": "^1.4.1",
    "@stripe/stripe-js": "^1.16.0",
    "aos": "^2.3.4",
    "classnames": "^2.3.1",
    "emoji-mart": "^3.0.1",
    "js-cookie": "^3.0.1",
    "prop-types": "^15.7.2",
    "react": "^17.0.2",
    "react-cropper": "^2.1.8",
    "react-dom": "^17.0.2",
    "react-dropzone": "^11.3.4",
    "react-router": "^5.2.0",
    "react-router-dom": "^5.2.0",
    "react-scripts": "^2.1.3",
    "recharts": "^2.1.2",
    "workbox-background-sync": "^6.2.4",
    "workbox-broadcast-update": "^6.2.2",
    "workbox-cacheable-response": "^6.2.4",
    "workbox-core": "^6.1.5",
    "workbox-expiration": "^6.1.5",
    "workbox-google-analytics": "^6.2.4",
    "workbox-navigation-preload": "^6.2.2",
    "workbox-precaching": "^6.2.4",
    "workbox-range-requests": "^6.1.5",
    "workbox-routing": "^6.2.4",
    "workbox-strategies": "^6.1.5",
    "workbox-streams": "^6.1.5"
  },
  "devDependencies": {
    "@testing-library/jest-dom": "^5.14.1",
    "@testing-library/react": "^12.0.0",
    "@testing-library/user-event": "^13.2.1"
  },
  "scripts": {
    "start": "react-scripts --openssl-legacy-provider start",
    "build": "react-scripts --openssl-legacy-provider build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
  "eslintConfig": {
    "extends": "react-app"
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/dunky11/react-saas-template.git"
  },
  "author": "dunky11",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/dunky11/react-saas-template/issues"
  }
}



================================================
FILE: public/index.html
================================================
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />
    <meta name="theme-color" content="#000000" />
    <meta
      name="description"
      content="Free Template for building a SaaS application or admin dashboard using React + Material-UI"
    />
    <!--
      manifest.json provides metadata used when your web app is added to the
      homescreen on Android. See https://developers.google.com/web/fundamentals/engage-and-retain/web-app-manifest/
    -->
    <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />
    <link rel="shortcut icon" href="%PUBLIC_URL%/favicon.ico" />
    <link
      rel="apple-touch-icon"
      sizes="180x180"
      href="%PUBLIC_URL%/apple-touch-icon.png"
    />
    <!--
      Notice the use of %PUBLIC_URL% in the tags above.
      It will be replaced with the URL of the `public` folder during the build.
      Only files inside the `public` folder can be referenced from the HTML.

      Unlike "/favicon.ico" or "favicon.ico", "%PUBLIC_URL%/favicon.ico" will
      work correctly both with client-side routing and a non-root public URL.
      Learn how to configure a non-root public URL by running `npm run build`.
    -->

    <!--
      Roboto is the default font for Material-UI. Baloo+Bhaijaan is only used for the logo
    -->
    <link
      href="https://fonts.googleapis.com/css?family=Baloo+Bhaijaan%7CRoboto:300,400,500&display=swap"
      rel="stylesheet"
    />
    <title>
      WaVer - Free React template for building an SaaS or admin application
    </title>
  </head>
  <body>
    <noscript> You need to enable JavaScript to run this app. </noscript>
    <div id="root"></div>
    <!--
      This HTML file is a template.
      If you open it directly in the browser, you will see an empty page.

      You can add webfonts, meta tags, or analytics to this file.
      The build step will place the bundled scripts into the <body> tag.

      To begin the development, run `npm start` or `yarn start`.
      To create a production bundle, use `npm run build` or `yarn build`.
    -->
  </body>
</html>



================================================
FILE: public/manifest.json
================================================
{
  "short_name": "WaVer",
  "name": "WaVer react template",
  "icons": [
    {
      "src": "favicon.ico",
      "sizes": "64x64 32x32 16x16",
      "type": "image/x-icon"
    },
    {
      "src": "favicon-192x192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "favicon-512x512.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ],
  "start_url": "./index.html",
  "display": "standalone",
  "theme_color": "#b3294e",
  "background_color": "#f5f5f5"
}



================================================
FILE: public/robots.txt
================================================
User-agent: *
Allow: /




================================================
FILE: src/App.js
================================================
import React, { Fragment, Suspense, lazy } from "react";
import { ThemeProvider, StyledEngineProvider, CssBaseline } from "@mui/material";
import { BrowserRouter, Route, Switch } from "react-router-dom";
import theme from "./theme";
import GlobalStyles from "./GlobalStyles";
import Pace from "./shared/components/Pace";

const LoggedInComponent = lazy(() => import("./logged_in/components/Main"));

const LoggedOutComponent = lazy(() => import("./logged_out/components/Main"));

function App() {
  return (
    <BrowserRouter>
      <StyledEngineProvider injectFirst>
        <ThemeProvider theme={theme}>
          <CssBaseline />
          <GlobalStyles />
          <Pace color={theme.palette.primary.light} />
          <Suspense fallback={<Fragment />}>
            <Switch>
              <Route path="/c">
                <LoggedInComponent />
              </Route>
              <Route>
                <LoggedOutComponent />
              </Route>
            </Switch>
          </Suspense>
        </ThemeProvider>
      </StyledEngineProvider>
    </BrowserRouter>
  );
}

export default App;



================================================
FILE: src/App.test.js
================================================
import React from "react";
import { render } from "@testing-library/react";
import App from "./App";

test("Trying to render <App />", () => {
  render(<App />);
});



================================================
FILE: src/GlobalStyles.js
================================================
import withStyles from '@mui/styles/withStyles';

const styles = theme => ({
  "@global": {
    /**
     * Disable the focus outline, which is default on some browsers like
     * chrome when focusing elements
     */
    "*:focus": {
      outline: 0
    },
    ".text-white": {
      color: theme.palette.common.white
    },
    ".listItemLeftPadding": {
      paddingTop: `${theme.spacing(1.75)} !important`,
      paddingBottom: `${theme.spacing(1.75)} !important`,
      paddingLeft: `${theme.spacing(4)} !important`,
      [theme.breakpoints.down('md')]: {
        paddingLeft: `${theme.spacing(4)} !important`
      },
      "@media (max-width:  420px)": {
        paddingLeft: `${theme.spacing(1)} !important`
      }
    },
    ".container": {
      width: "100%",
      paddingRight: theme.spacing(4),
      paddingLeft: theme.spacing(4),
      marginRight: "auto",
      marginLeft: "auto",
      [theme.breakpoints.up("sm")]: {
        maxWidth: 540
      },
      [theme.breakpoints.up("md")]: {
        maxWidth: 720
      },
      [theme.breakpoints.up("lg")]: {
        maxWidth: 1170
      }
    },
    ".row": {
      display: "flex",
      flexWrap: "wrap",
      marginRight: -theme.spacing(2),
      marginLeft: -theme.spacing(2)
    },
    ".container-fluid": {
      width: "100%",
      paddingRight: theme.spacing(2),
      paddingLeft: theme.spacing(2),
      marginRight: "auto",
      marginLeft: "auto",
      maxWidth: 1370
    },
    ".lg-mg-top": {
      marginTop: `${theme.spacing(20)} !important`,
      [theme.breakpoints.down('lg')]: {
        marginTop: `${theme.spacing(18)} !important`
      },
      [theme.breakpoints.down('md')]: {
        marginTop: `${theme.spacing(16)} !important`
      },
      [theme.breakpoints.down('sm')]: {
        marginTop: `${theme.spacing(14)} !important`
      }
    },
    ".lg-mg-bottom": {
      marginBottom: `${theme.spacing(20)} !important`,
      [theme.breakpoints.down('lg')]: {
        marginBottom: `${theme.spacing(18)} !important`
      },
      [theme.breakpoints.down('md')]: {
        marginBottom: `${theme.spacing(16)} !important`
      },
      [theme.breakpoints.down('sm')]: {
        marginBottom: `${theme.spacing(14)} !important`
      }
    },
    ".lg-p-top": {
      paddingTop: `${theme.spacing(20)} !important`,
      [theme.breakpoints.down('lg')]: {
        paddingTop: `${theme.spacing(18)} !important`
      },
      [theme.breakpoints.down('md')]: {
        paddingTop: `${theme.spacing(16)} !important`
      },
      [theme.breakpoints.down('sm')]: {
        paddingTop: `${theme.spacing(14)} !important`
      }
    }
  }
});

function globalStyles() {
  return null;
}

export default withStyles(styles, { withTheme: true })(globalStyles);



================================================
FILE: src/index.js
================================================
import React from "react";
import ReactDOM from "react-dom";
import App from "./App";
import * as serviceWorkerRegistration from './serviceWorkerRegistration';

ReactDOM.render(
  <App />,
  document.getElementById("root")
);

serviceWorkerRegistration.register();



================================================
FILE: src/service-worker.js
================================================
/* eslint-disable no-restricted-globals */

// This service worker can be customized!
// See https://developers.google.com/web/tools/workbox/modules
// for the list of available Workbox modules, or add any other
// code you'd like.
// You can also remove this file if you'd prefer not to use a
// service worker, and the Workbox build step will be skipped.

import { clientsClaim } from 'workbox-core';
import { ExpirationPlugin } from 'workbox-expiration';
import { precacheAndRoute, createHandlerBoundToURL } from 'workbox-precaching';
import { registerRoute } from 'workbox-routing';
import { StaleWhileRevalidate } from 'workbox-strategies';

clientsClaim();

// Precache all of the assets generated by your build process.
// Their URLs are injected into the manifest variable below.
// This variable must be present somewhere in your service worker file,
// even if you decide not to use precaching. See https://cra.link/PWA
precacheAndRoute(self.__WB_MANIFEST);

// Set up App Shell-style routing, so that all navigation requests
// are fulfilled with your index.html shell. Learn more at
// https://developers.google.com/web/fundamentals/architecture/app-shell
const fileExtensionRegexp = new RegExp('/[^/?]+\\.[^/]+$');
registerRoute(
  // Return false to exempt requests from being fulfilled by index.html.
  ({ request, url }) => {
    // If this isn't a navigation, skip.
    if (request.mode !== 'navigate') {
      return false;
    } // If this is a URL that starts with /_, skip.

    if (url.pathname.startsWith('/_')) {
      return false;
    } // If this looks like a URL for a resource, because it contains // a file extension, skip.

    if (url.pathname.match(fileExtensionRegexp)) {
      return false;
    } // Return true to signal that we want to use the handler.

    return true;
  },
  createHandlerBoundToURL(process.env.PUBLIC_URL + '/index.html')
);

// An example runtime caching route for requests that aren't handled by the
// precache, in this case same-origin .png requests like those from in public/
registerRoute(
  // Add in any other file extensions or routing criteria as needed.
  ({ url }) => url.origin === self.location.origin && url.pathname.endsWith('.png'), // Customize this strategy as needed, e.g., by changing to CacheFirst.
  new StaleWhileRevalidate({
    cacheName: 'images',
    plugins: [
      // Ensure that once this runtime cache reaches a maximum size the
      // least-recently used images are removed.
      new ExpirationPlugin({ maxEntries: 50 }),
    ],
  })
);

// This allows the web app to trigger skipWaiting via
// registration.waiting.postMessage({type: 'SKIP_WAITING'})
self.addEventListener('message', (event) => {
  if (event.data && event.data.type === 'SKIP_WAITING') {
    self.skipWaiting();
  }
});

// Any other custom service worker logic can go here.



================================================
FILE: src/serviceWorkerRegistration.js
================================================
// This optional code is used to register a service worker.
// register() is not called by default.

// This lets the app load faster on subsequent visits in production, and gives
// it offline capabilities. However, it also means that developers (and users)
// will only see deployed updates on subsequent visits to a page, after all the
// existing tabs open on the page have been closed, since previously cached
// resources are updated in the background.

// To learn more about the benefits of this model and instructions on how to
// opt-in, read https://cra.link/PWA

const isLocalhost = Boolean(
  window.location.hostname === 'localhost' ||
    // [::1] is the IPv6 localhost address.
    window.location.hostname === '[::1]' ||
    // 127.0.0.0/8 are considered localhost for IPv4.
    window.location.hostname.match(/^127(?:\.(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)){3}$/)
);

export function register(config) {
  if (process.env.NODE_ENV === 'production' && 'serviceWorker' in navigator) {
    // The URL constructor is available in all browsers that support SW.
    const publicUrl = new URL(process.env.PUBLIC_URL, window.location.href);
    if (publicUrl.origin !== window.location.origin) {
      // Our service worker won't work if PUBLIC_URL is on a different origin
      // from what our page is served on. This might happen if a CDN is used to
      // serve assets; see https://github.com/facebook/create-react-app/issues/2374
      return;
    }

    window.addEventListener('load', () => {
      const swUrl = `${process.env.PUBLIC_URL}/service-worker.js`;

      if (isLocalhost) {
        // This is running on localhost. Let's check if a service worker still exists or not.
        checkValidServiceWorker(swUrl, config);

        // Add some additional logging to localhost, pointing developers to the
        // service worker/PWA documentation.
        navigator.serviceWorker.ready.then(() => {
          console.log(
            'This web app is being served cache-first by a service ' +
              'worker. To learn more, visit https://cra.link/PWA'
          );
        });
      } else {
        // Is not localhost. Just register service worker
        registerValidSW(swUrl, config);
      }
    });
  }
}

function registerValidSW(swUrl, config) {
  navigator.serviceWorker
    .register(swUrl)
    .then((registration) => {
      registration.onupdatefound = () => {
        const installingWorker = registration.installing;
        if (installingWorker == null) {
          return;
        }
        installingWorker.onstatechange = () => {
          if (installingWorker.state === 'installed') {
            if (navigator.serviceWorker.controller) {
              // At this point, the updated precached content has been fetched,
              // but the previous service worker will still serve the older
              // content until all client tabs are closed.
              console.log(
                'New content is available and will be used when all ' +
                  'tabs for this page are closed. See https://cra.link/PWA.'
              );

              // Execute callback
              if (config && config.onUpdate) {
                config.onUpdate(registration);
              }
            } else {
              // At this point, everything has been precached.
              // It's the perfect time to display a
              // "Content is cached for offline use." message.
              console.log('Content is cached for offline use.');

              // Execute callback
              if (config && config.onSuccess) {
                config.onSuccess(registration);
              }
            }
          }
        };
      };
    })
    .catch((error) => {
      console.error('Error during service worker registration:', error);
    });
}

function checkValidServiceWorker(swUrl, config) {
  // Check if the service worker can be found. If it can't reload the page.
  fetch(swUrl, {
    headers: { 'Service-Worker': 'script' },
  })
    .then((response) => {
      // Ensure service worker exists, and that we really are getting a JS file.
      const contentType = response.headers.get('content-type');
      if (
        response.status === 404 ||
        (contentType != null && contentType.indexOf('javascript') === -1)
      ) {
        // No service worker found. Probably a different app. Reload the page.
        navigator.serviceWorker.ready.then((registration) => {
          registration.unregister().then(() => {
            window.location.reload();
          });
        });
      } else {
        // Service worker found. Proceed as normal.
        registerValidSW(swUrl, config);
      }
    })
    .catch(() => {
      console.log('No internet connection found. App is running in offline mode.');
    });
}

export function unregister() {
  if ('serviceWorker' in navigator) {
    navigator.serviceWorker.ready
      .then((registration) => {
        registration.unregister();
      })
      .catch((error) => {
        console.error(error.message);
      });
  }
}



================================================
FILE: src/setupTests.js
================================================
// jest-dom adds custom jest matchers for asserting on DOM nodes.
// allows you to do things like:
// expect(element).toHaveTextContent(/react/i)
// learn more: https://github.com/testing-library/jest-dom
import '@testing-library/jest-dom/extend-expect';



================================================
FILE: src/theme.js
================================================
import { createTheme, responsiveFontSizes, adaptV4Theme } from "@mui/material";

// colors
const primary = "#b3294e";
const secondary = "#4829B2";
const black = "#343a40";
const darkBlack = "rgb(36, 40, 44)";
const background = "#f5f5f5";
const warningLight = "rgba(253, 200, 69, .3)";
const warningMain = "rgba(253, 200, 69, .5)";
const warningDark = "rgba(253, 200, 69, .7)";

// border
const borderWidth = 2;
const borderColor = "rgba(0, 0, 0, 0.13)";

// breakpoints
const xl = 1920;
const lg = 1280;
const md = 960;
const sm = 600;
const xs = 0;

// spacing
const spacing = 8;

const theme = createTheme(adaptV4Theme({
  palette: {
    primary: { main: primary },
    secondary: { main: secondary },
    common: {
      black,
      darkBlack
    },
    warning: {
      light: warningLight,
      main: warningMain,
      dark: warningDark
    },
    // Used to shift a color's luminance by approximately
    // two indexes within its tonal palette.
    // E.g., shift from Red 500 to Red 300 or Red 700.
    tonalOffset: 0.2,
    background: {
      default: background
    },
    spacing
  },
  breakpoints: {
    // Define custom breakpoint values.
    // These will apply to Material-UI components that use responsive
    // breakpoints, such as `Grid` and `Hidden`. You can also use the
    // theme breakpoint functions `up`, `down`, and `between` to create
    // media queries for these breakpoints
    values: {
      xl,
      lg,
      md,
      sm,
      xs
    }
  },
  border: {
    borderColor: borderColor,
    borderWidth: borderWidth
  },
  overrides: {
    MuiExpansionPanel: {
      root: {
        position: "static"
      }
    },
    MuiTableCell: {
      root: {
        paddingLeft: spacing * 2,
        paddingRight: spacing * 2,
        borderBottom: `${borderWidth}px solid ${borderColor}`,
        [`@media (max-width:  ${sm}px)`]: {
          paddingLeft: spacing,
          paddingRight: spacing
        }
      }
    },
    MuiDivider: {
      root: {
        backgroundColor: borderColor,
        height: borderWidth
      }
    },
    MuiPrivateNotchedOutline: {
      root: {
        borderWidth: borderWidth
      }
    },
    MuiListItem: {
      divider: {
        borderBottom: `${borderWidth}px solid ${borderColor}`
      }
    },
    MuiDialog: {
      paper: {
        width: "100%",
        maxWidth: 430,
        marginLeft: spacing,
        marginRight: spacing
      }
    },
    MuiTooltip: {
      tooltip: {
        backgroundColor: darkBlack
      }
    },
    MuiExpansionPanelDetails: {
      root: {
        [`@media (max-width:  ${sm}px)`]: {
          paddingLeft: spacing,
          paddingRight: spacing
        }
      }
    }
  },
  typography: {
    useNextVariants: true
  }
}));

export default responsiveFontSizes(theme);



================================================
FILE: src/logged_in/components/Main.js
================================================
import React, { memo, useCallback, useState, useEffect, Fragment } from "react";
import PropTypes from "prop-types";
import classNames from "classnames";
import withStyles from '@mui/styles/withStyles';
import Routing from "./Routing";
import NavBar from "./navigation/NavBar";
import ConsecutiveSnackbarMessages from "../../shared/components/ConsecutiveSnackbarMessages";
import smoothScrollTop from "../../shared/functions/smoothScrollTop";
import persons from "../dummy_data/persons";
import LazyLoadAddBalanceDialog from "./subscription/LazyLoadAddBalanceDialog";

const styles = (theme) => ({
  main: {
    marginLeft: theme.spacing(9),
    transition: theme.transitions.create(["width", "margin"], {
      easing: theme.transitions.easing.sharp,
      duration: theme.transitions.duration.leavingScreen,
    }),
    [theme.breakpoints.down('sm')]: {
      marginLeft: 0,
    },
  },
});

function shuffle(array) {
  for (let i = array.length - 1; i > 0; i--) {
    let j = Math.floor(Math.random() * (i + 1));
    [array[i], array[j]] = [array[j], array[i]];
  }
}

function Main(props) {
  const { classes } = props;
  const [selectedTab, setSelectedTab] = useState(null);
  const [CardChart, setCardChart] = useState(null);
  const [hasFetchedCardChart, setHasFetchedCardChart] = useState(false);
  const [EmojiTextArea, setEmojiTextArea] = useState(null);
  const [hasFetchedEmojiTextArea, setHasFetchedEmojiTextArea] = useState(false);
  const [ImageCropper, setImageCropper] = useState(null);
  const [hasFetchedImageCropper, setHasFetchedImageCropper] = useState(false);
  const [Dropzone, setDropzone] = useState(null);
  const [hasFetchedDropzone, setHasFetchedDropzone] = useState(false);
  const [DateTimePicker, setDateTimePicker] = useState(null);
  const [hasFetchedDateTimePicker, setHasFetchedDateTimePicker] = useState(
    false
  );
  const [transactions, setTransactions] = useState([]);
  const [statistics, setStatistics] = useState({ views: [], profit: [] });
  const [posts, setPosts] = useState([]);
  const [targets, setTargets] = useState([]);
  const [messages, setMessages] = useState([]);
  const [isAccountActivated, setIsAccountActivated] = useState(false);
  const [isAddBalanceDialogOpen, setIsAddBalanceDialogOpen] = useState(false);
  const [pushMessageToSnackbar, setPushMessageToSnackbar] = useState(null);

  const fetchRandomTargets = useCallback(() => {
    const targets = [];
    for (let i = 0; i < 35; i += 1) {
      const randomPerson = persons[Math.floor(Math.random() * persons.length)];
      const target = {
        id: i,
        number1: Math.floor(Math.random() * 251),
        number2: Math.floor(Math.random() * 251),
        number3: Math.floor(Math.random() * 251),
        number4: Math.floor(Math.random() * 251),
        name: randomPerson.name,
        profilePicUrl: randomPerson.src,
        isActivated: Math.round(Math.random()) ? true : false,
      };
      targets.push(target);
    }
    setTargets(targets);
  }, [setTargets]);

  const openAddBalanceDialog = useCallback(() => {
    setIsAddBalanceDialogOpen(true);
  }, [setIsAddBalanceDialogOpen]);

  const closeAddBalanceDialog = useCallback(() => {
    setIsAddBalanceDialogOpen(false);
  }, [setIsAddBalanceDialogOpen]);

  const onPaymentSuccess = useCallback(() => {
    pushMessageToSnackbar({
      text: "Your balance has been updated.",
    });
    setIsAddBalanceDialogOpen(false);
  }, [pushMessageToSnackbar, setIsAddBalanceDialogOpen]);

  const fetchRandomStatistics = useCallback(() => {
    const statistics = { profit: [], views: [] };
    const iterations = 300;
    const oneYearSeconds = 60 * 60 * 24 * 365;
    let curProfit = Math.round(3000 + Math.random() * 1000);
    let curViews = Math.round(3000 + Math.random() * 1000);
    let curUnix = Math.round(new Date().getTime() / 1000) - oneYearSeconds;
    for (let i = 0; i < iterations; i += 1) {
      curUnix += Math.round(oneYearSeconds / iterations);
      curProfit += Math.round((Math.random() * 2 - 1) * 10);
      curViews += Math.round((Math.random() * 2 - 1) * 10);
      statistics.profit.push({
        value: curProfit,
        timestamp: curUnix,
      });
      statistics.views.push({
        value: curViews,
        timestamp: curUnix,
      });
    }
    setStatistics(statistics);
  }, [setStatistics]);

  const fetchRandomTransactions = useCallback(() => {
    const transactions = [];
    const iterations = 32;
    const oneMonthSeconds = Math.round(60 * 60 * 24 * 30.5);
    const transactionTemplates = [
      {
        description: "Starter subscription",
        isSubscription: true,
        balanceChange: -1499,
      },
      {
        description: "Premium subscription",
        isSubscription: true,
        balanceChange: -2999,
      },
      {
        description: "Business subscription",
        isSubscription: true,
        balanceChange: -4999,
      },
      {
        description: "Tycoon subscription",
        isSubscription: true,
        balanceChange: -9999,
      },
      {
        description: "Added funds",
        isSubscription: false,
        balanceChange: 2000,
      },
      {
        description: "Added funds",
        isSubscription: false,
        balanceChange: 5000,
      },
    ];
    let curUnix = Math.round(
      new Date().getTime() / 1000 - iterations * oneMonthSeconds
    );
    for (let i = 0; i < iterations; i += 1) {
      const randomTransactionTemplate =
        transactionTemplates[
          Math.floor(Math.random() * transactionTemplates.length)
        ];
      const transaction = {
        id: i,
        description: randomTransactionTemplate.description,
        balanceChange: randomTransactionTemplate.balanceChange,
        paidUntil: curUnix + oneMonthSeconds,
        timestamp: curUnix,
      };
      curUnix += oneMonthSeconds;
      transactions.push(transaction);
    }
    transactions.reverse();
    setTransactions(transactions);
  }, [setTransactions]);

  const fetchRandomMessages = useCallback(() => {
    shuffle(persons);
    const messages = [];
    const iterations = persons.length;
    const oneDaySeconds = 60 * 60 * 24;
    let curUnix = Math.round(
      new Date().getTime() / 1000 - iterations * oneDaySeconds
    );
    for (let i = 0; i < iterations; i += 1) {
      const person = persons[i];
      const message = {
        id: i,
        src: person.src,
        date: curUnix,
        text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr sed.",
      };
      curUnix += oneDaySeconds;
      messages.push(message);
    }
    messages.reverse();
    setMessages(messages);
  }, [setMessages]);

  const fetchRandomPosts = useCallback(() => {
    shuffle(persons);
    const posts = [];
    const iterations = persons.length;
    const oneDaySeconds = 60 * 60 * 24;
    let curUnix = Math.round(
      new Date().getTime() / 1000 - iterations * oneDaySeconds
    );
    for (let i = 0; i < iterations; i += 1) {
      const person = persons[i];
      const post = {
        id: i,
        src: person.src,
        timestamp: curUnix,
        name: person.name,
      };
      curUnix += oneDaySeconds;
      posts.push(post);
    }
    posts.reverse();
    setPosts(posts);
  }, [setPosts]);

  const toggleAccountActivation = useCallback(() => {
    if (pushMessageToSnackbar) {
      if (isAccountActivated) {
        pushMessageToSnackbar({
          text: "Your account is now deactivated.",
        });
      } else {
        pushMessageToSnackbar({
          text: "Your account is now activated.",
        });
      }
    }
    setIsAccountActivated(!isAccountActivated);
  }, [pushMessageToSnackbar, isAccountActivated, setIsAccountActivated]);

  const selectDashboard = useCallback(() => {
    smoothScrollTop();
    document.title = "WaVer - Dashboard";
    setSelectedTab("Dashboard");
    if (!hasFetchedCardChart) {
      setHasFetchedCardChart(true);
      import("../../shared/components/CardChart").then((Component) => {
        setCardChart(Component.default);
      });
    }
  }, [
    setSelectedTab,
    setCardChart,
    hasFetchedCardChart,
    setHasFetchedCardChart,
  ]);

  const selectPosts = useCallback(() => {
    smoothScrollTop();
    document.title = "WaVer - Posts";
    setSelectedTab("Posts");
    if (!hasFetchedEmojiTextArea) {
      setHasFetchedEmojiTextArea(true);
      import("../../shared/components/EmojiTextArea").then((Component) => {
        setEmojiTextArea(Component.default);
      });
    }
    if (!hasFetchedImageCropper) {
      setHasFetchedImageCropper(true);
      import("../../shared/components/ImageCropper").then((Component) => {
        setImageCropper(Component.default);
      });
    }
    if (!hasFetchedDropzone) {
      setHasFetchedDropzone(true);
      import("../../shared/components/Dropzone").then((Component) => {
        setDropzone(Component.default);
      });
    }
    if (!hasFetchedDateTimePicker) {
      setHasFetchedDateTimePicker(true);
      import("../../shared/components/DateTimePicker").then((Component) => {
        setDateTimePicker(Component.default);
      });
    }
  }, [
    setSelectedTab,
    setEmojiTextArea,
    setImageCropper,
    setDropzone,
    setDateTimePicker,
    hasFetchedEmojiTextArea,
    setHasFetchedEmojiTextArea,
    hasFetchedImageCropper,
    setHasFetchedImageCropper,
    hasFetchedDropzone,
    setHasFetchedDropzone,
    hasFetchedDateTimePicker,
    setHasFetchedDateTimePicker,
  ]);

  const selectSubscription = useCallback(() => {
    smoothScrollTop();
    document.title = "WaVer - Subscription";
    setSelectedTab("Subscription");
  }, [setSelectedTab]);

  const getPushMessageFromChild = useCallback(
    (pushMessage) => {
      setPushMessageToSnackbar(() => pushMessage);
    },
    [setPushMessageToSnackbar]
  );

  useEffect(() => {
    fetchRandomTargets();
    fetchRandomStatistics();
    fetchRandomTransactions();
    fetchRandomMessages();
    fetchRandomPosts();
  }, [
    fetchRandomTargets,
    fetchRandomStatistics,
    fetchRandomTransactions,
    fetchRandomMessages,
    fetchRandomPosts,
  ]);

  return (
    <Fragment>
      <LazyLoadAddBalanceDialog
        open={isAddBalanceDialogOpen}
        onClose={closeAddBalanceDialog}
        onSuccess={onPaymentSuccess}
      />
      <NavBar
        selectedTab={selectedTab}
        messages={messages}
        openAddBalanceDialog={openAddBalanceDialog}
      />
      <ConsecutiveSnackbarMessages
        getPushMessageFromChild={getPushMessageFromChild}
      />
      <main className={classNames(classes.main)}>
        <Routing
          isAccountActivated={isAccountActivated}
          ImageCropper={ImageCropper}
          EmojiTextArea={EmojiTextArea}
          CardChart={CardChart}
          Dropzone={Dropzone}
          DateTimePicker={DateTimePicker}
          toggleAccountActivation={toggleAccountActivation}
          pushMessageToSnackbar={pushMessageToSnackbar}
          transactions={transactions}
          statistics={statistics}
          posts={posts}
          targets={targets}
          selectDashboard={selectDashboard}
          selectPosts={selectPosts}
          selectSubscription={selectSubscription}
          openAddBalanceDialog={openAddBalanceDialog}
          setTargets={setTargets}
          setPosts={setPosts}
        />
      </main>
    </Fragment>
  );
}

Main.propTypes = {
  classes: PropTypes.object.isRequired,
};

export default withStyles(styles, { withTheme: true })(memo(Main));



================================================
FILE: src/logged_in/components/Routing.js
================================================
import React, { memo } from "react";
import PropTypes from "prop-types";
import { Switch } from "react-router-dom";
import withStyles from '@mui/styles/withStyles';
import Dashboard from "./dashboard/Dashboard";
import Posts from "./posts/Posts";
import Subscription from "./subscription/Subscription";
import PropsRoute from "../../shared/components/PropsRoute";
import useLocationBlocker from "../../shared/functions/useLocationBlocker";

const styles = (theme) => ({
  wrapper: {
    margin: theme.spacing(1),
    width: "auto",
    [theme.breakpoints.up("xs")]: {
      width: "95%",
      marginLeft: "auto",
      marginRight: "auto",
      marginTop: theme.spacing(4),
      marginBottom: theme.spacing(4),
    },
    [theme.breakpoints.up("sm")]: {
      marginTop: theme.spacing(6),
      marginBottom: theme.spacing(6),
      width: "90%",
      marginLeft: "auto",
      marginRight: "auto",
    },
    [theme.breakpoints.up("md")]: {
      marginTop: theme.spacing(6),
      marginBottom: theme.spacing(6),
      width: "82.5%",
      marginLeft: "auto",
      marginRight: "auto",
    },
    [theme.breakpoints.up("lg")]: {
      marginTop: theme.spacing(6),
      marginBottom: theme.spacing(6),
      width: "70%",
      marginLeft: "auto",
      marginRight: "auto",
    },
  },
});

function Routing(props) {
  const {
    classes,
    EmojiTextArea,
    ImageCropper,
    Dropzone,
    DateTimePicker,
    pushMessageToSnackbar,
    posts,
    transactions,
    toggleAccountActivation,
    CardChart,
    statistics,
    targets,
    setTargets,
    setPosts,
    isAccountActivated,
    selectDashboard,
    selectPosts,
    selectSubscription,
    openAddBalanceDialog,
  } = props;
  useLocationBlocker();
  return (
    <div className={classes.wrapper}>
      <Switch>
        <PropsRoute
          path="/c/posts"
          component={Posts}
          EmojiTextArea={EmojiTextArea}
          ImageCropper={ImageCropper}
          Dropzone={Dropzone}
          DateTimePicker={DateTimePicker}
          pushMessageToSnackbar={pushMessageToSnackbar}
          posts={posts}
          setPosts={setPosts}
          selectPosts={selectPosts}
        />
        <PropsRoute
          path="/c/subscription"
          component={Subscription}
          transactions={transactions}
          pushMessageToSnackbar={pushMessageToSnackbar}
          selectSubscription={selectSubscription}
          openAddBalanceDialog={openAddBalanceDialog}
        />
        <PropsRoute
          path=""
          component={Dashboard}
          toggleAccountActivation={toggleAccountActivation}
          pushMessageToSnackbar={pushMessageToSnackbar}
          CardChart={CardChart}
          statistics={statistics}
          targets={targets}
          setTargets={setTargets}
          isAccountActivated={isAccountActivated}
          selectDashboard={selectDashboard}
        />
      </Switch>
    </div>
  );
}

Routing.propTypes = {
  classes: PropTypes.object.isRequired,
  EmojiTextArea: PropTypes.elementType,
  ImageCropper: PropTypes.elementType,
  Dropzone: PropTypes.elementType,
  DateTimePicker: PropTypes.elementType,
  pushMessageToSnackbar: PropTypes.func,
  setTargets: PropTypes.func.isRequired,
  setPosts: PropTypes.func.isRequired,
  posts: PropTypes.arrayOf(PropTypes.object).isRequired,
  transactions: PropTypes.arrayOf(PropTypes.object).isRequired,
  toggleAccountActivation: PropTypes.func,
  CardChart: PropTypes.elementType,
  statistics: PropTypes.object.isRequired,
  targets: PropTypes.arrayOf(PropTypes.object).isRequired,
  isAccountActivated: PropTypes.bool.isRequired,
  selectDashboard: PropTypes.func.isRequired,
  selectPosts: PropTypes.func.isRequired,
  selectSubscription: PropTypes.func.isRequired,
  openAddBalanceDialog: PropTypes.func.isRequired,
};

export default withStyles(styles, { withTheme: true })(memo(Routing));



================================================
FILE: src/logged_in/components/dashboard/AccountInformationArea.js
================================================
import React from "react";
import PropTypes from "prop-types";
import classNames from "classnames";
import {
  Paper,
  Toolbar,
  ListItemText,
  ListItemSecondaryAction,
  ListItemIcon,
  Switch,
  Box,
} from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import LoopIcon from "@mui/icons-material/Loop";

const styles = theme => ({
  paper: {
    borderBottomLeftRadius: 0,
    borderBottomRightRadius: 0
  },
  toolbar: { justifyContent: "space-between" },
  scaleMinus: {
    transform: "scaleX(-1)"
  },
  "@keyframes spin": {
    from: { transform: "rotate(359deg)" },
    to: { transform: "rotate(0deg)" }
  },
  spin: { animation: "$spin 2s infinite linear" },
  listItemSecondaryAction: { paddingRight: theme.spacing(1) }
});

function AccountInformationArea(props) {
  const { classes, toggleAccountActivation, isAccountActivated } = props;
  return (
    <Paper className={classes.paper}>
      <Toolbar className={classes.toolbar}>
        <Box display="flex" alignItems="center">
          <Box mr={2}>
            <ListItemText
              primary="Status"
              secondary={isAccountActivated ? "Activated" : "Not activated"}
              className="mr-2"
            />
          </Box>
          <ListItemIcon>
            <LoopIcon
              className={classNames(
                isAccountActivated ? classes.spin : null,
                classes.scaleMinus
              )}
            />
          </ListItemIcon>
        </Box>
        <ListItemSecondaryAction className={classes.listItemSecondaryAction}>
          <Switch
            color="secondary"
            checked={isAccountActivated}
            onClick={toggleAccountActivation}
            inputProps={{
              "aria-label": isAccountActivated
                ? "Deactivate Account"
                : "Activate Account"
            }}
          />
        </ListItemSecondaryAction>
      </Toolbar>
    </Paper>
  );
}

AccountInformationArea.propTypes = {
  classes: PropTypes.object.isRequired,
  theme: PropTypes.object.isRequired,
  toggleAccountActivation: PropTypes.func.isRequired,
  isAccountActivated: PropTypes.bool.isRequired
};

export default withStyles(styles, { withTheme: true })(AccountInformationArea);



================================================
FILE: src/logged_in/components/dashboard/Dashboard.js
================================================
import React, { Fragment, useEffect } from "react";
import PropTypes from "prop-types";
import { Typography, Box } from "@mui/material";
import SettingsArea from "./SettingsArea";
import UserDataArea from "./UserDataArea";
import AccountInformationArea from "./AccountInformationArea";
import StatisticsArea from "./StatisticsArea";

function Dashboard(props) {
  const {
    selectDashboard,
    CardChart,
    statistics,
    toggleAccountActivation,
    pushMessageToSnackbar,
    targets,
    setTargets,
    isAccountActivated,
  } = props;

  useEffect(selectDashboard, [selectDashboard]);

  return (
    <Fragment>
      <StatisticsArea CardChart={CardChart} data={statistics} />
      <Box mt={4}>
        <Typography variant="subtitle1" gutterBottom>
          Your Account
        </Typography>
      </Box>
      <AccountInformationArea
        isAccountActivated={isAccountActivated}
        toggleAccountActivation={toggleAccountActivation}
      />
      <Box mt={4}>
        <Typography variant="subtitle1" gutterBottom>
          Settings
        </Typography>
      </Box>
      <SettingsArea pushMessageToSnackbar={pushMessageToSnackbar} />
      <UserDataArea
        pushMessageToSnackbar={pushMessageToSnackbar}
        targets={targets}
        setTargets={setTargets}
      />
    </Fragment>
  );
}

Dashboard.propTypes = {
  CardChart: PropTypes.elementType,
  statistics: PropTypes.object.isRequired,
  toggleAccountActivation: PropTypes.func,
  pushMessageToSnackbar: PropTypes.func,
  targets: PropTypes.arrayOf(PropTypes.object).isRequired,
  setTargets: PropTypes.func.isRequired,
  isAccountActivated: PropTypes.bool.isRequired,
  selectDashboard: PropTypes.func.isRequired,
};

export default Dashboard;



================================================
FILE: src/logged_in/components/dashboard/Settings1.js
================================================
import React, { useState, useCallback } from "react";
import PropTypes from "prop-types";
import {
  List,
  ListItem,
  ListItemSecondaryAction,
  Button,
  Accordion,
  AccordionSummary,
  Typography,
  ListItemText,
  OutlinedInput,
  AccordionDetails,
  MenuItem,
  FormControl,
  Select,
  Box,
} from "@mui/material";
import withStyles from "@mui/styles/withStyles";
import ExpandMoreIcon from "@mui/icons-material/ExpandMore";
import Bordered from "../../../shared/components/Bordered";
import ButtonCircularProgress from "../../../shared/components/ButtonCircularProgress";

const styles = (theme) => ({
  numberInput: {
    width: 110,
  },
  numberInputInput: {
    padding: "9px 34px 9px 14.5px",
  },
  dBlock: { display: "block" },
  listItemLeftPadding: {
    paddingRight: theme.spacing(3),
  },
  accordionDetails: {
    paddintTop: theme.spacing(0),
    display: "flex",
    justifyContent: "flex-end",
  },
});
const inputOptions = ["None", "Slow", "Normal", "Fast"];

function Settings1(props) {
  const { classes, pushMessageToSnackbar } = props;
  const [isSaveLoading, setIsSaveLoading] = useState(false);
  const [isDefaultLoading, setIsDefaultLoading] = useState(false);
  const [option1, setOption1] = useState("None");
  const [option2, setOption2] = useState("None");
  const [option3, setOption3] = useState("None");
  const [option4, setOption4] = useState("None");
  const [option5, setOption5] = useState("2 Days");
  const [option6, setOption6] = useState(7500);

  const handleChange = useCallback(
    (event) => {
      const { name, value } = event.target;
      if (name === "option6") {
        if (value > 7500 || value < 1000) {
          return;
        }
      }
      switch (name) {
        case "option1": {
          setOption1(value);
          break;
        }
        case "option2": {
          setOption2(value);
          break;
        }
        case "option3": {
          setOption3(value);
          break;
        }
        case "option4": {
          setOption4(value);
          break;
        }
        case "option5": {
          setOption5(value);
          break;
        }
        case "option6": {
          setOption6(value);
          break;
        }
        default:
          throw new Error("No branch selected in switch statement.");
      }
    },
    [setOption1, setOption2, setOption3, setOption4, setOption5, setOption6]
  );

  const resetState = useCallback(() => {
    setIsSaveLoading(false);
    setIsDefaultLoading(false);
    setOption1("None");
    setOption2("None");
    setOption3("None");
    setOption4("None");
    setOption5("2 Days");
    setOption6(7500);
  }, [
    setIsSaveLoading,
    setIsDefaultLoading,
    setOption1,
    setOption2,
    setOption3,
    setOption4,
    setOption5,
    setOption6,
  ]);

  const onSetDefault = useCallback(() => {
    setIsDefaultLoading(true);
    setTimeout(() => {
      pushMessageToSnackbar({
        text: "Your settings have been reset to default",
      });
      resetState();
    }, 1500);
  }, [pushMessageToSnackbar, resetState]);

  const onSubmit = useCallback(() => {
    setIsSaveLoading(true);
    setTimeout(() => {
      pushMessageToSnackbar({
        text: "Your settings have been saved",
      });
      setIsSaveLoading(false);
    }, 1500);
  }, [setIsSaveLoading, pushMessageToSnackbar]);

  const inputs = [
    {
      state: option1,
      label: "Option 1",
      stateName: "option1",
    },
    {
      state: option2,
      label: "Option 2",
      stateName: "option2",
    },
    {
      state: option3,
      label: "Option 3",
      stateName: "option3",
    },
    {
      state: option4,
      label: "Option 4",
      stateName: "option4",
    },
  ];

  return (
    <Accordion>
      <AccordionSummary expandIcon={<ExpandMoreIcon />}>
        <Typography>Settings 1</Typography>
      </AccordionSummary>
      <AccordionDetails className={classes.dBlock}>
        <List disablePadding>
          <Bordered disableVerticalPadding disableBorderRadius>
            {inputs.map((element, index) => (
              <ListItem
                className="listItemLeftPadding"
                disableGutters
                divider
                key={index}
              >
                <ListItemText>
                  <Typography variant="body2">{element.label}</Typography>
                </ListItemText>
                <FormControl variant="outlined">
                  <ListItemSecondaryAction
                    className={classes.ListItemSecondaryAction}
                  >
                    <Select
                      value={element.state}
                      onChange={handleChange}
                      input={
                        <OutlinedInput
                          name={element.stateName}
                          labelWidth={0}
                          className={classes.numberInput}
                          classes={{ input: classes.numberInputInput }}
                        />
                      }
                      MenuProps={{ disableScrollLock: true }}
                    >
                      {inputOptions.map((innerElement) => (
                        <MenuItem value={innerElement} key={innerElement}>
                          {innerElement}
                        </MenuItem>
                      ))}
                    </Select>
                  </ListItemSecondaryAction>
                </FormControl>
              </ListItem>
            ))}
            <ListItem className="listItemLeftPadding" disableGutters divider>
              <ListItemText>
                <Typography variant="body2">Option 5</Typography>
              </ListItemText>
              <FormControl variant="outlined">
                <ListItemSecondaryAction
                  className={classes.ListItemSecondaryAction}
                >
                  <Select
                    value={option5}
                    onChange={handleChange}
                    input={
                      <OutlinedInput
                        name="option5"
                        labelWidth={0}
                        className={classes.numberInput}
                        classes={{ input: classes.numberInputInput }}
                      />
                    }
                    MenuProps={{ disableScrollLock: true }}
                  >
                    {[
                      "Always",
                      "6 Hours",
                      "12 Hours",
                      "1 Day",
                      "2 Days",
                      "3 Days",
                      "1 Week",
                    ].map((element) => (
                      <MenuItem value={element} key={element}>
                        {element}
                      </MenuItem>
                    ))}
                  </Select>
                </ListItemSecondaryAction>
              </FormControl>
            </ListItem>
            <ListItem className="listItemLeftPadding" disableGutters>
              <ListItemText>
                <Typography variant="body2">Option 6</Typography>
              </ListItemText>
              <FormControl variant="outlined">
                <ListItemSecondaryAction
                  className={classes.ListItemSecondaryAction}
                >
                  <OutlinedInput
                    labelWidth={0}
                    name="option6"
                    value={option6}
                    type="number"
                    onChange={handleChange}
                    className={classes.numberInput}
                    classes={{ input: classes.numberInputInput }}
                    inputProps={{ step: 20 }}
                  />
                </ListItemSecondaryAction>
              </FormControl>
            </ListItem>
          </Bordered>
        </List>
      </AccordionDetails>
      <AccordionDetails className={classes.accordionDetails}>
        <Box mr={1}>
          <Button
            onClick={onSetDefault}
            disabled={isSaveLoading || isDefaultLoading}
          >
            Default {isDefaultLoading && <ButtonCircularProgress />}
          </Button>
        </Box>
        <Button
          variant="contained"
          color="secondary"
          disabled={isSaveLoading || isDefaultLoading}
          onClick={onSubmit}
        >
          Save {isSaveLoading && <ButtonCircularProgress />}
        </Button>
      </AccordionDetails>
    </Accordion>
  );
}

Settings1.propTypes = {
  classes: PropTypes.object.isRequired,
  theme: PropTypes.object.isRequired,
  pushMessageToSnackbar: PropTypes.func,
};

export default withStyles(styles, { withTheme: true })(Settings1);



================================================
FILE: src/logged_in/components/dashboard/Settings2.js
================================================
import React, { useState, useCallback } from "react";
import PropTypes from "prop-types";
import {
  Accordion,
  AccordionSummary,
  AccordionDetails,
  Typography,
  Button,
  List,
  ListItem,
  ListItemText,
  ListItemSecondaryAction,
  FormControl,
  Select,
  OutlinedInput,
  MenuItem,
  Checkbox,
  Box,
} from "@mui/material";
import withStyles from "@mui/styles/withStyles";
import ExpandMoreIcon from "@mui/icons-material/ExpandMore";
import HelpIcon from "../../../shared/components/HelpIcon";
import Bordered from "../../../shared/components/Bordered";
import ButtonCircularProgress from "../../../shared/components/ButtonCircularProgress";

const styles = (theme) => ({
  numberInput: {
    width: 120,
    [theme.breakpoints.down("md")]: {
      width: 80,
    },
    "@media (max-width: 350px)": {
      width: 65,
    },
  },
  numberInputInput: {
    padding: "9px 14.5px",
    "@media (max-width: 380px)": {
      padding: "9px 8.5px",
    },
    "@media (max-width: 350px)": {
      padding: "9px 6.5px",
    },
  },
  listItem: {
    [theme.breakpoints.up("sm")]: {
      paddingLeft: theme.spacing(4),
    },
    paddingLeft: 100,
  },
  AccordionDetails: {
    paddingTop: theme.spacing(0),
    display: "flex",
    justifyContent: "flex-end",
  },
  dBlock: {
    display: "block",
  },
});

function Settings2(props) {
  const { pushMessageToSnackbar, classes } = props;
  const [isDefaultLoading, setIsDefaultLoading] = useState(false);
  const [isSaveLoading, setIsSaveLoading] = useState(false);
  const [option1, setOption1] = useState(false);
  const [option2, setOption2] = useState(false);
  const [option3, setOption3] = useState(false);
  const [option4, setOption4] = useState(false);
  const [option5, setOption5] = useState(false);
  const [option6, setOption6] = useState("Both");
  const [option7, setOption7] = useState("2 weeks");

  const resetState = useCallback(() => {
    setIsDefaultLoading(false);
    setIsSaveLoading(false);
    setOption1(false);
    setOption2(false);
    setOption3(false);
    setOption4(false);
    setOption5(false);
    setOption6("Both");
    setOption7("2 weeks");
  }, [
    setOption1,
    setOption2,
    setOption3,
    setOption4,
    setOption5,
    setOption6,
    setOption7,
  ]);

  const onSubmit = useCallback(() => {
    setIsSaveLoading(true);
    setTimeout(() => {
      pushMessageToSnackbar({
        text: "Your settings have been saved",
      });
      setIsSaveLoading(false);
    }, 1500);
  }, [pushMessageToSnackbar, setIsSaveLoading]);

  const onSetDefault = useCallback(() => {
    setIsDefaultLoading(true);
    setTimeout(() => {
      pushMessageToSnackbar({
        text: "Your settings have been reset to default",
      });
      resetState();
    }, 1500);
  }, [pushMessageToSnackbar, resetState, setIsDefaultLoading]);

  const handleInputChange = useCallback(
    (event) => {
      const { name, value } = event.target;
      switch (name) {
        case "option6": {
          setOption6(value);
          break;
        }
        case "option7": {
          setOption7(value);
          break;
        }
        default:
          throw new Error("No branch selected in switch statement");
      }
    },
    [setOption6, setOption7]
  );

  const handleCheckboxChange = (name) => (event) => {
    switch (name) {
      case "option1":
        setOption1(event.target.checked);
        break;
      case "option2":
        setOption2(event.target.checked);
        break;
      case "option3":
        setOption3(event.target.checked);
        break;
      case "option4":
        setOption4(event.target.checked);
        break;
      case "option5":
        setOption5(event.target.checked);
        break;
      default:
        throw new Error("No branch selected in switch statement.");
    }
  };

  const inputs = [
    {
      title: "Option 1",
      secondaryAction: (
        <Checkbox
          value="option1"
          color="primary"
          checked={option1}
          onChange={handleCheckboxChange("option1")}
        />
      ),
    },
    {
      title: "Option 2",
      secondaryAction: (
        <Checkbox
          value="option2"
          color="primary"
          checked={option2}
          onChange={handleCheckboxChange("option2")}
        />
      ),
    },
    {
      title: "Option 3",
      secondaryAction: (
        <Checkbox
          value="option3"
          color="primary"
          checked={option3}
          onChange={handleCheckboxChange("option3")}
        />
      ),
      helpText: "You can add some further explanation here.",
    },
    {
      title: "Option 4",
      secondaryAction: (
        <Checkbox
          value="option4"
          color="primary"
          checked={option4}
          onChange={handleCheckboxChange("option4")}
        />
      ),
    },
    {
      title: "Option 5",
      secondaryAction: (
        <Checkbox
          value="option5"
          color="primary"
          checked={option5}
          onChange={handleCheckboxChange("option5")}
        />
      ),
    },
    {
      title: "Option 6",
      secondaryAction: (
        <Select
          value={option6}
          input={
            <OutlinedInput
              onChange={handleInputChange}
              labelWidth={0}
              className={classes.numberInput}
              classes={{ input: classes.numberInputInput }}
              name="option6"
            />
          }
        >
          <MenuItem value="Both">Both</MenuItem>
          <MenuItem value="Male+">Male+</MenuItem>
          <MenuItem value="Female+">Female+</MenuItem>
          <MenuItem value="Only male">Only male</MenuItem>
          <MenuItem value="Only female">Only female</MenuItem>
        </Select>
      ),
      helpText: "You can add some further explanation here.",
    },
    {
      title: "Option 7",
      secondaryAction: (
        <Select
          value={option7}
          input={
            <OutlinedInput
              onChange={handleInputChange}
              labelWidth={0}
              className={classes.numberInput}
              classes={{ input: classes.numberInputInput }}
              name="option7"
            />
          }
        >
          <MenuItem value="None">None</MenuItem>
          <MenuItem value="6 hours">6 hours</MenuItem>
          <MenuItem value="12 hours">12 hours</MenuItem>
          <MenuItem value="1 day">1 day</MenuItem>
          <MenuItem value="3 days">3 days</MenuItem>
          <MenuItem value="1 week">1 week</MenuItem>
          <MenuItem value="2 weeks">2 weeks</MenuItem>
          <MenuItem value="1 month">1 month</MenuItem>
          <MenuItem value="3 months">3 months</MenuItem>
          <MenuItem value="6 months">6 months</MenuItem>
        </Select>
      ),
      helpText: "You can add some further explanation here.",
    },
  ];

  return (
    <Accordion>
      <AccordionSummary expandIcon={<ExpandMoreIcon />}>
        <Typography>Settings 2</Typography>
      </AccordionSummary>
      <AccordionDetails className={classes.dBlock}>
        <List disablePadding>
          <Bordered disableVerticalPadding disableBorderRadius>
            {inputs.map((element, index) => (
              <ListItem
                key={index}
                divider={index !== inputs.length - 1}
                className="listItemLeftPadding"
              >
                <ListItemText>
                  <Typography variant="body2">
                    {element.title}
                    {element.helpText && <HelpIcon title={element.helpText} />}
                  </Typography>
                </ListItemText>
                <ListItemSecondaryAction>
                  <FormControl variant="outlined">
                    {element.secondaryAction}
                  </FormControl>
                </ListItemSecondaryAction>
              </ListItem>
            ))}
          </Bordered>
        </List>
      </AccordionDetails>
      <AccordionDetails className={classes.AccordionDetails}>
        <Box mr={1}>
          <Button
            onClick={onSetDefault}
            disabled={isSaveLoading || isDefaultLoading}
          >
            Default {isDefaultLoading && <ButtonCircularProgress />}
          </Button>
        </Box>
        <Button
          variant="contained"
          color="secondary"
          onClick={onSubmit}
          disabled={isSaveLoading || isDefaultLoading}
        >
          Save {isSaveLoading && <ButtonCircularProgress />}
        </Button>
      </AccordionDetails>
    </Accordion>
  );
}

Settings2.propTypes = {
  classes: PropTypes.object,
  pushMessageToSnackbar: PropTypes.func,
};

export default withStyles(styles, { withTheme: true })(Settings2);



================================================
FILE: src/logged_in/components/dashboard/SettingsArea.js
================================================
import React, { Fragment } from "react";
import PropTypes from "prop-types";
import Settings1 from "./Settings1";
import Settings2 from "./Settings2";

function SettingsArea(props) {
  const { pushMessageToSnackbar } = props;
  return (
    <Fragment>
      <Settings1 pushMessageToSnackbar={pushMessageToSnackbar} />
      <Settings2 pushMessageToSnackbar={pushMessageToSnackbar} />
    </Fragment>
  );
}

SettingsArea.propTypes = {
  pushMessageToSnackbar: PropTypes.func
};

export default SettingsArea;



================================================
FILE: src/logged_in/components/dashboard/StatisticsArea.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Grid } from "@mui/material";

import withTheme from '@mui/styles/withTheme';

function StatisticsArea(props) {
  const { theme, CardChart, data } = props;
  return (
    CardChart &&
    data.profit.length >= 2 &&
    data.views.length >= 2 && (
      <Grid container spacing={3}>
        <Grid item xs={12} md={6}>
          <CardChart
            data={data.profit}
            color={theme.palette.secondary.light}
            height="70px"
            title="Profit"
          />
        </Grid>
        <Grid item xs={12} md={6}>
          <CardChart
            data={data.views}
            color={theme.palette.primary.light}
            height="70px"
            title="Views"
          />
        </Grid>
      </Grid>
    )
  );
}

StatisticsArea.propTypes = {
  theme: PropTypes.object.isRequired,
  data: PropTypes.object.isRequired,
  CardChart: PropTypes.elementType
};

export default withTheme(StatisticsArea);



================================================
FILE: src/logged_in/components/dashboard/UserDataArea.js
================================================
import React, { useState, useCallback } from "react";
import PropTypes from "prop-types";
import {
  Table,
  TableBody,
  TableCell,
  TablePagination,
  TableRow,
  IconButton,
  Avatar,
  Box,
  Accordion,
  AccordionSummary,
  Typography,
} from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import PlayCirlceOutlineIcon from "@mui/icons-material/PlayCircleOutline";
import PauseCircleOutlineIcon from "@mui/icons-material/PauseCircleOutline";
import ExpandMoreIcon from "@mui/icons-material/ExpandMore";
import DeleteIcon from "@mui/icons-material/Delete";
import EnhancedTableHead from "../../../shared/components/EnhancedTableHead";
import stableSort from "../../../shared/functions/stableSort";
import getSorting from "../../../shared/functions/getSorting";
import HighlightedInformation from "../../../shared/components/HighlightedInformation";
import ConfirmationDialog from "../../../shared/components/ConfirmationDialog";

const styles = (theme) => ({
  tableWrapper: {
    overflowX: "auto",
  },
  alignRight: {
    display: "flex",
    flexDirection: "row-reverse",
    alignItems: "center",
    paddingLeft: theme.spacing(2),
  },
  blackIcon: {
    color: theme.palette.common.black,
  },
  avatar: {
    width: 28,
    height: 28,
  },
  firstData: {
    paddingLeft: theme.spacing(3),
  },
  iconButton: {
    padding: theme.spacing(1),
  },
  dBlock: {
    display: "block",
  },
  dNone: {
    display: "none",
  },
});

const rows = [
  {
    id: "icon",
    numeric: true,
    label: "",
  },
  {
    id: "name",
    numeric: false,
    label: "Name",
  },
  { id: "number1", numeric: false, label: "Category 1" },
  { id: "number2", numeric: false, label: "Category 2" },
  { id: "number3", numeric: false, label: "Category 3" },
  {
    id: "number4",
    numeric: false,
    label: "Category 4",
  },
  {
    id: "actions",
    numeric: false,
    label: "",
  },
];

const rowsPerPage = 25;

function CustomTable(props) {
  const { pushMessageToSnackbar, classes, targets, setTargets } = props;
  const [order, setOrder] = useState("asc");
  const [orderBy, setOrderBy] = useState(null);
  const [page, setPage] = useState(0);
  const [isDeleteTargetDialogOpen, setIsDeleteTargetDialogOpen] = useState(
    false
  );
  const [deleteTargetDialogRow, setDeleteTargetDialogRow] = useState(null);
  const [isDeleteTargetLoading, setIsDeleteTargetLoading] = useState(false);

  const handleRequestSort = useCallback(
    (__, property) => {
      const _orderBy = property;
      let _order = "desc";
      if (orderBy === property && order === "desc") {
        _order = "asc";
      }
      setOrder(_order);
      setOrderBy(_orderBy);
    },
    [setOrder, setOrderBy, order, orderBy]
  );

  const deleteTarget = useCallback(() => {
    setIsDeleteTargetLoading(true);
    setTimeout(() => {
      setIsDeleteTargetDialogOpen(false);
      setIsDeleteTargetLoading(false);
      const _targets = [...targets];
      const index = _targets.findIndex(
        (element) => element.id === deleteTargetDialogRow.id
      );
      _targets.splice(index, 1);
      setTargets(_targets);
      pushMessageToSnackbar({
        text: "Your friend has been removed",
      });
    }, 1500);
  }, [
    setIsDeleteTargetDialogOpen,
    setIsDeleteTargetLoading,
    pushMessageToSnackbar,
    setTargets,
    deleteTargetDialogRow,
    targets,
  ]);

  const handleChangePage = useCallback(
    (_, page) => {
      setPage(page);
    },
    [setPage]
  );

  const handleDeleteTargetDialogClose = useCallback(() => {
    setIsDeleteTargetDialogOpen(false);
  }, [setIsDeleteTargetDialogOpen]);

  const handleDeleteTargetDialogOpen = useCallback(
    (row) => {
      setIsDeleteTargetDialogOpen(true);
      setDeleteTargetDialogRow(row);
    },
    [setIsDeleteTargetDialogOpen, setDeleteTargetDialogRow]
  );

  const toggleTarget = useCallback(
    (row) => {
      const _targets = [...targets];
      const index = _targets.findIndex((element) => element.id === row.id);
      row.isActivated = !row.isActivated;
      _targets[index] = row;
      if (row.isActivated) {
        pushMessageToSnackbar({
          text: "The row is now activated",
        });
      } else {
        pushMessageToSnackbar({
          text: "The row is now deactivated",
        });
      }
      setTargets(_targets);
    },
    [pushMessageToSnackbar, targets, setTargets]
  );

  return (
    <Accordion>
      <AccordionSummary expandIcon={<ExpandMoreIcon />}>
        <Typography>Some user data</Typography>
      </AccordionSummary>
      <ConfirmationDialog
        open={isDeleteTargetDialogOpen}
        title="Confirmation"
        content={
          deleteTargetDialogRow ? (
            <span>
              {"Do you really want to remove the friend "}
              <b>{deleteTargetDialogRow.name}</b>
              {" from your list?"}
            </span>
          ) : null
        }
        onClose={handleDeleteTargetDialogClose}
        onConfirm={deleteTarget}
        loading={isDeleteTargetLoading}
      />
      <Box width="100%">
        <div className={classes.tableWrapper}>
          {targets.length > 0 ? (
            <Table aria-labelledby="tableTitle">
              <EnhancedTableHead
                order={order}
                orderBy={orderBy}
                onRequestSort={handleRequestSort}
                rowCount={targets.length}
                rows={rows}
              />
              <TableBody>
                {stableSort(targets, getSorting(order, orderBy))
                  .slice(page * rowsPerPage, page * rowsPerPage + rowsPerPage)
                  .map((row, index) => (
                    <TableRow hover tabIndex={-1} key={index}>
                      <TableCell
                        component="th"
                        scope="row"
                        className={classes.firstData}
                      >
                        <Avatar
                          className={classes.avatar}
                          src={row.profilePicUrl}
                        />
                      </TableCell>
                      <TableCell component="th" scope="row">
                        {row.name}
                      </TableCell>
                      <TableCell component="th" scope="row">
                        {row.number1}
                      </TableCell>
                      <TableCell component="th" scope="row">
                        {row.number2}
                      </TableCell>
                      <TableCell component="th" scope="row">
                        {row.number3}
                      </TableCell>
                      <TableCell component="th" scope="row">
                        {row.number4}
                      </TableCell>
                      <TableCell component="th" scope="row">
                        <Box display="flex" justifyContent="flex-end">
                          {row.isActivated ? (
                            <IconButton
                              className={classes.iconButton}
                              onClick={() => {
                                toggleTarget(row);
                              }}
                              aria-label="Pause"
                              size="large">
                              <PauseCircleOutlineIcon
                                className={classes.blackIcon}
                              />
                            </IconButton>
                          ) : (
                            <IconButton
                              className={classes.iconButton}
                              color="primary"
                              onClick={() => {
                                toggleTarget(row);
                              }}
                              aria-label="Resume"
                              size="large">
                              <PlayCirlceOutlineIcon />
                            </IconButton>
                          )}
                          <IconButton
                            className={classes.iconButton}
                            onClick={() => {
                              handleDeleteTargetDialogOpen(row);
                            }}
                            aria-label="Delete"
                            size="large">
                            <DeleteIcon className={classes.blackIcon} />
                          </IconButton>
                        </Box>
                      </TableCell>
                    </TableRow>
                  ))}
              </TableBody>
            </Table>
          ) : (
            <Box m={2}>
              <HighlightedInformation>
                No friends added yet.
              </HighlightedInformation>
            </Box>
          )}
        </div>
        <div className={classes.alignRight}>
          <TablePagination
            component="div"
            count={targets.length}
            rowsPerPage={rowsPerPage}
            page={page}
            backIconButtonProps={{
              "aria-label": "Previous Page",
            }}
            nextIconButtonProps={{
              "aria-label": "Next Page",
            }}
            onPageChange={handleChangePage}
            classes={{
              select: classes.dNone,
              selectIcon: classes.dNone,
              actions: targets.length > 0 ? classes.dBlock : classes.dNone,
              caption: targets.length > 0 ? classes.dBlock : classes.dNone,
            }}
            labelRowsPerPage=""
          />
        </div>
      </Box>
    </Accordion>
  );
}

CustomTable.propTypes = {
  classes: PropTypes.object.isRequired,
  targets: PropTypes.arrayOf(PropTypes.object).isRequired,
  setTargets: PropTypes.func.isRequired,
  pushMessageToSnackbar: PropTypes.func,
};

export default withStyles(styles, { withTheme: true })(CustomTable);



================================================
FILE: src/logged_in/components/navigation/Balance.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { OutlinedInput } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import currencyPrettyPrint from "../../../shared/functions/currencyPrettyPrint";

const styles = {
  input: { padding: "0px 9px", cursor: "pointer" },
  outlinedInput: {
    width: 90,
    height: 40,
    cursor: "pointer"
  },
  wrapper: {
    display: "flex",
    alignItems: "center"
  }
};

function Balance(props) {
  const { balance, classes, openAddBalanceDialog } = props;
  return (
    <div className={classes.wrapper}>
      <OutlinedInput
        value={balance === null ? "" : currencyPrettyPrint(balance)}
        className={classes.outlinedInput}
        classes={{ input: classes.input }}
        readOnly
        labelWidth={0}
        onClick={openAddBalanceDialog}
      />
    </div>
  );
}

Balance.propTypes = {
  balance: PropTypes.number.isRequired,
  classes: PropTypes.object.isRequired,
  openAddBalanceDialog: PropTypes.func.isRequired
};

export default withStyles(styles)(Balance);



================================================
FILE: src/logged_in/components/navigation/MessageListItem.js
================================================
import React, { useCallback, useState } from "react";
import PropTypes from "prop-types";
import {
  ListItem,
  ListItemAvatar,
  ListItemText,
  Avatar,
} from "@mui/material";
import ErrorIcon from "@mui/icons-material/Error";
import formatDistance from "date-fns/formatDistance";

function MessageListItem(props) {
  const { message, divider } = props;
  const [hasErrorOccurred, setHasErrorOccurred] = useState(false);

  const handleError = useCallback(() => {
    setHasErrorOccurred(true);
  }, [setHasErrorOccurred]);

  return (
    <ListItem divider={divider}>
      <ListItemAvatar>
        {hasErrorOccurred ? (
          <ErrorIcon color="secondary" />
        ) : (
          <Avatar
            src={hasErrorOccurred ? null : message.src}
            onError={handleError}
          />
        )}
      </ListItemAvatar>
      <ListItemText
        primary={message.text}
        secondary={`${formatDistance(message.date * 1000, new Date())} ago`}
      />
    </ListItem>
  );
}

MessageListItem.propTypes = {
  message: PropTypes.object.isRequired,
  divider: PropTypes.bool,
};

export default MessageListItem;



================================================
FILE: src/logged_in/components/navigation/MessagePopperButton.js
================================================
import React, { Fragment, useState, useRef, useCallback } from "react";
import PropTypes from "prop-types";
import {
  Popover,
  IconButton,
  AppBar,
  List,
  Divider,
  ListItem,
  ListItemText,
  Typography,
  Box,
} from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import MessageIcon from "@mui/icons-material/Message";
import MessageListItem from "./MessageListItem";

const styles = (theme) => ({
  tabContainer: {
    overflowY: "auto",
    maxHeight: 350,
  },
  popoverPaper: {
    width: "100%",
    maxWidth: 350,
    marginLeft: theme.spacing(2),
    marginRight: theme.spacing(1),
    [theme.breakpoints.down('md')]: {
      maxWidth: 270,
    },
  },
  divider: {
    marginTop: -2,
  },
  noShadow: {
    boxShadow: "none !important",
  },
});

function MessagePopperButton(props) {
  const { classes, messages } = props;
  const anchorEl = useRef();
  const [isOpen, setIsOpen] = useState(false);

  const handleClick = useCallback(() => {
    setIsOpen(!isOpen);
  }, [isOpen, setIsOpen]);

  const handleClickAway = useCallback(() => {
    setIsOpen(false);
  }, [setIsOpen]);

  const id = isOpen ? "scroll-playground" : null;
  return (
    <Fragment>
      <IconButton
        onClick={handleClick}
        buttonRef={anchorEl}
        aria-label="Open Messages"
        aria-describedby={id}
        color="primary"
        size="large">
        <MessageIcon />
      </IconButton>
      <Popover
        disableScrollLock
        id={id}
        open={isOpen}
        anchorEl={anchorEl.current}
        anchorOrigin={{
          vertical: "bottom",
          horizontal: "left",
        }}
        transformOrigin={{
          vertical: "top",
          horizontal: "right",
        }}
        classes={{ paper: classes.popoverPaper }}
        onClose={handleClickAway}
      >
        <AppBar position="static" color="inherit" className={classes.noShadow}>
          <Box pt={1} pl={2} pb={1} pr={1}>
            <Typography variant="subtitle1">Messages</Typography>
          </Box>
          <Divider className={classes.divider} />
        </AppBar>
        <List dense className={classes.tabContainer}>
          {messages.length === 0 ? (
            <ListItem>
              <ListItemText>
                You haven&apos;t received any messages yet.
              </ListItemText>
            </ListItem>
          ) : (
            messages.map((element, index) => (
              <MessageListItem
                key={index}
                message={element}
                divider={index !== messages.length - 1}
              />
            ))
          )}
        </List>
      </Popover>
    </Fragment>
  );
}

MessagePopperButton.propTypes = {
  classes: PropTypes.object.isRequired,
  messages: PropTypes.arrayOf(PropTypes.object).isRequired,
};

export default withStyles(styles, { withTheme: true })(MessagePopperButton);



================================================
FILE: src/logged_in/components/navigation/NavBar.js
================================================
import React, { Fragment, useRef, useCallback, useState } from "react";
import { Link } from "react-router-dom";
import PropTypes from "prop-types";
import classNames from "classnames";
import {
  AppBar,
  Toolbar,
  Typography,
  Avatar,
  Drawer,
  List,
  IconButton,
  ListItem,
  ListItemIcon,
  ListItemText,
  Hidden,
  Tooltip,
  Box,
} from "@mui/material";
import withStyles from "@mui/styles/withStyles";
import DashboardIcon from "@mui/icons-material/Dashboard";
import ImageIcon from "@mui/icons-material/Image";
import AccountBalanceIcon from "@mui/icons-material/AccountBalance";
import PowerSettingsNewIcon from "@mui/icons-material/PowerSettingsNew";
import MenuIcon from "@mui/icons-material/Menu";
import SupervisorAccountIcon from "@mui/icons-material/SupervisorAccount";
import MessagePopperButton from "./MessagePopperButton";
import SideDrawer from "./SideDrawer";
import Balance from "./Balance";
import NavigationDrawer from "../../../shared/components/NavigationDrawer";
import useMediaQuery from "@mui/material/useMediaQuery";

const styles = (theme) => ({
  appBar: {
    boxShadow: theme.shadows[6],
    backgroundColor: theme.palette.common.white,
    transition: theme.transitions.create(["width", "margin"], {
      easing: theme.transitions.easing.sharp,
      duration: theme.transitions.duration.leavingScreen,
    }),
    [theme.breakpoints.down("sm")]: {
      width: "100%",
      marginLeft: 0,
    },
  },
  appBarToolbar: {
    display: "flex",
    justifyContent: "space-between",
    paddingLeft: theme.spacing(1),
    paddingRight: theme.spacing(1),
    [theme.breakpoints.up("sm")]: {
      paddingLeft: theme.spacing(2),
      paddingRight: theme.spacing(2),
    },
    [theme.breakpoints.up("md")]: {
      paddingLeft: theme.spacing(3),
      paddingRight: theme.spacing(3),
    },
    [theme.breakpoints.up("lg")]: {
      paddingLeft: theme.spacing(4),
      paddingRight: theme.spacing(4),
    },
  },
  accountAvatar: {
    backgroundColor: theme.palette.secondary.main,
    height: 24,
    width: 24,
    marginLeft: theme.spacing(2),
    marginRight: theme.spacing(2),
    [theme.breakpoints.down("sm")]: {
      marginLeft: theme.spacing(1.5),
      marginRight: theme.spacing(1.5),
    },
  },
  drawerPaper: {
    height: "100%vh",
    whiteSpace: "nowrap",
    border: 0,
    width: theme.spacing(7),
    overflowX: "hidden",
    marginTop: theme.spacing(8),
    [theme.breakpoints.up("sm")]: {
      width: theme.spacing(9),
    },
    backgroundColor: theme.palette.common.black,
  },
  smBordered: {
    [theme.breakpoints.down("sm")]: {
      borderRadius: "50% !important",
    },
  },
  menuLink: {
    textDecoration: "none",
    color: theme.palette.text.primary,
  },
  iconListItem: {
    width: "auto",
    borderRadius: theme.shape.borderRadius,
    paddingTop: 11,
    paddingBottom: 11,
    marginLeft: theme.spacing(1),
    marginRight: theme.spacing(1),
  },
  textPrimary: {
    color: theme.palette.primary.main,
  },
  mobileItemSelected: {
    backgroundColor: `${theme.palette.primary.main} !important`,
  },
  brandText: {
    fontFamily: "'Baloo Bhaijaan', cursive",
    fontWeight: 400,
  },
  username: {
    paddingLeft: 0,
    paddingRight: theme.spacing(2),
  },
  justifyCenter: {
    justifyContent: "center",
  },
  permanentDrawerListItem: {
    justifyContent: "center",
    paddingTop: theme.spacing(2),
    paddingBottom: theme.spacing(2),
  },
});

function NavBar(props) {
  const { selectedTab, messages, classes, openAddBalanceDialog, theme } = props;
  // Will be use to make website more accessible by screen readers
  const links = useRef([]);
  const [isMobileOpen, setIsMobileOpen] = useState(false);
  const [isSideDrawerOpen, setIsSideDrawerOpen] = useState(false);
  const isWidthUpSm = useMediaQuery(theme.breakpoints.up("sm"));

  const openMobileDrawer = useCallback(() => {
    setIsMobileOpen(true);
  }, [setIsMobileOpen]);

  const closeMobileDrawer = useCallback(() => {
    setIsMobileOpen(false);
  }, [setIsMobileOpen]);

  const openDrawer = useCallback(() => {
    setIsSideDrawerOpen(true);
  }, [setIsSideDrawerOpen]);

  const closeDrawer = useCallback(() => {
    setIsSideDrawerOpen(false);
  }, [setIsSideDrawerOpen]);

  const menuItems = [
    {
      link: "/c/dashboard",
      name: "Dashboard",
      onClick: closeMobileDrawer,
      icon: {
        desktop: (
          <DashboardIcon
            className={
              selectedTab === "Dashboard" ? classes.textPrimary : "text-white"
            }
            fontSize="small"
          />
        ),
        mobile: <DashboardIcon className="text-white" />,
      },
    },
    {
      link: "/c/posts",
      name: "Posts",
      onClick: closeMobileDrawer,
      icon: {
        desktop: (
          <ImageIcon
            className={
              selectedTab === "Posts" ? classes.textPrimary : "text-white"
            }
            fontSize="small"
          />
        ),
        mobile: <ImageIcon className="text-white" />,
      },
    },
    {
      link: "/c/subscription",
      name: "Subscription",
      onClick: closeMobileDrawer,
      icon: {
        desktop: (
          <AccountBalanceIcon
            className={
              selectedTab === "Subscription"
                ? classes.textPrimary
                : "text-white"
            }
            fontSize="small"
          />
        ),
        mobile: <AccountBalanceIcon className="text-white" />,
      },
    },
    {
      link: "/",
      name: "Logout",
      icon: {
        desktop: (
          <PowerSettingsNewIcon className="text-white" fontSize="small" />
        ),
        mobile: <PowerSettingsNewIcon className="text-white" />,
      },
    },
  ];
  return (
    <Fragment>
      <AppBar position="sticky" className={classes.appBar}>
        <Toolbar className={classes.appBarToolbar}>
          <Box display="flex" alignItems="center">
            <Hidden smUp>
              <Box mr={1}>
                <IconButton
                  aria-label="Open Navigation"
                  onClick={openMobileDrawer}
                  color="primary"
                  size="large"
                >
                  <MenuIcon />
                </IconButton>
              </Box>
            </Hidden>
            <Hidden smDown>
              <Typography
                variant="h4"
                className={classes.brandText}
                display="inline"
                color="primary"
              >
                Wa
              </Typography>
              <Typography
                variant="h4"
                className={classes.brandText}
                display="inline"
                color="secondary"
              >
                Ver
              </Typography>
            </Hidden>
          </Box>
          <Box
            display="flex"
            justifyContent="flex-end"
            alignItems="center"
            width="100%"
          >
            {isWidthUpSm && (
              <Box mr={3}>
                <Balance
                  balance={2573}
                  openAddBalanceDialog={openAddBalanceDialog}
                />
              </Box>
            )}
            <MessagePopperButton messages={messages} />
            <ListItem
              disableGutters
              className={classNames(classes.iconListItem, classes.smBordered)}
            >
              <Avatar
                alt="profile picture"
                src={`${process.env.PUBLIC_URL}/images/logged_in/profilePicture.jpg`}
                className={classNames(classes.accountAvatar)}
              />
              {isWidthUpSm && (
                <ListItemText
                  className={classes.username}
                  primary={
                    <Typography color="textPrimary">Username</Typography>
                  }
                />
              )}
            </ListItem>
          </Box>
          <IconButton
            onClick={openDrawer}
            color="primary"
            aria-label="Open Sidedrawer"
            size="large"
          >
            <SupervisorAccountIcon />
          </IconButton>
          <SideDrawer open={isSideDrawerOpen} onClose={closeDrawer} />
        </Toolbar>
      </AppBar>
      <Hidden smDown>
        <Drawer //  both drawers can be combined into one for performance
          variant="permanent"
          classes={{
            paper: classes.drawerPaper,
          }}
          open={false}
        >
          <List>
            {menuItems.map((element, index) => (
              <Link
                to={element.link}
                className={classes.menuLink}
                onClick={element.onClick}
                key={index}
                ref={(node) => {
                  links.current[index] = node;
                }}
              >
                <Tooltip
                  title={element.name}
                  placement="right"
                  key={element.name}
                >
                  <ListItem
                    selected={selectedTab === element.name}
                    button
                    divider={index !== menuItems.length - 1}
                    className={classes.permanentDrawerListItem}
                    onClick={() => {
                      links.current[index].click();
                    }}
                    aria-label={
                      element.name === "Logout"
                        ? "Logout"
                        : `Go to ${element.name}`
                    }
                  >
                    <ListItemIcon className={classes.justifyCenter}>
                      {element.icon.desktop}
                    </ListItemIcon>
                  </ListItem>
                </Tooltip>
              </Link>
            ))}
          </List>
        </Drawer>
      </Hidden>
      <NavigationDrawer
        menuItems={menuItems.map((element) => ({
          link: element.link,
          name: element.name,
          icon: element.icon.mobile,
          onClick: element.onClick,
        }))}
        anchor="left"
        open={isMobileOpen}
        selectedItem={selectedTab}
        onClose={closeMobileDrawer}
      />
    </Fragment>
  );
}

NavBar.propTypes = {
  messages: PropTypes.arrayOf(PropTypes.object).isRequired,
  selectedTab: PropTypes.string.isRequired,
  classes: PropTypes.object.isRequired,
  openAddBalanceDialog: PropTypes.func.isRequired,
};

export default withStyles(styles, { withTheme: true })(NavBar);



================================================
FILE: src/logged_in/components/navigation/SideDrawer.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Drawer, IconButton, Toolbar, Divider, Typography, Box } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import CloseIcon from "@mui/icons-material/Close";

const drawerWidth = 240;

const styles = {
  toolbar: {
    minWidth: drawerWidth
  }
};

function SideDrawer(props) {
  const { classes, onClose, open } = props;
  return (
    <Drawer anchor="right" open={open} variant="temporary" onClose={onClose}>
      <Toolbar disableGutters className={classes.toolbar}>
        <Box
          pl={3}
          pr={3}
          display="flex"
          justifyContent="space-between"
          width="100%"
          alignItems="center"
        >
          <Typography variant="h6">A Sidedrawer</Typography>
          <IconButton
            onClick={onClose}
            color="primary"
            aria-label="Close Sidedrawer"
            size="large">
            <CloseIcon />
          </IconButton>
        </Box>
      </Toolbar>
      <Divider />
    </Drawer>
  );
}

SideDrawer.propTypes = {
  classes: PropTypes.object.isRequired,
  open: PropTypes.bool.isRequired,
  onClose: PropTypes.func.isRequired
};

export default withStyles(styles)(SideDrawer);



================================================
FILE: src/logged_in/components/posts/AddPost.js
================================================
import React, { Fragment, useState, useCallback } from "react";
import PropTypes from "prop-types";
import { Button, Box } from "@mui/material";
import ActionPaper from "../../../shared/components/ActionPaper";
import ButtonCircularProgress from "../../../shared/components/ButtonCircularProgress";
import AddPostOptions from "./AddPostOptions";

function AddPost(props) {
  const {
    pushMessageToSnackbar,
    Dropzone,
    EmojiTextArea,
    DateTimePicker,
    ImageCropper,
    onClose,
  } = props;

  const [files, setFiles] = useState([]);
  const [uploadAt, setUploadAt] = useState(new Date());
  const [loading, setLoading] = useState(false);
  const [cropperFile, setCropperFile] = useState(null);

  const acceptDrop = useCallback(
    (file) => {
      setFiles([file]);
    },
    [setFiles]
  );

  const onDrop = useCallback(
    (acceptedFiles, rejectedFiles) => {
      if (acceptedFiles.length + rejectedFiles.length > 1) {
        pushMessageToSnackbar({
          isErrorMessage: true,
          text: "You cannot upload more than one file at once",
        });
      } else if (acceptedFiles.length === 0) {
        pushMessageToSnackbar({
          isErrorMessage: true,
          text: "The file you wanted to upload isn't an image",
        });
      } else if (acceptedFiles.length === 1) {
        const file = acceptedFiles[0];
        file.preview = URL.createObjectURL(file);
        file.key = new Date().getTime();
        setCropperFile(file);
      }
    },
    [pushMessageToSnackbar, setCropperFile]
  );

  const onCropperClose = useCallback(() => {
    setCropperFile(null);
  }, [setCropperFile]);

  const deleteItem = useCallback(() => {
    setCropperFile(null);
    setFiles([]);
  }, [setCropperFile, setFiles]);

  const onCrop = useCallback(
    (dataUrl) => {
      const file = { ...cropperFile };
      file.preview = dataUrl;
      acceptDrop(file);
      setCropperFile(null);
    },
    [acceptDrop, cropperFile, setCropperFile]
  );

  const handleUpload = useCallback(() => {
    setLoading(true);
    setTimeout(() => {
      pushMessageToSnackbar({
        text: "Your post has been uploaded",
      });
      onClose();
    }, 1500);
  }, [setLoading, onClose, pushMessageToSnackbar]);

  return (
    <Fragment>
      <ActionPaper
        helpPadding
        maxWidth="md"
        content={
          <AddPostOptions
            EmojiTextArea={EmojiTextArea}
            Dropzone={Dropzone}
            files={files}
            onDrop={onDrop}
            deleteItem={deleteItem}
            DateTimePicker={DateTimePicker}
            uploadAt={uploadAt}
            onChangeUploadAt={setUploadAt}
            onCrop={onCrop}
            ImageCropper={ImageCropper}
            cropperFile={cropperFile}
            onCropperClose={onCropperClose}
          />
        }
        actions={
          <Fragment>
            <Box mr={1}>
              <Button onClick={onClose} disabled={loading}>
                Back
              </Button>
            </Box>
            <Button
              onClick={handleUpload}
              variant="contained"
              color="secondary"
              disabled={files.length === 0 || loading}
            >
              Upload {loading && <ButtonCircularProgress />}
            </Button>
          </Fragment>
        }
      />
    </Fragment>
  );
}

AddPost.propTypes = {
  pushMessageToSnackbar: PropTypes.func,
  onClose: PropTypes.func,
  Dropzone: PropTypes.elementType,
  EmojiTextArea: PropTypes.elementType,
  DateTimePicker: PropTypes.elementType,
  ImageCropper: PropTypes.elementType,
};

export default AddPost;



================================================
FILE: src/logged_in/components/posts/AddPostOptions.js
================================================
import React, { Fragment, useState, useCallback } from "react";
import PropTypes from "prop-types";
import {
  Typography,
  IconButton,
  List,
  ListItem,
  ListItemText,
  ListItemSecondaryAction,
  FormControl,
  Select,
  OutlinedInput,
  MenuItem,
  Box,
} from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import CloseIcon from "@mui/icons-material/Close";
import Bordered from "../../../shared/components/Bordered";
import ImageCropperDialog from "../../../shared/components/ImageCropperDialog";

const styles = (theme) => ({
  floatButtonWrapper: {
    position: "absolute",
    top: theme.spacing(1),
    right: theme.spacing(1),
    zIndex: 1000,
  },
  inputRoot: {
    width: 190,
    "@media (max-width:  400px)": {
      width: 160,
    },
    "@media (max-width:  360px)": {
      width: 140,
    },
    "@media (max-width:  340px)": {
      width: 120,
    },
  },
  uploadIcon: {
    fontSize: 48,
    transition: theme.transitions.create(["color", "box-shadow", "border"], {
      duration: theme.transitions.duration.short,
      easing: theme.transitions.easing.easeInOut,
    }),
  },
  imgWrapper: { position: "relative" },
  img: {
    width: "100%",
    border: "1px solid rgba(0, 0, 0, 0.23)",
    borderRadius: theme.shape.borderRadius,
    borderTopLeftRadius: 0,
    borderBottomLeftRadius: 0,
  },
  uploadText: {
    transition: theme.transitions.create(["color", "box-shadow", "border"], {
      duration: theme.transitions.duration.short,
      easing: theme.transitions.easing.easeInOut,
    }),
  },
  numberInput: {
    width: 110,
  },
  numberInputInput: {
    padding: "9px 34px 9px 14.5px",
  },
  emojiTextArea: {
    borderTopRightRadius: 0,
    borderBottomRightRadius: 0,
    marginRight: -1,
  },
  dNone: {
    display: "none",
  },
});

const inputOptions = ["None", "Slow", "Normal", "Fast"];

function AddPostOptions(props) {
  const {
    Dropzone,
    classes,
    files,
    deleteItem,
    onDrop,
    EmojiTextArea,
    ImageCropper,
    DateTimePicker,
    cropperFile,
    onCrop,
    onCropperClose,
    uploadAt,
    onChangeUploadAt,
  } = props;
  const [option1, setOption1] = useState("None");
  const [option2, setOption2] = useState("None");
  const [option3, setOption3] = useState("None");
  const [option4, setOption4] = useState("None");

  const handleChange = useCallback(
    (event) => {
      const { name, value } = event.target;
      switch (name) {
        case "option1":
          setOption1(value);
          break;
        case "option2":
          setOption2(value);
          break;
        case "option3":
          setOption3(value);
          break;
        case "option4":
          setOption4(value);
          break;
        default:
          throw new Error("No branch selected in switch-statement.");
      }
    },
    [setOption1, setOption2, setOption3, setOption4]
  );

  const printFile = useCallback(() => {
    if (files[0]) {
      return (
        <div className={classes.imgWrapper}>
          <img
            alt="uploaded item"
            src={files[0].preview}
            className={classes.img}
            style={{ height: 148 }}
          />
          <div className={classes.floatButtonWrapper}>
            <IconButton onClick={deleteItem} size="large">
              <CloseIcon />
            </IconButton>
          </div>
        </div>
      );
    }
    return (
      <Dropzone accept="image/png, image/jpeg" onDrop={onDrop} fullHeight>
        <span className={classes.uploadText}>
          Click / Drop file <br /> here
        </span>
      </Dropzone>
    );
  }, [onDrop, files, classes, deleteItem]);

  const inputs = 
    [
      {
        state: option1,
        label: "Option 1",
        stateName: "option1",
      },
      {
        state: option2,
        label: "Option 2",
        stateName: "option2",
      },
      {
        state: option3,
        label: "Option 3",
        stateName: "option3",
      },
      {
        state: option4,
        label: "Option 4",
        stateName: "option4",
      },
    ];

  return (
    <Fragment>
      {ImageCropper && (
        <ImageCropperDialog
          open={cropperFile ? true : false}
          ImageCropper={ImageCropper}
          src={cropperFile ? cropperFile.preview : ""}
          onCrop={onCrop}
          onClose={onCropperClose}
          aspectRatio={4 / 3}
        />
      )}
      <Typography paragraph variant="h6">
        Upload Image
      </Typography>
      <Box mb={2}>
        {EmojiTextArea && (
          <EmojiTextArea
            inputClassName={classes.emojiTextArea}
            maxCharacters={2200}
            rightContent={printFile()}
            emojiSet="google"
          />
        )}
      </Box>
      <Typography paragraph variant="h6">
        Options
      </Typography>
      <List disablePadding>
        <Bordered disableVerticalPadding disableBorderRadius>
          <ListItem divider disableGutters className="listItemLeftPadding">
            <ListItemText>
              <Typography variant="body2">Upload at</Typography>
            </ListItemText>
            <ListItemSecondaryAction>
              {DateTimePicker && (
                <DateTimePicker
                  value={uploadAt}
                  format="yyyy/MM/dd hh:mm a"
                  onChange={onChangeUploadAt}
                  disablePast
                />
              )}
            </ListItemSecondaryAction>
          </ListItem>
          {inputs.map((element, index) => (
            <ListItem
              className="listItemLeftPadding"
              disableGutters
              divider={index !== inputs.length - 1}
              key={index}
            >
              <ListItemText>
                <Typography variant="body2">{element.label}</Typography>
              </ListItemText>
              <FormControl variant="outlined">
                <ListItemSecondaryAction>
                  <Select
                    value={element.state}
                    onChange={handleChange}
                    input={
                      <OutlinedInput
                        name={element.stateName}
                        labelWidth={0}
                        className={classes.numberInput}
                        classes={{ input: classes.numberInputInput }}
                      />
                    }
                    MenuProps={{ disableScrollLock: true }}
                  >
                    {inputOptions.map((innerElement) => (
                      <MenuItem value={innerElement} key={innerElement}>
                        {innerElement}
                      </MenuItem>
                    ))}
                  </Select>
                </ListItemSecondaryAction>
              </FormControl>
            </ListItem>
          ))}
        </Bordered>
      </List>
    </Fragment>
  );
}

AddPostOptions.propTypes = {
  onEmojiTextareaChange: PropTypes.func,
  DateTimePicker: PropTypes.elementType,
  EmojiTextArea: PropTypes.elementType,
  Dropzone: PropTypes.elementType,
  ImageCropper: PropTypes.elementType,
  classes: PropTypes.object,
  cropperFile: PropTypes.object,
  onCrop: PropTypes.func,
  onCropperClose: PropTypes.func,
  files: PropTypes.arrayOf(PropTypes.object).isRequired,
  deleteItem: PropTypes.func,
  onDrop: PropTypes.func,
  value: PropTypes.string,
  characters: PropTypes.number,
  uploadAt: PropTypes.instanceOf(Date),
  onChangeUploadAt: PropTypes.func,
};

export default withStyles(styles, { withTheme: true })(AddPostOptions);



================================================
FILE: src/logged_in/components/posts/PostContent.js
================================================
import React, { useState, useCallback } from "react";
import PropTypes from "prop-types";
import { Grid, TablePagination, Divider, Toolbar, Typography, Button, Paper, Box } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import DeleteIcon from "@mui/icons-material/Delete";
import SelfAligningImage from "../../../shared/components/SelfAligningImage";
import HighlightedInformation from "../../../shared/components/HighlightedInformation";
import ConfirmationDialog from "../../../shared/components/ConfirmationDialog";

const styles = {
  dBlock: { display: "block" },
  dNone: { display: "none" },
  toolbar: {
    justifyContent: "space-between",
  },
};

const rowsPerPage = 25;

function PostContent(props) {
  const {
    pushMessageToSnackbar,
    setPosts,
    posts,
    openAddPostModal,
    classes,
  } = props;
  const [page, setPage] = useState(0);
  const [isDeletePostDialogOpen, setIsDeletePostDialogOpen] = useState(false);
  const [isDeletePostDialogLoading, setIsDeletePostDialogLoading] = useState(
    false
  );

  const closeDeletePostDialog = useCallback(() => {
    setIsDeletePostDialogOpen(false);
    setIsDeletePostDialogLoading(false);
  }, [setIsDeletePostDialogOpen, setIsDeletePostDialogLoading]);

  const deletePost = useCallback(() => {
    setIsDeletePostDialogLoading(true);
    setTimeout(() => {
      const _posts = [...posts];
      const index = _posts.find((element) => element.id === deletePost.id);
      _posts.splice(index, 1);
      setPosts(_posts);
      pushMessageToSnackbar({
        text: "Your post has been deleted",
      });
      closeDeletePostDialog();
    }, 1500);
  }, [
    posts,
    setPosts,
    setIsDeletePostDialogLoading,
    pushMessageToSnackbar,
    closeDeletePostDialog,
  ]);

  const onDelete = useCallback(() => {
    setIsDeletePostDialogOpen(true);
  }, [setIsDeletePostDialogOpen]);

  const handleChangePage = useCallback(
    (__, page) => {
      setPage(page);
    },
    [setPage]
  );

  const printImageGrid = useCallback(() => {
    if (posts.length > 0) {
      return (
        <Box p={1}>
          <Grid container spacing={1}>
            {posts
              .slice(page * rowsPerPage, page * rowsPerPage + rowsPerPage)
              .map((post) => (
                <Grid item xs={6} sm={4} md={3} key={post.id}>
                  <SelfAligningImage
                    src={post.src}
                    title={post.name}
                    timeStamp={post.timestamp}
                    options={[
                      {
                        name: "Delete",
                        onClick: () => {
                          onDelete(post);
                        },
                        icon: <DeleteIcon />,
                      },
                    ]}
                  />
                </Grid>
              ))}
          </Grid>
        </Box>
      );
    }
    return (
      <Box m={2}>
        <HighlightedInformation>
          No posts added yet. Click on &quot;NEW&quot; to create your first one.
        </HighlightedInformation>
      </Box>
    );
  }, [posts, onDelete, page]);

  return (
    <Paper>
      <Toolbar className={classes.toolbar}>
        <Typography variant="h6">Your Posts</Typography>
        <Button
          variant="contained"
          color="secondary"
          onClick={openAddPostModal}
          disableElevation
        >
          Add Post
        </Button>
      </Toolbar>
      <Divider />
      {printImageGrid()}
      <TablePagination
        component="div"
        count={posts.length}
        rowsPerPage={rowsPerPage}
        page={page}
        backIconButtonProps={{
          "aria-label": "Previous Page",
        }}
        nextIconButtonProps={{
          "aria-label": "Next Page",
        }}
        onPageChange={handleChangePage}
        classes={{
          select: classes.dNone,
          selectIcon: classes.dNone,
          actions: posts.length > 0 ? classes.dBlock : classes.dNone,
          caption: posts.length > 0 ? classes.dBlock : classes.dNone,
        }}
        labelRowsPerPage=""
      />
      <ConfirmationDialog
        open={isDeletePostDialogOpen}
        title="Confirmation"
        content="Do you really want to delete the post?"
        onClose={closeDeletePostDialog}
        loading={isDeletePostDialogLoading}
        onConfirm={deletePost}
      />
    </Paper>
  );
}

PostContent.propTypes = {
  openAddPostModal: PropTypes.func.isRequired,
  classes: PropTypes.object.isRequired,
  posts: PropTypes.arrayOf(PropTypes.object).isRequired,
  setPosts: PropTypes.func.isRequired,
  pushMessageToSnackbar: PropTypes.func,
};

export default withStyles(styles)(PostContent);



================================================
FILE: src/logged_in/components/posts/Posts.js
================================================
import React, { useState, useCallback, useEffect } from "react";
import PropTypes from "prop-types";
import PostContent from "./PostContent";
import AddPost from "./AddPost";

function Posts(props) {
  const {
    selectPosts,
    EmojiTextArea,
    ImageCropper,
    Dropzone,
    DateTimePicker,
    pushMessageToSnackbar,
    posts,
    setPosts,
  } = props;
  const [isAddPostPaperOpen, setIsAddPostPaperOpen] = useState(false);

  const openAddPostModal = useCallback(() => {
    setIsAddPostPaperOpen(true);
  }, [setIsAddPostPaperOpen]);

  const closeAddPostModal = useCallback(() => {
    setIsAddPostPaperOpen(false);
  }, [setIsAddPostPaperOpen]);

  useEffect(() => {
    selectPosts();
  }, [selectPosts]);

  if (isAddPostPaperOpen) {
    return <AddPost
      onClose={closeAddPostModal}
      EmojiTextArea={EmojiTextArea}
      ImageCropper={ImageCropper}
      Dropzone={Dropzone}
      DateTimePicker={DateTimePicker}
      pushMessageToSnackbar={pushMessageToSnackbar}
    />
  }
  return <PostContent
    openAddPostModal={openAddPostModal}
    posts={posts}
    setPosts={setPosts}
    pushMessageToSnackbar={pushMessageToSnackbar}
  />
}

Posts.propTypes = {
  EmojiTextArea: PropTypes.elementType,
  ImageCropper: PropTypes.elementType,
  Dropzone: PropTypes.elementType,
  DateTimePicker: PropTypes.elementType,
  posts: PropTypes.arrayOf(PropTypes.object).isRequired,
  setPosts: PropTypes.func.isRequired,
  pushMessageToSnackbar: PropTypes.func,
  selectPosts: PropTypes.func.isRequired,
};

export default Posts;



================================================
FILE: src/logged_in/components/subscription/AddBalanceDialog.js
================================================
import React, { useState, Fragment } from "react";
import PropTypes from "prop-types";
import { loadStripe } from "@stripe/stripe-js";
import {
  Elements,
  CardElement,
  IbanElement,
  useStripe,
  useElements
} from "@stripe/react-stripe-js";
import { Grid, Button, Box } from "@mui/material";
import withTheme from '@mui/styles/withTheme';
import StripeCardForm from "./stripe/StripeCardForm";
import StripeIbanForm from "./stripe/StripeIBANForm";
import FormDialog from "../../../shared/components/FormDialog";
import ColoredButton from "../../../shared/components/ColoredButton";
import HighlightedInformation from "../../../shared/components/HighlightedInformation";
import ButtonCircularProgress from "../../../shared/components/ButtonCircularProgress";

const stripePromise = loadStripe("pk_test_6pRNASCoBOKtIshFeQd4XMUh");

const paymentOptions = ["Credit Card", "SEPA Direct Debit"];

const AddBalanceDialog = withTheme(function (props) {
  const { open, theme, onClose, onSuccess } = props;

  const [loading, setLoading] = useState(false);
  const [paymentOption, setPaymentOption] = useState("Credit Card");
  const [stripeError, setStripeError] = useState("");
  const [name, setName] = useState("");
  const [email, setEmail] = useState("");
  const [amount, setAmount] = useState(0);
  const [amountError, setAmountError] = useState("");
  const elements = useElements();
  const stripe = useStripe();

  const onAmountChange = amount => {
    if (amount < 0) {
      return;
    }
    if (amountError) {
      setAmountError("");
    }
    setAmount(amount);
  };

  const getStripePaymentInfo = () => {
    switch (paymentOption) {
      case "Credit Card": {
        return {
          type: "card",
          card: elements.getElement(CardElement),
          billing_details: { name: name }
        };
      }
      case "SEPA Direct Debit": {
        return {
          type: "sepa_debit",
          sepa_debit: elements.getElement(IbanElement),
          billing_details: { email: email, name: name }
        };
      }
      default:
        throw new Error("No case selected in switch statement");
    }
  };

  const renderPaymentComponent = () => {
    switch (paymentOption) {
      case "Credit Card":
        return (
          <Fragment>
            <Box mb={2}>
              <StripeCardForm
                stripeError={stripeError}
                setStripeError={setStripeError}
                setName={setName}
                name={name}
                amount={amount}
                amountError={amountError}
                onAmountChange={onAmountChange}
              />
            </Box>
            <HighlightedInformation>
              You can check this integration using the credit card number{" "}
              <b>4242 4242 4242 4242 04 / 24 24 242 42424</b>
            </HighlightedInformation>
          </Fragment>
        );
      case "SEPA Direct Debit":
        return (
          <Fragment>
            <Box mb={2}>
              <StripeIbanForm
                stripeError={stripeError}
                setStripeError={setStripeError}
                setName={setName}
                setEmail={setEmail}
                name={name}
                email={email}
                amount={amount}
                amountError={amountError}
                onAmountChange={onAmountChange}
              />
            </Box>
            <HighlightedInformation>
              You can check this integration using the IBAN
              <br />
              <b>DE89370400440532013000</b>
            </HighlightedInformation>
          </Fragment>
        );
      default:
        throw new Error("No case selected in switch statement");
    }
  };

  return (
    <FormDialog
      open={open}
      onClose={onClose}
      headline="Add Balance"
      hideBackdrop={false}
      loading={loading}
      onFormSubmit={async event => {
        event.preventDefault();
        if (amount <= 0) {
          setAmountError("Can't be zero");
          return;
        }
        if (stripeError) {
          setStripeError("");
        }
        setLoading(true);
        const { error } = await stripe.createPaymentMethod(
          getStripePaymentInfo()
        );
        if (error) {
          setStripeError(error.message);
          setLoading(false);
          return;
        }
        onSuccess();
      }}
      content={
        <Box pb={2}>
          <Box mb={2}>
            <Grid container spacing={1}>
              {paymentOptions.map(option => (
                <Grid item key={option}>
                  <ColoredButton
                    variant={
                      option === paymentOption ? "contained" : "outlined"
                    }
                    disableElevation
                    onClick={() => {
                      setStripeError("");
                      setPaymentOption(option);
                    }}
                    color={theme.palette.common.black}
                  >
                    {option}
                  </ColoredButton>
                </Grid>
              ))}
            </Grid>
          </Box>
          {renderPaymentComponent()}
        </Box>
      }
      actions={
        <Fragment>
          <Button
            fullWidth
            variant="contained"
            color="secondary"
            type="submit"
            size="large"
            disabled={loading}
          >
            Pay with Stripe {loading && <ButtonCircularProgress />}
          </Button>
        </Fragment>
      }
    />
  );
});

AddBalanceDialog.propTypes = {
  open: PropTypes.bool.isRequired,
  theme: PropTypes.object.isRequired,
  onClose: PropTypes.func.isRequired,
  onSuccess: PropTypes.func.isRequired
};

function Wrapper(props) {
  const { open, onClose, onSuccess } = props;
  return (
    <Elements stripe={stripePromise}>
      {open && (
        <AddBalanceDialog open={open} onClose={onClose} onSuccess={onSuccess} />
      )}
    </Elements>
  );
}


Wrapper.propTypes = {
  open: PropTypes.bool.isRequired,
  onClose: PropTypes.func.isRequired,
  onSuccess: PropTypes.func.isRequired
};

export default Wrapper;



================================================
FILE: src/logged_in/components/subscription/LazyLoadAddBalanceDialog.js
================================================
import React, { useState, useEffect, Fragment } from "react";
import PropTypes from "prop-types";

function LazyLoadAddBalanceDialog(props) {
  const { open, onClose, onSuccess } = props;
  const [AddBalanceDialog, setAddBalanceDialog] = useState(null);
  const [hasFetchedAddBalanceDialog, setHasFetchedAddBlanceDialog] = useState(false);

  useEffect(() => {
    if (open && !hasFetchedAddBalanceDialog) {
      setHasFetchedAddBlanceDialog(true);
      import("./AddBalanceDialog").then(Component => {
        setAddBalanceDialog(() => Component.default);
      });
    }
  }, [open, hasFetchedAddBalanceDialog, setHasFetchedAddBlanceDialog, setAddBalanceDialog]);

  return (
    <Fragment>
      {AddBalanceDialog && (
        <AddBalanceDialog
          open={open}
          onClose={onClose}
          onSuccess={onSuccess}
        ></AddBalanceDialog>
      )}
    </Fragment>
  );

}

LazyLoadAddBalanceDialog.propTypes = {
  open: PropTypes.bool.isRequired,
  onClose: PropTypes.func.isRequired,
  onSuccess: PropTypes.func.isRequired
};

export default LazyLoadAddBalanceDialog;



================================================
FILE: src/logged_in/components/subscription/Subscription.js
================================================
import React, { useEffect } from "react";
import PropTypes from "prop-types";
import { List, Divider, Paper } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import SubscriptionTable from "./SubscriptionTable";
import SubscriptionInfo from "./SubscriptionInfo";

const styles = {
  divider: {
    backgroundColor: "rgba(0, 0, 0, 0.26)"
  }
};

function Subscription(props) {
  const {
    transactions,
    classes,
    openAddBalanceDialog,
    selectSubscription
  } = props;

  useEffect(selectSubscription, [selectSubscription]);

  return (
    <Paper>
      <List disablePadding>
        <SubscriptionInfo openAddBalanceDialog={openAddBalanceDialog} />
        <Divider className={classes.divider} />
        <SubscriptionTable transactions={transactions} />
      </List>
    </Paper>
  );
}

Subscription.propTypes = {
  classes: PropTypes.object.isRequired,
  transactions: PropTypes.arrayOf(PropTypes.object).isRequired,
  selectSubscription: PropTypes.func.isRequired,
  openAddBalanceDialog: PropTypes.func.isRequired
};

export default withStyles(styles)(Subscription);



================================================
FILE: src/logged_in/components/subscription/SubscriptionInfo.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { ListItemText, Button, Toolbar } from "@mui/material";

import withStyles from '@mui/styles/withStyles';

const styles = {
  toolbar: {
    justifyContent: "space-between"
  }
};

function SubscriptionInfo(props) {
  const { classes, openAddBalanceDialog } = props;
  return (
    <Toolbar className={classes.toolbar}>
      <ListItemText primary="Status" secondary="Premium Account" />
      <Button
        variant="contained"
        color="secondary"
        onClick={openAddBalanceDialog}
        disableElevation
      >
        Add Balance
      </Button>
    </Toolbar>
  );
}

SubscriptionInfo.propTypes = {
  classes: PropTypes.object.isRequired,
  openAddBalanceDialog: PropTypes.func.isRequired
};

export default withStyles(styles)(SubscriptionInfo);



================================================
FILE: src/logged_in/components/subscription/SubscriptionTable.js
================================================
import React, { useCallback, useState } from "react";
import PropTypes from "prop-types";
import { Table, TableBody, TableCell, TablePagination, TableRow } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import EnhancedTableHead from "../../../shared/components/EnhancedTableHead";
import ColorfulChip from "../../../shared/components/ColorfulChip";
import unixToDateString from "../../../shared/functions/unixToDateString";
import HighlightedInformation from "../../../shared/components/HighlightedInformation";
import currencyPrettyPrint from "../../../shared/functions/currencyPrettyPrint";

const styles = theme => ({
  tableWrapper: {
    overflowX: "auto",
    width: "100%"
  },
  blackBackground: {
    backgroundColor: theme.palette.primary.main
  },
  contentWrapper: {
    padding: theme.spacing(3),
    [theme.breakpoints.down('sm')]: {
      padding: theme.spacing(2)
    },
    width: "100%"
  },
  dBlock: {
    display: "block !important"
  },
  dNone: {
    display: "none !important"
  },
  firstData: {
    paddingLeft: theme.spacing(3)
  }
});

const rows = [
  {
    id: "description",
    numeric: false,
    label: "Action"
  },
  {
    id: "balanceChange",
    numeric: false,
    label: "Balance change"
  },
  {
    id: "date",
    numeric: false,
    label: "Date"
  },
  {
    id: "paidUntil",
    numeric: false,
    label: "Paid until"
  }
];

const rowsPerPage = 25;

function SubscriptionTable(props) {
  const { transactions, theme, classes } = props;
  const [page, setPage] = useState(0);

  const handleChangePage = useCallback(
    (_, page) => {
      setPage(page);
    },
    [setPage]
  );

  if (transactions.length > 0) {
    return (
      <div className={classes.tableWrapper}>
        <Table aria-labelledby="tableTitle">
          <EnhancedTableHead rowCount={transactions.length} rows={rows} />
          <TableBody>
            {transactions
              .slice(page * rowsPerPage, page * rowsPerPage + rowsPerPage)
              .map((transaction, index) => (
                <TableRow hover tabIndex={-1} key={index}>
                  <TableCell
                    component="th"
                    scope="row"
                    className={classes.firstData}
                  >
                    {transaction.description}
                  </TableCell>
                  <TableCell component="th" scope="row">
                    {transaction.balanceChange > 0 ? (
                      <ColorfulChip
                        label={`+${currencyPrettyPrint(
                          transaction.balanceChange
                        )}`}
                        color={theme.palette.secondary.main}
                      />
                    ) : (
                      <ColorfulChip
                        label={currencyPrettyPrint(transaction.balanceChange)}
                        color={theme.palette.error.dark}
                      />
                    )}
                  </TableCell>
                  <TableCell component="th" scope="row">
                    {unixToDateString(transaction.timestamp)}
                  </TableCell>
                  <TableCell component="th" scope="row">
                    {transaction.paidUntil
                      ? unixToDateString(transaction.paidUntil)
                      : ""}
                  </TableCell>
                </TableRow>
              ))}
          </TableBody>
        </Table>
        <TablePagination
          component="div"
          count={transactions.length}
          rowsPerPage={rowsPerPage}
          page={page}
          backIconButtonProps={{
            "aria-label": "Previous Page"
          }}
          nextIconButtonProps={{
            "aria-label": "Next Page"
          }}
          onPageChange={handleChangePage}
          classes={{
            select: classes.dNone,
            selectIcon: classes.dNone,
            actions: transactions.length > 0 ? classes.dBlock : classes.dNone,
            caption: transactions.length > 0 ? classes.dBlock : classes.dNone
          }}
          labelRowsPerPage=""
        />
      </div>
    );
  }
  return (
    <div className={classes.contentWrapper}>
      <HighlightedInformation>
        No transactions received yet.
      </HighlightedInformation>
    </div>
  );
}

SubscriptionTable.propTypes = {
  theme: PropTypes.object.isRequired,
  classes: PropTypes.object.isRequired,
  transactions: PropTypes.arrayOf(PropTypes.object).isRequired
};

export default withStyles(styles, { withTheme: true })(SubscriptionTable);



================================================
FILE: src/logged_in/components/subscription/stripe/StripeCardForm.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { TextField, Grid, InputAdornment } from "@mui/material";
import { CardElement } from "@stripe/react-stripe-js";
import StripeTextField from "./StripeTextField";

function StripeCardForm(props) {
  const {
    stripeError,
    setStripeError,
    amount,
    amountError,
    onAmountChange,
    name,
    setName
  } = props;
  return (
    <Grid container spacing={2} justifyContent="space-between">
      <Grid item xs={8}>
        <TextField
          variant="outlined"
          margin="none"
          required
          label="Your Name"
          value={name}
          onChange={event => {
            setName(event.target.value);
          }}
          fullWidth
          autoFocus
          autoComplete="off"
          type="text"
        />
      </Grid>
      <Grid item xs={4}>
        <TextField
          required
          value={amount}
          onChange={event => {
            onAmountChange(parseInt(event.target.value));
          }}
          error={amountError ? true : false}
          helperText={amountError}
          variant="outlined"
          fullWidth
          type="number"
          margin="none"
          label="Amount"
          InputProps={{
            startAdornment: <InputAdornment position="start">$</InputAdornment>
          }}
        />
      </Grid>
      <Grid item xs={12}>
        <StripeTextField
          margin="none"
          fullWidth
          label="Credit Card"
          error={stripeError ? true : false}
          helperText={stripeError}
          variant="outlined"
          required
          StripeElement={CardElement}
          onChange={() => {
            if (stripeError) {
              setStripeError("");
            }
          }}
        ></StripeTextField>
      </Grid>
    </Grid>
  );
}

StripeCardForm.propTypes = {
  stripeError: PropTypes.string.isRequired,
  setStripeError: PropTypes.func.isRequired,
  amount: PropTypes.number.isRequired,
  onAmountChange: PropTypes.func.isRequired,
  amountError: PropTypes.string.isRequired,
  name: PropTypes.string.isRequired,
  setName: PropTypes.func.isRequired
};

export default StripeCardForm;



================================================
FILE: src/logged_in/components/subscription/stripe/StripeIBANForm.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { TextField, Grid, InputAdornment } from "@mui/material";
import StripeTextField from "./StripeTextField";
import { IbanElement } from "@stripe/react-stripe-js";

function StripeIBANForm(props) {
  const {
    stripeError,
    setStripeError,
    amount,
    amountError,
    onAmountChange,
    name,
    setName,
    email,
    setEmail
  } = props;
  return (
    <Grid container spacing={2} justifyContent="space-between">
      <Grid item xs={8}>
        <TextField
          variant="outlined"
          margin="none"
          required
          label="Your Name"
          value={name}
          onChange={event => {
            setName(event.target.value);
          }}
          fullWidth
          autoFocus
          autoComplete="off"
          type="text"
        />
      </Grid>
      <Grid item xs={4}>
        <TextField
          required
          value={amount}
          onChange={event => {
            onAmountChange(parseInt(event.target.value));
          }}
          error={amountError ? true : false}
          helperText={amountError}
          variant="outlined"
          fullWidth
          type="number"
          margin="none"
          label="Amount"
          InputProps={{
            startAdornment: <InputAdornment position="start">$</InputAdornment>
          }}
        />
      </Grid>
      <Grid item xs={12}>
        <TextField
          required
          variant="outlined"
          fullWidth
          value={email}
          onChange={event => {
            setEmail(event.target.value);
          }}
          type="email"
          margin="none"
          label="Email"
        />
      </Grid>
      <Grid item xs={12}>
        <StripeTextField
          margin="none"
          variant="outlined"
          fullWidth
          label="IBAN"
          error={stripeError ? true : false}
          helperText={stripeError}
          required
          StripeElement={IbanElement}
          stripeOptions={{ supportedCountries: ["SEPA"] }}
          onChange={() => {
            if (stripeError) {
              setStripeError("");
            }
          }}
        ></StripeTextField>
      </Grid>
    </Grid>
  );
}

StripeIBANForm.propTypes = {
  stripeError: PropTypes.string.isRequired,
  setStripeError: PropTypes.func.isRequired,
  amount: PropTypes.number.isRequired,
  onAmountChange: PropTypes.func.isRequired,
  amountError: PropTypes.string.isRequired,
  name: PropTypes.string.isRequired,
  setName: PropTypes.func.isRequired,
  email: PropTypes.string.isRequired,
  setEmail: PropTypes.func.isRequired
};

export default StripeIBANForm;



================================================
FILE: src/logged_in/components/subscription/stripe/StripeTextField.js
================================================
import React from "react";
import { TextField } from "@mui/material";
import withTheme from "@mui/styles/withTheme";

function StripeTextField(props) {
  const { stripeOptions, StripeElement, select, theme, ...rest } = props;
  const options = {
    style: {
      base: {
        ...theme.typography.body1,
        color: theme.palette.text.primary,
        fontSize: "16px",
        fontSmoothing: "antialiased",
        "::placeholder": {
          color: theme.palette.text.secondary,
        },
      },
      invalid: {
        iconColor: theme.palette.error.main,
        color: theme.palette.error.main,
      },
    },
    ...stripeOptions,
  };
  return (
    <TextField
      InputLabelProps={{
        shrink: true,
      }}
      inputProps={{ component: StripeElement, options: options }}
      {...rest}
    />
  );
}

export default withTheme(StripeTextField);



================================================
FILE: src/logged_in/dummy_data/persons.js
================================================
const data = [
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image1.jpg`,
    name: "Markus",
  },
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image2.jpg`,
    name: "David",
  },
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image3.jpg`,
    name: "Arold",
  },
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image4.jpg`,
    name: "Joanic",
  },
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image5.jpg`,
    name: "Sophia",
  },
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image6.jpg`,
    name: "Aaron",
  },
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image7.jpg`,
    name: "Steven",
  },
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image8.jpg`,
    name: "Felix",
  },
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image9.jpg`,
    name: "Vivien",
  },
  {
    src: `${process.env.PUBLIC_URL}/images/logged_in/image10.jpg`,
    name: "Leonie",
  },
];

export default data;


================================================
FILE: src/logged_out/components/Main.js
================================================
import React, { memo, useState, useEffect, useCallback } from "react";
import PropTypes from "prop-types";
import AOS from "aos/dist/aos";
import withStyles from '@mui/styles/withStyles';
import NavBar from "./navigation/NavBar";
import Footer from "./footer/Footer";
import "aos/dist/aos.css";
import CookieRulesDialog from "./cookies/CookieRulesDialog";
import CookieConsent from "./cookies/CookieConsent";
import dummyBlogPosts from "../dummy_data/blogPosts";
import DialogSelector from "./register_login/DialogSelector";
import Routing from "./Routing";
import smoothScrollTop from "../../shared/functions/smoothScrollTop";

AOS.init({ once: true });

const styles = (theme) => ({
  wrapper: {
    backgroundColor: theme.palette.common.white,
    overflowX: "hidden",
  },
});

function Main(props) {
  const { classes } = props;
  const [selectedTab, setSelectedTab] = useState(null);
  const [isMobileDrawerOpen, setIsMobileDrawerOpen] = useState(false);
  const [blogPosts, setBlogPosts] = useState([]);
  const [dialogOpen, setDialogOpen] = useState(null);
  const [isCookieRulesDialogOpen, setIsCookieRulesDialogOpen] = useState(false);

  const selectHome = useCallback(() => {
    smoothScrollTop();
    document.title =
      "WaVer - Free template for building a SaaS or admin application";
    setSelectedTab("Home");
  }, [setSelectedTab]);

  const selectBlog = useCallback(() => {
    smoothScrollTop();
    document.title = "WaVer - Blog";
    setSelectedTab("Blog");
  }, [setSelectedTab]);

  const openLoginDialog = useCallback(() => {
    setDialogOpen("login");
    setIsMobileDrawerOpen(false);
  }, [setDialogOpen, setIsMobileDrawerOpen]);

  const closeDialog = useCallback(() => {
    setDialogOpen(null);
  }, [setDialogOpen]);

  const openRegisterDialog = useCallback(() => {
    setDialogOpen("register");
    setIsMobileDrawerOpen(false);
  }, [setDialogOpen, setIsMobileDrawerOpen]);

  const openTermsDialog = useCallback(() => {
    setDialogOpen("termsOfService");
  }, [setDialogOpen]);

  const handleMobileDrawerOpen = useCallback(() => {
    setIsMobileDrawerOpen(true);
  }, [setIsMobileDrawerOpen]);

  const handleMobileDrawerClose = useCallback(() => {
    setIsMobileDrawerOpen(false);
  }, [setIsMobileDrawerOpen]);

  const openChangePasswordDialog = useCallback(() => {
    setDialogOpen("changePassword");
  }, [setDialogOpen]);

  const fetchBlogPosts = useCallback(() => {
    const blogPosts = dummyBlogPosts.map((blogPost) => {
      let title = blogPost.title;
      title = title.toLowerCase();
      /* Remove unwanted characters, only accept alphanumeric and space */
      title = title.replace(/[^A-Za-z0-9 ]/g, "");
      /* Replace multi spaces with a single space */
      title = title.replace(/\s{2,}/g, " ");
      /* Replace space with a '-' symbol */
      title = title.replace(/\s/g, "-");
      blogPost.url = `/blog/post/${title}`;
      blogPost.params = `?id=${blogPost.id}`;
      return blogPost;
    });
    setBlogPosts(blogPosts);
  }, [setBlogPosts]);

  const handleCookieRulesDialogOpen = useCallback(() => {
    setIsCookieRulesDialogOpen(true);
  }, [setIsCookieRulesDialogOpen]);

  const handleCookieRulesDialogClose = useCallback(() => {
    setIsCookieRulesDialogOpen(false);
  }, [setIsCookieRulesDialogOpen]);

  useEffect(fetchBlogPosts, [fetchBlogPosts]);

  return (
    <div className={classes.wrapper}>
      {!isCookieRulesDialogOpen && (
        <CookieConsent
          handleCookieRulesDialogOpen={handleCookieRulesDialogOpen}
        />
      )}
      <DialogSelector
        openLoginDialog={openLoginDialog}
        dialogOpen={dialogOpen}
        onClose={closeDialog}
        openTermsDialog={openTermsDialog}
        openRegisterDialog={openRegisterDialog}
        openChangePasswordDialog={openChangePasswordDialog}
      />
      <CookieRulesDialog
        open={isCookieRulesDialogOpen}
        onClose={handleCookieRulesDialogClose}
      />
      <NavBar
        selectedTab={selectedTab}
        selectTab={setSelectedTab}
        openLoginDialog={openLoginDialog}
        openRegisterDialog={openRegisterDialog}
        mobileDrawerOpen={isMobileDrawerOpen}
        handleMobileDrawerOpen={handleMobileDrawerOpen}
        handleMobileDrawerClose={handleMobileDrawerClose}
      />
      <Routing
        blogPosts={blogPosts}
        selectHome={selectHome}
        selectBlog={selectBlog}
      />
      <Footer />
    </div>
  );
}

Main.propTypes = {
  classes: PropTypes.object.isRequired,
};

export default withStyles(styles, { withTheme: true })(memo(Main));



================================================
FILE: src/logged_out/components/Routing.js
================================================
import React, { memo } from "react";
import PropTypes from "prop-types";
import { Switch } from "react-router-dom";
import PropsRoute from "../../shared/components/PropsRoute";
import Home from "./home/Home";
import Blog from "./blog/Blog";
import BlogPost from "./blog/BlogPost";
import useLocationBlocker from "../../shared/functions/useLocationBlocker";

function Routing(props) {
  const { blogPosts, selectBlog, selectHome } = props;
  useLocationBlocker();
  return (
    <Switch>
      {blogPosts.map((post) => (
        <PropsRoute
          path={post.url}
          component={BlogPost}
          title={post.title}
          key={post.title}
          src={post.src}
          date={post.date}
          content={post.content}
          otherArticles={blogPosts.filter(
            (blogPost) => blogPost.id !== post.id
          )}
        />
      ))}
      <PropsRoute
        exact
        path="/blog"
        component={Blog}
        selectBlog={selectBlog}
        blogPosts={blogPosts}
      />
      <PropsRoute path="/" component={Home} selectHome={selectHome} />
    </Switch>
  );
}

Routing.propTypes = {
  blogposts: PropTypes.arrayOf(PropTypes.object),
  selectHome: PropTypes.func.isRequired,
  selectBlog: PropTypes.func.isRequired,
};

export default memo(Routing);



================================================
FILE: src/logged_out/components/blog/Blog.js
================================================
import React, { useEffect } from "react";
import PropTypes from "prop-types";
import classNames from "classnames";
import { Grid, Box } from "@mui/material";
import withStyles from "@mui/styles/withStyles";
import BlogCard from "./BlogCard";
import useMediaQuery from "@mui/material/useMediaQuery";

const styles = (theme) => ({
  blogContentWrapper: {
    marginLeft: theme.spacing(1),
    marginRight: theme.spacing(1),
    [theme.breakpoints.up("sm")]: {
      marginLeft: theme.spacing(4),
      marginRight: theme.spacing(4),
    },
    maxWidth: 1280,
    width: "100%",
  },
  wrapper: {
    minHeight: "60vh",
  },
  noDecoration: {
    textDecoration: "none !important",
  },
});

function getVerticalBlogPosts(isWidthUpSm, isWidthUpMd, blogPosts) {
  const gridRows = [[], [], []];
  let rows;
  let xs;
  if (isWidthUpMd) {
    rows = 3;
    xs = 4;
  } else if (isWidthUpSm) {
    rows = 2;
    xs = 6;
  } else {
    rows = 1;
    xs = 12;
  }
  blogPosts.forEach((blogPost, index) => {
    gridRows[index % rows].push(
      <Grid key={blogPost.id} item xs={12}>
        <Box mb={3}>
          <BlogCard
            src={blogPost.src}
            title={blogPost.title}
            snippet={blogPost.snippet}
            date={blogPost.date}
            url={blogPost.url}
          />
        </Box>
      </Grid>
    );
  });
  return gridRows.map((element, index) => (
    <Grid key={index} item xs={xs}>
      {element}
    </Grid>
  ));
}

function Blog(props) {
  const { classes, blogPosts, selectBlog, theme } = props;

  const isWidthUpSm = useMediaQuery(theme.breakpoints.up("sm"));
  const isWidthUpMd = useMediaQuery(theme.breakpoints.up("md"));

  useEffect(() => {
    selectBlog();
  }, [selectBlog]);

  return (
    <Box
      display="flex"
      justifyContent="center"
      className={classNames(classes.wrapper, "lg-p-top")}
    >
      <div className={classes.blogContentWrapper}>
        <Grid container spacing={3}>
          {getVerticalBlogPosts(isWidthUpSm, isWidthUpMd, blogPosts)}
        </Grid>
      </div>
    </Box>
  );
}

Blog.propTypes = {
  selectBlog: PropTypes.func.isRequired,
  classes: PropTypes.object.isRequired,
  blogPosts: PropTypes.arrayOf(PropTypes.object),
};

export default withStyles(styles, { withTheme: true })(Blog);



================================================
FILE: src/logged_out/components/blog/BlogCard.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Link } from "react-router-dom";
import format from "date-fns/format";
import classNames from "classnames";
import { Typography, Card, Box } from "@mui/material";

import withStyles from '@mui/styles/withStyles';

const styles = (theme) => ({
  img: {
    width: "100%",
    height: "auto",
    marginBottom: 8,
  },
  card: {
    boxShadow: theme.shadows[2],
  },
  noDecoration: {
    textDecoration: "none !important",
  },
  title: {
    transition: theme.transitions.create(["background-color"], {
      duration: theme.transitions.duration.complex,
      easing: theme.transitions.easing.easeInOut,
    }),
    cursor: "pointer",
    color: theme.palette.secondary.main,
    "&:hover": {
      color: theme.palette.secondary.dark,
    },
    "&:active": {
      color: theme.palette.primary.dark,
    },
  },
  link: {
    transition: theme.transitions.create(["background-color"], {
      duration: theme.transitions.duration.complex,
      easing: theme.transitions.easing.easeInOut,
    }),
    cursor: "pointer",
    color: theme.palette.primary.main,
    "&:hover": {
      color: theme.palette.primary.dark,
    },
  },
  showFocus: {
    "&:focus span": {
      color: theme.palette.secondary.dark,
    },
  },
});

function BlogCard(props) {
  const { classes, url, src, date, title, snippet } = props;

  return (
    <Card className={classes.card}>
      {src && (
        <Link to={url} tabIndex={-1}>
          <img src={src} className={classes.img} alt="" />
        </Link>
      )}
      <Box p={2}>
        <Typography variant="body2" color="textSecondary">
          {format(new Date(date * 1000), "PPP", {
            awareOfUnicodeTokens: true,
          })}
        </Typography>
        <Link
          to={url}
          className={classNames(classes.noDecoration, classes.showFocus)}
        >
          <Typography variant="h6">
            <span className={classes.title}>{title}</span>
          </Typography>
        </Link>
        <Typography variant="body1" color="textSecondary">
          {snippet}
          <Link to={url} className={classes.noDecoration} tabIndex={-1}>
            <span className={classes.link}> read more...</span>
          </Link>
        </Typography>
      </Box>
    </Card>
  );
}

BlogCard.propTypes = {
  classes: PropTypes.object.isRequired,
  url: PropTypes.string.isRequired,
  title: PropTypes.string.isRequired,
  date: PropTypes.number.isRequired,
  snippet: PropTypes.string.isRequired,
  src: PropTypes.string,
};

export default withStyles(styles, { withTheme: true })(BlogCard);



================================================
FILE: src/logged_out/components/blog/BlogPost.js
================================================
import React, { useEffect } from "react";
import PropTypes from "prop-types";
import classNames from "classnames";
import format from "date-fns/format";
import { Grid, Typography, Card, Box } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import BlogCard from "./BlogCard";
import ShareButton from "../../../shared/components/ShareButton";
import ZoomImage from "../../../shared/components/ZoomImage";
import smoothScrollTop from "../../../shared/functions/smoothScrollTop";

const styles = (theme) => ({
  blogContentWrapper: {
    marginLeft: theme.spacing(1),
    marginRight: theme.spacing(1),
    [theme.breakpoints.up("sm")]: {
      marginLeft: theme.spacing(4),
      marginRight: theme.spacing(4),
    },
    maxWidth: 1280,
    width: "100%",
  },
  wrapper: {
    minHeight: "60vh",
  },
  img: {
    width: "100%",
    height: "auto",
  },
  card: {
    boxShadow: theme.shadows[4],
  },
});

function BlogPost(props) {
  const { classes, date, title, src, content, otherArticles } = props;

  useEffect(() => {
    document.title = `WaVer - ${title}`;
    smoothScrollTop();
  }, [title]);

  return (
    <Box
      className={classNames("lg-p-top", classes.wrapper)}
      display="flex"
      justifyContent="center"
    >
      <div className={classes.blogContentWrapper}>
        <Grid container spacing={5}>
          <Grid item md={9}>
            <Card className={classes.card}>
              <Box pt={3} pr={3} pl={3} pb={2}>
                <Typography variant="h4">
                  <b>{title}</b>
                </Typography>
                <Typography variant="body1" color="textSecondary">
                  {format(new Date(date * 1000), "PPP", {
                    awareOfUnicodeTokens: true,
                  })}
                </Typography>
              </Box>
              <ZoomImage className={classes.img} src={src} alt="" />
              <Box p={3}>
                {content}
                <Box pt={2}>
                  <Grid spacing={1} container>
                    {["Facebook", "Twitter", "Reddit", "Tumblr"].map(
                      (type, index) => (
                        <Grid item key={index}>
                          <ShareButton
                            type={type}
                            title="React SaaS Template"
                            description="I found an awesome template for an webapp using React!"
                            disableElevation
                            variant="contained"
                            className="text-white"
                            classes={{
                              label: "text-white",
                            }}
                          />
                        </Grid>
                      )
                    )}
                  </Grid>
                </Box>
              </Box>
            </Card>
          </Grid>
          <Grid item md={3}>
            <Typography variant="h6" paragraph>
              Other articles
            </Typography>
            {otherArticles.map((blogPost) => (
              <Box key={blogPost.id} mb={3}>
                <BlogCard
                  title={blogPost.title}
                  snippet={blogPost.snippet}
                  date={blogPost.date}
                  url={`${blogPost.url}${blogPost.params}`}
                />
              </Box>
            ))}
          </Grid>
        </Grid>
      </div>
    </Box>
  );
}

BlogPost.propTypes = {
  classes: PropTypes.object.isRequired,
  title: PropTypes.string.isRequired,
  date: PropTypes.number.isRequired,
  src: PropTypes.string.isRequired,
  content: PropTypes.node.isRequired,
  otherArticles: PropTypes.arrayOf(PropTypes.object).isRequired,
};

export default withStyles(styles, { withTheme: true })(BlogPost);



================================================
FILE: src/logged_out/components/cookies/CookieConsent.js
================================================
import React, { Fragment, useState, useCallback, useEffect } from "react";
import PropTypes from "prop-types";
import Cookies from "js-cookie";
import { Snackbar, Button, Typography, Box } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import fetchIpData from "./fetchIpData";

const styles = (theme) => ({
  snackbarContent: {
    borderBottomLeftRadius: 0,
    borderBottomRightRadius: 0,
    paddingLeft: theme.spacing(3),
    paddingRight: theme.spacing(3),
  },
});

const europeanCountryCodes = [
  "AT",
  "BE",
  "BG",
  "CY",
  "CZ",
  "DE",
  "DK",
  "EE",
  "ES",
  "FI",
  "FR",
  "GB",
  "GR",
  "HR",
  "HU",
  "IE",
  "IT",
  "LT",
  "LU",
  "LV",
  "MT",
  "NL",
  "PO",
  "PT",
  "RO",
  "SE",
  "SI",
  "SK",
];

function CookieConsent(props) {
  const { classes, handleCookieRulesDialogOpen } = props;
  const [isVisible, setIsVisible] = useState(false);

  const openOnEuCountry = useCallback(() => {
    fetchIpData
      .then((data) => {
        if (
          data &&
          data.country &&
          !europeanCountryCodes.includes(data.country)
        ) {
          setIsVisible(false);
        } else {
          setIsVisible(true);
        }
      })
      .catch(() => {
        setIsVisible(true);
      });
  }, [setIsVisible]);

  /**
   * Set a persistent cookie
   */
  const onAccept = useCallback(() => {
    Cookies.set("remember-cookie-snackbar", "", {
      expires: 365,
    });
    setIsVisible(false);
  }, [setIsVisible]);

  useEffect(() => {
    if (Cookies.get("remember-cookie-snackbar") === undefined) {
      openOnEuCountry();
    }
  }, [openOnEuCountry]);

  return (
    <Snackbar
      className={classes.snackbarContent}
      open={isVisible}
      message={
        <Typography className="text-white">
          We use cookies to ensure you get the best experience on our website.{" "}
        </Typography>
      }
      action={
        <Fragment>
          <Box mr={1}>
            <Button color="primary" onClick={handleCookieRulesDialogOpen}>
              More details
            </Button>
          </Box>
          <Button color="primary" onClick={onAccept}>
            Got it!
          </Button>
        </Fragment>
      }
    />
  );
}

CookieConsent.propTypes = {
  handleCookieRulesDialogOpen: PropTypes.func.isRequired,
};

export default withStyles(styles, { withTheme: true })(CookieConsent);



================================================
FILE: src/logged_out/components/cookies/CookieRulesDialog.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Dialog, DialogTitle, DialogContent, DialogActions, Typography } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import ArrowBackIcon from "@mui/icons-material/ArrowBack";
import ColoredButton from "../../../shared/components/ColoredButton";

const styles = theme => ({
  dialogActions: {
    justifyContent: "flex-start",
    paddingTop: theme.spacing(2),
    paddingBottom: theme.spacing(2),
    paddingRight: theme.spacing(2)
  },
  dialog: {
    zIndex: 1400
  },
  backIcon: {
    marginRight: theme.spacing(1)
  }
});

function CookieRulesDialog(props) {
  const { classes, onClose, open, theme } = props;
  return (
    <Dialog
      open={open}
      scroll="paper"
      onClose={onClose}
      className={classes.dialog}
    >
      <DialogTitle>Our Cookie Policy</DialogTitle>
      <DialogContent>
        <Typography variant="h6" color="primary" paragraph>
          What Are Cookies
        </Typography>
        <Typography paragraph>
          As is common practice with almost all professional websites this site
          uses cookies, which are tiny files that are downloaded to your
          computer, to improve your experience. This page describes what
          information they gather, how we use it and why we sometimes need to
          store these cookies. We will also share how you can prevent these
          cookies from being stored however this may downgrade or
          &apos;break&apos; certain elements of the sites functionality. For
          more general information on cookies see the Wikipedia article on HTTP
          Cookies.
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          How We Use Cookies
        </Typography>
        <Typography paragraph>
          We use cookies for a variety of reasons detailed below. Unfortunately
          in most cases there are no industry standard options for disabling
          cookies without completely disabling the functionality and features
          they add to this site. It is recommended that you leave on all cookies
          if you are not sure whether you need them or not in case they are used
          to provide a service that you use.
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Disabling Cookies
        </Typography>
        <Typography paragraph>
          You can prevent the setting of cookies by adjusting the settings on
          your browser (see your browser Help for how to do this). Be aware that
          disabling cookies will affect the functionality of this and many other
          websites that you visit. Disabling cookies will usually result in also
          disabling certain functionality and features of the this site.
          Therefore it is recommended that you do not disable cookies.
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          The Cookies We Set
        </Typography>
        <Typography paragraph>Account related cookies:</Typography>
        <Typography paragraph>
          If you create an account with us then we will use cookies for the
          management of the signup process and general administration. These
          cookies will usually be deleted when you log out however in some cases
          they may remain afterwards to remember your site preferences when
          logged out. We use cookies to remember that you accepted this message.
        </Typography>
        <Typography paragraph>Login related cookies:</Typography>
        <Typography paragraph>
          We use cookies when you are logged in so that we can remember this
          fact. This prevents you from having to log in every single time you
          visit a new page. These cookies are typically removed or cleared when
          you log out to ensure that you can only access restricted features and
          areas when logged in.
        </Typography>
        <Typography paragraph>Site preferences cookies:</Typography>
        <Typography paragraph>
          In order to provide you with a great experience on this site we
          provide the functionality to set your preferences for how this site
          runs when you use it. In order to remember your preferences we need to
          set cookies so that this information can be called whenever you
          interact with a page is affected by your preferences.
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Third Party Cookies:
        </Typography>
        <Typography paragraph>
          In some special cases we also use cookies provided by trusted third
          parties. The following section details which third party cookies you
          might encounter through this site.
        </Typography>
        <Typography paragraph>
          Third party analytics are used to track and measure usage of this site
          so that we can continue to produce engaging content. These cookies may
          track things such as how long you spend on the site or pages you visit
          which helps us to understand how we can improve the site for you.
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          More Information
        </Typography>
        <Typography paragraph>
          Hopefully that has clarified things for you and as was previously
          mentioned if there is something that you aren&apos;t sure whether you
          need or not it&apos;s usually safer to leave cookies enabled in case
          it does interact with one of the features you use on our site. This
          Cookies Policy was created with the help of the Cookies Policy
          Template Generator and the Terms and Conditions Template.
        </Typography>
        <Typography paragraph>
          However if you are still looking for more information then you can
          contact us by sending an email to tim.v.kaenel@gmail.com.
        </Typography>
      </DialogContent>
      <DialogActions className={classes.dialogActions}>
        <ColoredButton
          onClick={onClose}
          variant="contained"
          color={theme.palette.common.black}
        >
          <ArrowBackIcon className={classes.backIcon} />
          Back
        </ColoredButton>
      </DialogActions>
    </Dialog>
  );
}

CookieRulesDialog.propTypes = {
  classes: PropTypes.object.isRequired,
  onClose: PropTypes.func.isRequired,
  open: PropTypes.bool.isRequired,
  theme: PropTypes.object.isRequired
};

export default withStyles(styles, { withTheme: true })(CookieRulesDialog);



================================================
FILE: src/logged_out/components/cookies/fetchIpData.js
================================================
const fetchIpData = new Promise((resolve, reject) => {
  const ajax = new XMLHttpRequest();
  if (window.location.href.includes("localhost")) {
    /**
     *  Resolve with dummydata, GET call will be rejected,
     *  since ipinfos server is configured that way
     */
    resolve({ data: { country: "DE" } });
    return;
  }
  ajax.open("GET", "https://ipinfo.io/json");
  ajax.onload = () => {
    const response = JSON.parse(ajax.responseText);
    if (response) {
      resolve(response);
    } else {
      reject();
    }
  };
  ajax.onerror = reject;
  ajax.send();
});

export default fetchIpData;



================================================
FILE: src/logged_out/components/footer/Footer.js
================================================
import React from "react";
import PropTypes from "prop-types";
import {
  Grid,
  Typography,
  Box,
  IconButton,
  Hidden,
  TextField,
} from "@mui/material";
import withStyles from "@mui/styles/withStyles";
import PhoneIcon from "@mui/icons-material/Phone";
import MailIcon from "@mui/icons-material/Mail";
import WaveBorder from "../../../shared/components/WaveBorder";
import ColoredButton from "../../../shared/components/ColoredButton";
import useMediaQuery from "@mui/material/useMediaQuery";

const styles = (theme) => ({
  footerInner: {
    backgroundColor: theme.palette.common.darkBlack,
    paddingTop: theme.spacing(8),
    paddingLeft: theme.spacing(2),
    paddingRight: theme.spacing(2),
    paddingBottom: theme.spacing(6),
    [theme.breakpoints.up("sm")]: {
      paddingTop: theme.spacing(10),
      paddingLeft: theme.spacing(16),
      paddingRight: theme.spacing(16),
      paddingBottom: theme.spacing(10),
    },
    [theme.breakpoints.up("md")]: {
      paddingTop: theme.spacing(10),
      paddingLeft: theme.spacing(10),
      paddingRight: theme.spacing(10),
      paddingBottom: theme.spacing(10),
    },
  },
  brandText: {
    fontFamily: "'Baloo Bhaijaan', cursive",
    fontWeight: 400,
    color: theme.palette.common.white,
  },
  footerLinks: {
    marginTop: theme.spacing(2.5),
    marginBot: theme.spacing(1.5),
    color: theme.palette.common.white,
  },
  infoIcon: {
    color: `${theme.palette.common.white} !important`,
    backgroundColor: "#33383b !important",
  },
  socialIcon: {
    fill: theme.palette.common.white,
    backgroundColor: "#33383b",
    borderRadius: theme.shape.borderRadius,
    "&:hover": {
      backgroundColor: theme.palette.primary.light,
    },
  },
  link: {
    cursor: "Pointer",
    color: theme.palette.common.white,
    transition: theme.transitions.create(["color"], {
      duration: theme.transitions.duration.shortest,
      easing: theme.transitions.easing.easeIn,
    }),
    "&:hover": {
      color: theme.palette.primary.light,
    },
  },
  whiteBg: {
    backgroundColor: theme.palette.common.white,
  },
});

const infos = [
  {
    icon: <PhoneIcon />,
    description: "+1 555 123456",
  },
  {
    icon: <MailIcon />,
    description: "support@company.com",
  },
];

const socialIcons = [
  {
    icon: (
      <svg
        role="img"
        width="24px"
        height="24px"
        viewBox="0 0 24 24"
        xmlns="http://www.w3.org/2000/svg"
      >
        <title>GitHub</title>
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12" />
      </svg>
    ),
    label: "Github",
    href: "https://github.com/dunky11/react-saas-template",
  },
  {
    icon: (
      <svg
        role="img"
        width="24px"
        height="24px"
        viewBox="0 0 24 24"
        xmlns="http://www.w3.org/2000/svg"
      >
        <title>Facebook</title>
        <path d="M23.9981 11.9991C23.9981 5.37216 18.626 0 11.9991 0C5.37216 0 0 5.37216 0 11.9991C0 17.9882 4.38789 22.9522 10.1242 23.8524V15.4676H7.07758V11.9991H10.1242V9.35553C10.1242 6.34826 11.9156 4.68714 14.6564 4.68714C15.9692 4.68714 17.3424 4.92149 17.3424 4.92149V7.87439H15.8294C14.3388 7.87439 13.8739 8.79933 13.8739 9.74824V11.9991H17.2018L16.6698 15.4676H13.8739V23.8524C19.6103 22.9522 23.9981 17.9882 23.9981 11.9991Z" />
      </svg>
    ),
    label: "Facebook",
    href: "https://facebook.com",
  },
  {
    icon: (
      <svg
        role="img"
        width="24px"
        height="24px"
        viewBox="0 0 24 24"
        xmlns="http://www.w3.org/2000/svg"
      >
        <title>LinkedIn</title>
        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z" />
      </svg>
    ),
    label: "LinkedIn",
    href: "https://www.linkedin.com/",
  },
  {
    icon: (
      <svg
        role="img"
        width="24px"
        height="24px"
        viewBox="0 0 24 24"
        xmlns="http://www.w3.org/2000/svg"
      >
        <title>Twitter</title>
        <path d="M23.954 4.569c-.885.389-1.83.654-2.825.775 1.014-.611 1.794-1.574 2.163-2.723-.951.555-2.005.959-3.127 1.184-.896-.959-2.173-1.559-3.591-1.559-2.717 0-4.92 2.203-4.92 4.917 0 .39.045.765.127 1.124C7.691 8.094 4.066 6.13 1.64 3.161c-.427.722-.666 1.561-.666 2.475 0 1.71.87 3.213 2.188 4.096-.807-.026-1.566-.248-2.228-.616v.061c0 2.385 1.693 4.374 3.946 4.827-.413.111-.849.171-1.296.171-.314 0-.615-.03-.916-.086.631 1.953 2.445 3.377 4.604 3.417-1.68 1.319-3.809 2.105-6.102 2.105-.39 0-.779-.023-1.17-.067 2.189 1.394 4.768 2.209 7.557 2.209 9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63.961-.689 1.8-1.56 2.46-2.548l-.047-.02z" />
      </svg>
    ),
    label: "Twitter",
    href: "https://www.twitter.com/",
  },
];

function Footer(props) {
  const { classes, theme } = props;
  const isWidthUpMd = useMediaQuery(theme.breakpoints.up("md"));

  return (
    <footer className="lg-p-top">
      <WaveBorder
        upperColor="#FFFFFF"
        lowerColor={theme.palette.common.darkBlack}
        animationNegativeDelay={4}
      />
      <div className={classes.footerInner}>
        <Grid container spacing={isWidthUpMd ? 10 : 5}>
          <Grid item xs={12} md={6} lg={4}>
            <form>
              <Box display="flex" flexDirection="column">
                <Box mb={1}>
                  <TextField
                    variant="outlined"
                    multiline
                    placeholder="Get in touch with us"
                    InputProps={{
                      className: classes.whiteBg,
                      "aria-label": "Get in Touch",
                    }}
                    rows={4}
                    fullWidth
                    required
                  />
                </Box>
                <ColoredButton
                  color={theme.palette.common.white}
                  variant="outlined"
                  type="submit"
                >
                  Send Message
                </ColoredButton>
              </Box>
            </form>
          </Grid>
          <Hidden lgDown>
            <Grid item xs={12} md={6} lg={4}>
              <Box display="flex" justifyContent="center">
                <div>
                  {infos.map((info, index) => (
                    <Box display="flex" mb={1} key={index}>
                      <Box mr={2}>
                        <IconButton
                          className={classes.infoIcon}
                          tabIndex={-1}
                          disabled
                          size="large"
                        >
                          {info.icon}
                        </IconButton>
                      </Box>
                      <Box
                        display="flex"
                        flexDirection="column"
                        justifyContent="center"
                      >
                        <Typography variant="h6" className="text-white">
                          {info.description}
                        </Typography>
                      </Box>
                    </Box>
                  ))}
                </div>
              </Box>
            </Grid>
          </Hidden>
          <Grid item xs={12} md={6} lg={4}>
            <Typography variant="h6" paragraph className="text-white">
              About the Company
            </Typography>
            <Typography style={{ color: "#8f9296" }} paragraph>
              Lorem ipsum dolor sit amet, consectateur adispicing elit. Fusce
              euismod convallis velit, eu auctor lacus vehicula sit amet.
            </Typography>
            <Box display="flex">
              {socialIcons.map((socialIcon, index) => (
                <Box key={index} mr={index !== socialIcons.length - 1 ? 1 : 0}>
                  <IconButton
                    aria-label={socialIcon.label}
                    className={classes.socialIcon}
                    href={socialIcon.href}
                    size="large"
                  >
                    {socialIcon.icon}
                  </IconButton>
                </Box>
              ))}
            </Box>
          </Grid>
        </Grid>
      </div>
    </footer>
  );
}

Footer.propTypes = {
  theme: PropTypes.object.isRequired,
  classes: PropTypes.object.isRequired,
};

export default withStyles(styles, { withTheme: true })(Footer);



================================================
FILE: src/logged_out/components/home/calculateSpacing.js
================================================
function calculateSpacing(width, theme) {
  console.log(theme["breakpoints"]);
  const currentWidth = theme["breakpoints"]["values"][width];
  if (currentWidth >= theme["breakpoints"]["values"]["lg"]) {
    return 10;
  }
  if (currentWidth >= theme["breakpoints"]["values"]["md"]) {
    return 8;
  }
  if (currentWidth >= theme["breakpoints"]["values"]["sm"]) {
    return 6;
  }
  return 4;
}

export default calculateSpacing;



================================================
FILE: src/logged_out/components/home/FeatureCard.js
================================================
import React, { Fragment } from "react";
import PropTypes from "prop-types";
import { Typography } from "@mui/material";

import withStyles from "@mui/styles/withStyles";

const styles = (theme) => ({
  iconWrapper: {
    borderRadius: theme.shape.borderRadius,
    textAlign: "center",
    display: "inline-flex",
    alignItems: "center",
    justifyContent: "center",
    marginBottom: theme.spacing(3),
    padding: theme.spacing(1) * 1.5,
  },
});

function shadeColor(hex, percent) {
  const f = parseInt(hex.slice(1), 16);

  const t = percent < 0 ? 0 : 255;

  const p = percent < 0 ? percent * -1 : percent;

  const R = f >> 16;

  const G = (f >> 8) & 0x00ff;

  const B = f & 0x0000ff;
  return `#${(
    0x1000000 +
    (Math.round((t - R) * p) + R) * 0x10000 +
    (Math.round((t - G) * p) + G) * 0x100 +
    (Math.round((t - B) * p) + B)
  )
    .toString(16)
    .slice(1)}`;
}

function FeatureCard(props) {
  const { classes, Icon, color, headline, text } = props;
  return (
    <Fragment>
      <div
        // We will set color and fill here, due to some prios complications
        className={classes.iconWrapper}
        style={{
          color: color,
          backgroundColor: shadeColor(color, 0.5),
          fill: color,
          padding: 12,
        }}
      >
        {Icon}
      </div>
      <Typography variant="h5" paragraph>
        {headline}
      </Typography>
      <Typography variant="body1" color="textSecondary">
        {text}
      </Typography>
    </Fragment>
  );
}

FeatureCard.propTypes = {
  classes: PropTypes.object.isRequired,
  Icon: PropTypes.element.isRequired,
  color: PropTypes.string.isRequired,
  headline: PropTypes.string.isRequired,
  text: PropTypes.string.isRequired,
};

export default withStyles(styles, { withTheme: true })(FeatureCard);



================================================
FILE: src/logged_out/components/home/FeatureSection.js
================================================
import React from "react";
import { Grid, Typography } from "@mui/material";
import CodeIcon from "@mui/icons-material/Code";
import BuildIcon from "@mui/icons-material/Build";
import ComputerIcon from "@mui/icons-material/Computer";
import BarChartIcon from "@mui/icons-material/BarChart";
import HeadsetMicIcon from "@mui/icons-material/HeadsetMic";
import CalendarTodayIcon from "@mui/icons-material/CalendarToday";
import CloudIcon from "@mui/icons-material/Cloud";
import MeassageIcon from "@mui/icons-material/Message";
import CancelIcon from "@mui/icons-material/Cancel";
import calculateSpacing from "./calculateSpacing";
import useMediaQuery from "@mui/material/useMediaQuery";
import { withTheme } from "@mui/styles";
import FeatureCard from "./FeatureCard";
import useWidth from "../../../shared/functions/useWidth";

const iconSize = 30;

const features = [
  {
    color: "#00C853",
    headline: "Feature 1",
    text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.",
    icon: <BuildIcon style={{ fontSize: iconSize }} />,
    mdDelay: "0",
    smDelay: "0",
  },
  {
    color: "#6200EA",
    headline: "Feature 2",
    text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.",
    icon: <CalendarTodayIcon style={{ fontSize: iconSize }} />,
    mdDelay: "200",
    smDelay: "200",
  },
  {
    color: "#0091EA",
    headline: "Feature 3",
    text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.",
    icon: <MeassageIcon style={{ fontSize: iconSize }} />,
    mdDelay: "400",
    smDelay: "0",
  },
  {
    color: "#d50000",
    headline: "Feature 4",
    text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.",
    icon: <ComputerIcon style={{ fontSize: iconSize }} />,
    mdDelay: "0",
    smDelay: "200",
  },
  {
    color: "#DD2C00",
    headline: "Feature 5",
    text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.",
    icon: <BarChartIcon style={{ fontSize: iconSize }} />,
    mdDelay: "200",
    smDelay: "0",
  },
  {
    color: "#64DD17",
    headline: "Feature 6",
    text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.",
    icon: <HeadsetMicIcon style={{ fontSize: iconSize }} />,
    mdDelay: "400",
    smDelay: "200",
  },
  {
    color: "#304FFE",
    headline: "Feature 7",
    text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.",
    icon: <CloudIcon style={{ fontSize: iconSize }} />,
    mdDelay: "0",
    smDelay: "0",
  },
  {
    color: "#C51162",
    headline: "Feature 8",
    text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.",
    icon: <CodeIcon style={{ fontSize: iconSize }} />,
    mdDelay: "200",
    smDelay: "200",
  },
  {
    color: "#00B8D4",
    headline: "Feature 9",
    text: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.",
    icon: <CancelIcon style={{ fontSize: iconSize }} />,
    mdDelay: "400",
    smDelay: "0",
  },
];

function FeatureSection(props) {
  const { theme } = props;
  const width = useWidth();
  const isWidthUpMd = useMediaQuery(theme.breakpoints.up("md"));

  return (
    <div style={{ backgroundColor: "#FFFFFF" }}>
      <div className="container-fluid lg-p-top">
        <Typography variant="h3" align="center" className="lg-mg-bottom">
          Features
        </Typography>
        <div className="container-fluid">
          <Grid container spacing={calculateSpacing(width, theme)}>
            {features.map((element) => (
              <Grid
                item
                xs={6}
                md={4}
                data-aos="zoom-in-up"
                data-aos-delay={isWidthUpMd ? element.mdDelay : element.smDelay}
                key={element.headline}
              >
                <FeatureCard
                  Icon={element.icon}
                  color={element.color}
                  headline={element.headline}
                  text={element.text}
                />
              </Grid>
            ))}
          </Grid>
        </div>
      </div>
    </div>
  );
}

FeatureSection.propTypes = {};

export default withTheme(FeatureSection);



================================================
FILE: src/logged_out/components/home/HeadSection.js
================================================
import React, { Fragment } from "react";
import PropTypes from "prop-types";
import classNames from "classnames";
import { Grid, Typography, Card, Button, Hidden, Box } from "@mui/material";
import withStyles from "@mui/styles/withStyles";
import WaveBorder from "../../../shared/components/WaveBorder";
import ZoomImage from "../../../shared/components/ZoomImage";
import useMediaQuery from "@mui/material/useMediaQuery";

const styles = (theme) => ({
  extraLargeButtonLabel: {
    fontSize: theme.typography.body1.fontSize,
    [theme.breakpoints.up("sm")]: {
      fontSize: theme.typography.h6.fontSize,
    },
  },
  extraLargeButton: {
    paddingTop: theme.spacing(1.5),
    paddingBottom: theme.spacing(1.5),
    [theme.breakpoints.up("xs")]: {
      paddingTop: theme.spacing(1),
      paddingBottom: theme.spacing(1),
    },
    [theme.breakpoints.up("lg")]: {
      paddingTop: theme.spacing(2),
      paddingBottom: theme.spacing(2),
    },
  },
  card: {
    boxShadow: theme.shadows[4],
    marginLeft: theme.spacing(2),
    marginRight: theme.spacing(2),
    [theme.breakpoints.up("xs")]: {
      paddingTop: theme.spacing(3),
      paddingBottom: theme.spacing(3),
    },
    [theme.breakpoints.up("sm")]: {
      paddingTop: theme.spacing(5),
      paddingBottom: theme.spacing(5),
      paddingLeft: theme.spacing(4),
      paddingRight: theme.spacing(4),
    },
    [theme.breakpoints.up("md")]: {
      paddingTop: theme.spacing(5.5),
      paddingBottom: theme.spacing(5.5),
      paddingLeft: theme.spacing(5),
      paddingRight: theme.spacing(5),
    },
    [theme.breakpoints.up("lg")]: {
      paddingTop: theme.spacing(6),
      paddingBottom: theme.spacing(6),
      paddingLeft: theme.spacing(6),
      paddingRight: theme.spacing(6),
    },
    [theme.breakpoints.down("xl")]: {
      width: "auto",
    },
  },
  wrapper: {
    position: "relative",
    backgroundColor: theme.palette.secondary.main,
    paddingBottom: theme.spacing(2),
  },
  image: {
    maxWidth: "100%",
    verticalAlign: "middle",
    borderRadius: theme.shape.borderRadius,
    boxShadow: theme.shadows[4],
  },
  container: {
    marginTop: theme.spacing(6),
    marginBottom: theme.spacing(12),
    [theme.breakpoints.down("lg")]: {
      marginBottom: theme.spacing(9),
    },
    [theme.breakpoints.down("md")]: {
      marginBottom: theme.spacing(6),
    },
    [theme.breakpoints.down("md")]: {
      marginBottom: theme.spacing(3),
    },
  },
  containerFix: {
    [theme.breakpoints.up("md")]: {
      maxWidth: "none !important",
    },
  },
  waveBorder: {
    paddingTop: theme.spacing(4),
  },
});

function HeadSection(props) {
  const { classes, theme } = props;
  const isWidthUpLg = useMediaQuery(theme.breakpoints.up("lg"));

  return (
    <Fragment>
      <div className={classNames("lg-p-top", classes.wrapper)}>
        <div className={classNames("container-fluid", classes.container)}>
          <Box display="flex" justifyContent="center" className="row">
            <Card
              className={classes.card}
              data-aos-delay="200"
              data-aos="zoom-in"
            >
              <div className={classNames(classes.containerFix, "container")}>
                <Box justifyContent="space-between" className="row">
                  <Grid item xs={12} md={5}>
                    <Box
                      display="flex"
                      flexDirection="column"
                      justifyContent="space-between"
                      height="100%"
                    >
                      <Box mb={4}>
                        <Typography variant={isWidthUpLg ? "h3" : "h4"}>
                          Free Template for building a SaaS app using
                          Material-UI
                        </Typography>
                      </Box>
                      <div>
                        <Box mb={2}>
                          <Typography
                            variant={isWidthUpLg ? "h6" : "body1"}
                            color="textSecondary"
                          >
                            Lorem ipsum dolor sit amet, consetetur sadipscing
                            elitr, sed diam nonumy eirmod tempor invidunt
                          </Typography>
                        </Box>
                        <Button
                          variant="contained"
                          color="secondary"
                          fullWidth
                          className={classes.extraLargeButton}
                          classes={{ label: classes.extraLargeButtonLabel }}
                          href="https://github.com/dunky11/react-saas-template"
                        >
                          Download from GitHub
                        </Button>
                      </div>
                    </Box>
                  </Grid>
                  <Hidden mdDown>
                    <Grid item md={6}>
                      <ZoomImage
                        src={`${process.env.PUBLIC_URL}/images/logged_out/headerImage.jpg`}
                        className={classes.image}
                        alt="header example"
                      />
                    </Grid>
                  </Hidden>
                </Box>
              </div>
            </Card>
          </Box>
        </div>
      </div>
      <WaveBorder
        upperColor={theme.palette.secondary.main}
        lowerColor="#FFFFFF"
        className={classes.waveBorder}
        animationNegativeDelay={2}
      />
    </Fragment>
  );
}

HeadSection.propTypes = {
  classes: PropTypes.object,
  theme: PropTypes.object,
};

export default withStyles(styles, { withTheme: true })(HeadSection);



================================================
FILE: src/logged_out/components/home/Home.js
================================================
import React, { Fragment, useEffect } from "react";
import PropTypes from "prop-types";
import HeadSection from "./HeadSection";
import FeatureSection from "./FeatureSection";
import PricingSection from "./PricingSection";

function Home(props) {
  const { selectHome } = props;
  useEffect(() => {
    selectHome();
  }, [selectHome]);
  return (
    <Fragment>
      <HeadSection />
      <FeatureSection />
      <PricingSection />
    </Fragment>
  );
}

Home.propTypes = {
  selectHome: PropTypes.func.isRequired
};

export default Home;



================================================
FILE: src/logged_out/components/home/PriceCard.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Typography, Box } from "@mui/material";
import withStyles from "@mui/styles/withStyles";
import CheckIcon from "@mui/icons-material/Check";

const styles = (theme) => ({
  card: {
    paddingTop: theme.spacing(6),
    paddingBottom: theme.spacing(6),
    paddingLeft: theme.spacing(4),
    paddingRight: theme.spacing(4),
    marginTop: theme.spacing(2),
    border: `3px solid ${theme.palette.primary.dark}`,
    borderRadius: theme.shape.borderRadius * 2,
  },
  cardHightlighted: {
    paddingTop: theme.spacing(8),
    paddingBottom: theme.spacing(4),
    paddingLeft: theme.spacing(4),
    paddingRight: theme.spacing(4),
    border: `3px solid ${theme.palette.primary.dark}`,
    borderRadius: theme.shape.borderRadius * 2,
    backgroundColor: theme.palette.primary.main,
    [theme.breakpoints.down("sm")]: {
      marginTop: theme.spacing(2),
    },
  },
  title: {
    color: theme.palette.primary.main,
  },
});

function PriceCard(props) {
  const { classes, theme, title, pricing, features, highlighted } = props;
  return (
    <div className={highlighted ? classes.cardHightlighted : classes.card}>
      <Box mb={2}>
        <Typography
          variant={highlighted ? "h5" : "h6"}
          className={highlighted ? "text-white" : classes.title}
        >
          {title}
        </Typography>
      </Box>
      <Box mb={2}>
        <Typography
          variant={highlighted ? "h3" : "h4"}
          className={highlighted ? "text-white" : null}
        >
          {pricing}
        </Typography>
      </Box>
      {features.map((feature, index) => (
        <Box display="flex" alignItems="center" mb={1} key={index}>
          <CheckIcon
            style={{
              color: highlighted
                ? theme.palette.common.white
                : theme.palette.primary.dark,
            }}
          />
          <Box ml={1}>
            <Typography
              className={highlighted ? "text-white" : null}
              variant={highlighted ? "h6" : "body1"}
            >
              {feature}
            </Typography>
          </Box>
        </Box>
      ))}
    </div>
  );
}

PriceCard.propTypes = {
  classes: PropTypes.object.isRequired,
  theme: PropTypes.object.isRequired,
  title: PropTypes.string.isRequired,
  pricing: PropTypes.oneOfType([PropTypes.node, PropTypes.string]).isRequired,
  highlighted: PropTypes.bool,
};

export default withStyles(styles, { withTheme: true })(PriceCard);



================================================
FILE: src/logged_out/components/home/PricingSection.js
================================================
import React from "react";
import classNames from "classnames";
import { Grid, Typography } from "@mui/material";
import { withStyles } from "@mui/styles";
import PriceCard from "./PriceCard";
import calculateSpacing from "./calculateSpacing";
import useMediaQuery from "@mui/material/useMediaQuery";
import useWidth from "../../../shared/functions/useWidth";

const styles = (theme) => ({
  containerFix: {
    [theme.breakpoints.down("lg")]: {
      paddingLeft: theme.spacing(6),
      paddingRight: theme.spacing(6),
    },
    [theme.breakpoints.down("md")]: {
      paddingLeft: theme.spacing(4),
      paddingRight: theme.spacing(4),
    },
    [theme.breakpoints.down("sm")]: {
      paddingLeft: theme.spacing(2),
      paddingRight: theme.spacing(2),
    },
    overflow: "hidden",
    paddingTop: theme.spacing(1),
    paddingBottom: theme.spacing(1),
  },
  cardWrapper: {
    [theme.breakpoints.down("sm")]: {
      marginLeft: "auto",
      marginRight: "auto",
      maxWidth: 340,
    },
  },
  cardWrapperHighlighted: {
    [theme.breakpoints.down("sm")]: {
      marginLeft: "auto",
      marginRight: "auto",
      maxWidth: 360,
    },
  },
});

function PricingSection(props) {
  const { classes, theme } = props;
  const width = useWidth();
  const isWidthUpMd = useMediaQuery(theme.breakpoints.up("md"));
  return (
    <div className="lg-p-top" style={{ backgroundColor: "#FFFFFF" }}>
      <Typography variant="h3" align="center" className="lg-mg-bottom">
        Pricing
      </Typography>
      <div className={classNames("container-fluid", classes.containerFix)}>
        <Grid
          container
          spacing={calculateSpacing(width, theme)}
          className={classes.gridContainer}
        >
          <Grid
            item
            xs={12}
            sm={6}
            lg={3}
            className={classes.cardWrapper}
            data-aos="zoom-in-up"
          >
            <PriceCard
              title="Starter"
              pricing={
                <span>
                  $14.99
                  <Typography display="inline"> / month</Typography>
                </span>
              }
              features={["Feature 1", "Feature 2", "Feature 3"]}
            />
          </Grid>
          <Grid
            item
            className={classes.cardWrapperHighlighted}
            xs={12}
            sm={6}
            lg={3}
            data-aos="zoom-in-up"
            data-aos-delay="200"
          >
            <PriceCard
              highlighted
              title="Premium"
              pricing={
                <span>
                  $29.99
                  <Typography display="inline"> / month</Typography>
                </span>
              }
              features={["Feature 1", "Feature 2", "Feature 3"]}
            />
          </Grid>
          <Grid
            item
            className={classes.cardWrapper}
            xs={12}
            sm={6}
            lg={3}
            data-aos="zoom-in-up"
            data-aos-delay={isWidthUpMd ? "400" : "0"}
          >
            <PriceCard
              title="Business"
              pricing={
                <span>
                  $49.99
                  <Typography display="inline"> / month</Typography>
                </span>
              }
              features={["Feature 1", "Feature 2", "Feature 3"]}
            />
          </Grid>
          <Grid
            item
            className={classes.cardWrapper}
            xs={12}
            sm={6}
            lg={3}
            data-aos="zoom-in-up"
            data-aos-delay={isWidthUpMd ? "600" : "200"}
          >
            <PriceCard
              title="Tycoon"
              pricing={
                <span>
                  $99.99
                  <Typography display="inline"> / month</Typography>
                </span>
              }
              features={["Feature 1", "Feature 2", "Feature 3"]}
            />
          </Grid>
        </Grid>
      </div>
    </div>
  );
}

PricingSection.propTypes = {};

export default withStyles(styles, { withTheme: true })(PricingSection);



================================================
FILE: src/logged_out/components/navigation/NavBar.js
================================================
import React, { memo } from "react";
import PropTypes from "prop-types";
import { Link } from "react-router-dom";
import { AppBar, Toolbar, Typography, Button, Hidden, IconButton } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import MenuIcon from "@mui/icons-material/Menu";
import HomeIcon from "@mui/icons-material/Home";
import HowToRegIcon from "@mui/icons-material/HowToReg";
import LockOpenIcon from "@mui/icons-material/LockOpen";
import BookIcon from "@mui/icons-material/Book";
import NavigationDrawer from "../../../shared/components/NavigationDrawer";

const styles = theme => ({
  appBar: {
    boxShadow: theme.shadows[6],
    backgroundColor: theme.palette.common.white
  },
  toolbar: {
    display: "flex",
    justifyContent: "space-between"
  },
  menuButtonText: {
    fontSize: theme.typography.body1.fontSize,
    fontWeight: theme.typography.h6.fontWeight
  },
  brandText: {
    fontFamily: "'Baloo Bhaijaan', cursive",
    fontWeight: 400
  },
  noDecoration: {
    textDecoration: "none !important"
  }
});

function NavBar(props) {
  const {
    classes,
    openRegisterDialog,
    openLoginDialog,
    handleMobileDrawerOpen,
    handleMobileDrawerClose,
    mobileDrawerOpen,
    selectedTab
  } = props;
  const menuItems = [
    {
      link: "/",
      name: "Home",
      icon: <HomeIcon className="text-white" />
    },
    {
      link: "/blog",
      name: "Blog",
      icon: <BookIcon className="text-white" />
    },
    {
      name: "Register",
      onClick: openRegisterDialog,
      icon: <HowToRegIcon className="text-white" />
    },
    {
      name: "Login",
      onClick: openLoginDialog,
      icon: <LockOpenIcon className="text-white" />
    }
  ];
  return (
    <div className={classes.root}>
      <AppBar position="fixed" className={classes.appBar}>
        <Toolbar className={classes.toolbar}>
          <div>
            <Typography
              variant="h4"
              className={classes.brandText}
              display="inline"
              color="primary"
            >
              Wa
            </Typography>
            <Typography
              variant="h4"
              className={classes.brandText}
              display="inline"
              color="secondary"
            >
              Ver
            </Typography>
          </div>
          <div>
            <Hidden mdUp>
              <IconButton
                className={classes.menuButton}
                onClick={handleMobileDrawerOpen}
                aria-label="Open Navigation"
                size="large">
                <MenuIcon color="primary" />
              </IconButton>
            </Hidden>
            <Hidden mdDown>
              {menuItems.map(element => {
                if (element.link) {
                  return (
                    <Link
                      key={element.name}
                      to={element.link}
                      className={classes.noDecoration}
                      onClick={handleMobileDrawerClose}
                    >
                      <Button
                        color="secondary"
                        size="large"
                        classes={{ text: classes.menuButtonText }}
                      >
                        {element.name}
                      </Button>
                    </Link>
                  );
                }
                return (
                  <Button
                    color="secondary"
                    size="large"
                    onClick={element.onClick}
                    classes={{ text: classes.menuButtonText }}
                    key={element.name}
                  >
                    {element.name}
                  </Button>
                );
              })}
            </Hidden>
          </div>
        </Toolbar>
      </AppBar>
      <NavigationDrawer
        menuItems={menuItems}
        anchor="right"
        open={mobileDrawerOpen}
        selectedItem={selectedTab}
        onClose={handleMobileDrawerClose}
      />
    </div>
  );
}

NavBar.propTypes = {
  classes: PropTypes.object.isRequired,
  handleMobileDrawerOpen: PropTypes.func,
  handleMobileDrawerClose: PropTypes.func,
  mobileDrawerOpen: PropTypes.bool,
  selectedTab: PropTypes.string,
  openRegisterDialog: PropTypes.func.isRequired,
  openLoginDialog: PropTypes.func.isRequired
};

export default withStyles(styles, { withTheme: true })(memo(NavBar));



================================================
FILE: src/logged_out/components/register_login/ChangePasswordDialog.js
================================================
import React, { useState, useCallback } from "react";
import PropTypes from "prop-types";
import { TextField, Dialog, DialogContent, DialogActions, Button, Typography } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import ButtonCircularProgress from "../../../shared/components/ButtonCircularProgress";

const styles = (theme) => ({
  dialogContent: {
    paddingTop: theme.spacing(2),
  },
  dialogActions: {
    paddingTop: theme.spacing(2),
    paddingBottom: theme.spacing(2),
    paddingRight: theme.spacing(2),
  },
});

function ChangePassword(props) {
  const { onClose, classes, setLoginStatus } = props;
  const [isLoading, setIsLoading] = useState(false);

  const sendPasswordEmail = useCallback(() => {
    setIsLoading(true);
    setTimeout(() => {
      setLoginStatus("verificationEmailSend");
      setIsLoading(false);
      onClose();
    }, 1500);
  }, [setIsLoading, setLoginStatus, onClose]);

  return (
    <Dialog
      open
      hideBackdrop
      onClose={onClose}
      disableEscapeKeyDown={isLoading}
      maxWidth="xs">
      <form
        onSubmit={(e) => {
          e.preventDefault();
          sendPasswordEmail();
        }}
      >
        <DialogContent className={classes.dialogContent}>
          <Typography paragraph>
            Enter your email address below and we will send you instructions on
            how to reset your password.
          </Typography>
          <TextField
            variant="outlined"
            margin="dense"
            required
            fullWidth
            label="Email Address"
            autoFocus
            type="email"
            autoComplete="off"
          />
        </DialogContent>
        <DialogActions className={classes.dialogActions}>
          <Button onClick={onClose} disabled={isLoading}>
            Cancel
          </Button>
          <Button
            type="submit"
            variant="contained"
            color="secondary"
            disabled={isLoading}
          >
            Reset password
            {isLoading && <ButtonCircularProgress />}
          </Button>
        </DialogActions>
      </form>
    </Dialog>
  );
}

ChangePassword.propTypes = {
  onClose: PropTypes.func.isRequired,
  classes: PropTypes.object.isRequired,
  theme: PropTypes.object.isRequired,
  setLoginStatus: PropTypes.func.isRequired,
};

export default withStyles(styles, { withTheme: true })(ChangePassword);



================================================
FILE: src/logged_out/components/register_login/DialogSelector.js
================================================
import React, { useState, useCallback, Fragment } from "react";
import PropTypes from "prop-types";
import RegisterDialog from "./RegisterDialog";
import TermsOfServiceDialog from "./TermsOfServiceDialog";
import LoginDialog from "./LoginDialog";
import ChangePasswordDialog from "./ChangePasswordDialog";
import ModalBackdrop from "../../../shared/components/ModalBackdrop";

function DialogSelector(props) {
  const {
    dialogOpen,
    openTermsDialog,
    openRegisterDialog,
    openLoginDialog,
    openChangePasswordDialog,
    onClose,
  } = props;
  const [loginStatus, setLoginStatus] = useState(null);
  const [registerStatus, setRegisterStatus] = useState(null);

  const _onClose = useCallback(() => {
    setLoginStatus(null);
    setRegisterStatus(null);
    onClose();
  }, [onClose, setLoginStatus, setRegisterStatus]);

  const printDialog = useCallback(() => {
    switch (dialogOpen) {
      case "register":
        return (
          <RegisterDialog
            onClose={_onClose}
            openTermsDialog={openTermsDialog}
            status={registerStatus}
            setStatus={setRegisterStatus}
          />
        );
      case "termsOfService":
        return <TermsOfServiceDialog onClose={openRegisterDialog} />;
      case "login":
        return (
          <LoginDialog
            onClose={_onClose}
            status={loginStatus}
            setStatus={setLoginStatus}
            openChangePasswordDialog={openChangePasswordDialog}
          />
        );
      case "changePassword":
        return (
          <ChangePasswordDialog
            setLoginStatus={setLoginStatus}
            onClose={openLoginDialog}
          />
        );
      default:
    }
  }, [
    dialogOpen,
    openChangePasswordDialog,
    openLoginDialog,
    openRegisterDialog,
    openTermsDialog,
    _onClose,
    loginStatus,
    registerStatus,
    setLoginStatus,
    setRegisterStatus,
  ]);

  return (
    <Fragment>
      {dialogOpen && <ModalBackdrop open />}
      {printDialog()}
    </Fragment>
  );
}

DialogSelector.propTypes = {
  dialogOpen: PropTypes.string,
  openLoginDialog: PropTypes.func.isRequired,
  onClose: PropTypes.func.isRequired,
  openTermsDialog: PropTypes.func.isRequired,
  openRegisterDialog: PropTypes.func.isRequired,
  openChangePasswordDialog: PropTypes.func.isRequired,
};

export default DialogSelector;



================================================
FILE: src/logged_out/components/register_login/LoginDialog.js
================================================
import React, { useState, useCallback, useRef, Fragment } from "react";
import PropTypes from "prop-types";
import classNames from "classnames";
import { withRouter } from "react-router-dom";
import { TextField, Button, Checkbox, Typography, FormControlLabel } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import FormDialog from "../../../shared/components/FormDialog";
import HighlightedInformation from "../../../shared/components/HighlightedInformation";
import ButtonCircularProgress from "../../../shared/components/ButtonCircularProgress";
import VisibilityPasswordTextField from "../../../shared/components/VisibilityPasswordTextField";

const styles = (theme) => ({
  forgotPassword: {
    marginTop: theme.spacing(2),
    color: theme.palette.primary.main,
    cursor: "pointer",
    "&:enabled:hover": {
      color: theme.palette.primary.dark,
    },
    "&:enabled:focus": {
      color: theme.palette.primary.dark,
    },
  },
  disabledText: {
    cursor: "auto",
    color: theme.palette.text.disabled,
  },
  formControlLabel: {
    marginRight: 0,
  },
});

function LoginDialog(props) {
  const {
    setStatus,
    history,
    classes,
    onClose,
    openChangePasswordDialog,
    status,
  } = props;
  const [isLoading, setIsLoading] = useState(false);
  const [isPasswordVisible, setIsPasswordVisible] = useState(false);
  const loginEmail = useRef();
  const loginPassword = useRef();

  const login = useCallback(() => {
    setIsLoading(true);
    setStatus(null);
    if (loginEmail.current.value !== "test@web.com") {
      setTimeout(() => {
        setStatus("invalidEmail");
        setIsLoading(false);
      }, 1500);
    } else if (loginPassword.current.value !== "HaRzwc") {
      setTimeout(() => {
        setStatus("invalidPassword");
        setIsLoading(false);
      }, 1500);
    } else {
      setTimeout(() => {
        history.push("/c/dashboard");
      }, 150);
    }
  }, [setIsLoading, loginEmail, loginPassword, history, setStatus]);

  return (
    <Fragment>
      <FormDialog
        open
        onClose={onClose}
        loading={isLoading}
        onFormSubmit={(e) => {
          e.preventDefault();
          login();
        }}
        hideBackdrop
        headline="Login"
        content={
          <Fragment>
            <TextField
              variant="outlined"
              margin="normal"
              error={status === "invalidEmail"}
              required
              fullWidth
              label="Email Address"
              inputRef={loginEmail}
              autoFocus
              autoComplete="off"
              type="email"
              onChange={() => {
                if (status === "invalidEmail") {
                  setStatus(null);
                }
              }}
              helperText={
                status === "invalidEmail" &&
                "This email address isn't associated with an account."
              }
              FormHelperTextProps={{ error: true }}
            />
            <VisibilityPasswordTextField
              variant="outlined"
              margin="normal"
              required
              fullWidth
              error={status === "invalidPassword"}
              label="Password"
              inputRef={loginPassword}
              autoComplete="off"
              onChange={() => {
                if (status === "invalidPassword") {
                  setStatus(null);
                }
              }}
              helperText={
                status === "invalidPassword" ? (
                  <span>
                    Incorrect password. Try again, or click on{" "}
                    <b>&quot;Forgot Password?&quot;</b> to reset it.
                  </span>
                ) : (
                  ""
                )
              }
              FormHelperTextProps={{ error: true }}
              onVisibilityChange={setIsPasswordVisible}
              isVisible={isPasswordVisible}
            />
            <FormControlLabel
              className={classes.formControlLabel}
              control={<Checkbox color="primary" />}
              label={<Typography variant="body1">Remember me</Typography>}
            />
            {status === "verificationEmailSend" ? (
              <HighlightedInformation>
                We have send instructions on how to reset your password to your
                email address
              </HighlightedInformation>
            ) : (
              <HighlightedInformation>
                Email is: <b>test@web.com</b>
                <br />
                Password is: <b>HaRzwc</b>
              </HighlightedInformation>
            )}
          </Fragment>
        }
        actions={
          <Fragment>
            <Button
              type="submit"
              fullWidth
              variant="contained"
              color="secondary"
              disabled={isLoading}
              size="large"
            >
              Login
              {isLoading && <ButtonCircularProgress />}
            </Button>
            <Typography
              align="center"
              className={classNames(
                classes.forgotPassword,
                isLoading ? classes.disabledText : null
              )}
              color="primary"
              onClick={isLoading ? null : openChangePasswordDialog}
              tabIndex={0}
              role="button"
              onKeyDown={(event) => {
                // For screenreaders listen to space and enter events
                if (
                  (!isLoading && event.keyCode === 13) ||
                  event.keyCode === 32
                ) {
                  openChangePasswordDialog();
                }
              }}
            >
              Forgot Password?
            </Typography>
          </Fragment>
        }
      />
    </Fragment>
  );
}

LoginDialog.propTypes = {
  classes: PropTypes.object.isRequired,
  onClose: PropTypes.func.isRequired,
  setStatus: PropTypes.func.isRequired,
  openChangePasswordDialog: PropTypes.func.isRequired,
  history: PropTypes.object.isRequired,
  status: PropTypes.string,
};

export default withRouter(withStyles(styles)(LoginDialog));



================================================
FILE: src/logged_out/components/register_login/RegisterDialog.js
================================================
import React, { useState, useCallback, useRef, Fragment } from "react";
import PropTypes from "prop-types";
import { FormHelperText, TextField, Button, Checkbox, Typography, FormControlLabel } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import FormDialog from "../../../shared/components/FormDialog";
import HighlightedInformation from "../../../shared/components/HighlightedInformation";
import ButtonCircularProgress from "../../../shared/components/ButtonCircularProgress";
import VisibilityPasswordTextField from "../../../shared/components/VisibilityPasswordTextField";

const styles = (theme) => ({
  link: {
    transition: theme.transitions.create(["background-color"], {
      duration: theme.transitions.duration.complex,
      easing: theme.transitions.easing.easeInOut,
    }),
    cursor: "pointer",
    color: theme.palette.primary.main,
    "&:enabled:hover": {
      color: theme.palette.primary.dark,
    },
    "&:enabled:focus": {
      color: theme.palette.primary.dark,
    },
  },
});

function RegisterDialog(props) {
  const { setStatus, theme, onClose, openTermsDialog, status, classes } = props;
  const [isLoading, setIsLoading] = useState(false);
  const [hasTermsOfServiceError, setHasTermsOfServiceError] = useState(false);
  const [isPasswordVisible, setIsPasswordVisible] = useState(false);
  const registerTermsCheckbox = useRef();
  const registerPassword = useRef();
  const registerPasswordRepeat = useRef();

  const register = useCallback(() => {
    if (!registerTermsCheckbox.current.checked) {
      setHasTermsOfServiceError(true);
      return;
    }
    if (
      registerPassword.current.value !== registerPasswordRepeat.current.value
    ) {
      setStatus("passwordsDontMatch");
      return;
    }
    setStatus(null);
    setIsLoading(true);
    setTimeout(() => {
      setIsLoading(false);
    }, 1500);
  }, [
    setIsLoading,
    setStatus,
    setHasTermsOfServiceError,
    registerPassword,
    registerPasswordRepeat,
    registerTermsCheckbox,
  ]);

  return (
    <FormDialog
      loading={isLoading}
      onClose={onClose}
      open
      headline="Register"
      onFormSubmit={(e) => {
        e.preventDefault();
        register();
      }}
      hideBackdrop
      hasCloseIcon
      content={
        <Fragment>
          <TextField
            variant="outlined"
            margin="normal"
            required
            fullWidth
            error={status === "invalidEmail"}
            label="Email Address"
            autoFocus
            autoComplete="off"
            type="email"
            onChange={() => {
              if (status === "invalidEmail") {
                setStatus(null);
              }
            }}
            FormHelperTextProps={{ error: true }}
          />
          <VisibilityPasswordTextField
            variant="outlined"
            margin="normal"
            required
            fullWidth
            error={
              status === "passwordTooShort" || status === "passwordsDontMatch"
            }
            label="Password"
            inputRef={registerPassword}
            autoComplete="off"
            onChange={() => {
              if (
                status === "passwordTooShort" ||
                status === "passwordsDontMatch"
              ) {
                setStatus(null);
              }
            }}
            helperText={(() => {
              if (status === "passwordTooShort") {
                return "Create a password at least 6 characters long.";
              }
              if (status === "passwordsDontMatch") {
                return "Your passwords dont match.";
              }
              return null;
            })()}
            FormHelperTextProps={{ error: true }}
            isVisible={isPasswordVisible}
            onVisibilityChange={setIsPasswordVisible}
          />
          <VisibilityPasswordTextField
            variant="outlined"
            margin="normal"
            required
            fullWidth
            error={
              status === "passwordTooShort" || status === "passwordsDontMatch"
            }
            label="Repeat Password"
            inputRef={registerPasswordRepeat}
            autoComplete="off"
            onChange={() => {
              if (
                status === "passwordTooShort" ||
                status === "passwordsDontMatch"
              ) {
                setStatus(null);
              }
            }}
            helperText={(() => {
              if (status === "passwordTooShort") {
                return "Create a password at least 6 characters long.";
              }
              if (status === "passwordsDontMatch") {
                return "Your passwords dont match.";
              }
            })()}
            FormHelperTextProps={{ error: true }}
            isVisible={isPasswordVisible}
            onVisibilityChange={setIsPasswordVisible}
          />
          <FormControlLabel
            style={{ marginRight: 0 }}
            control={
              <Checkbox
                color="primary"
                inputRef={registerTermsCheckbox}
                onChange={() => {
                  setHasTermsOfServiceError(false);
                }}
              />
            }
            label={
              <Typography variant="body1">
                I agree to the
                <span
                  className={classes.link}
                  onClick={isLoading ? null : openTermsDialog}
                  tabIndex={0}
                  role="button"
                  onKeyDown={(event) => {
                    // For screenreaders listen to space and enter events
                    if (
                      (!isLoading && event.keyCode === 13) ||
                      event.keyCode === 32
                    ) {
                      openTermsDialog();
                    }
                  }}
                >
                  {" "}
                  terms of service
                </span>
              </Typography>
            }
          />
          {hasTermsOfServiceError && (
            <FormHelperText
              error
              style={{
                display: "block",
                marginTop: theme.spacing(-1),
              }}
            >
              In order to create an account, you have to accept our terms of
              service.
            </FormHelperText>
          )}
          {status === "accountCreated" ? (
            <HighlightedInformation>
              We have created your account. Please click on the link in the
              email we have sent to you before logging in.
            </HighlightedInformation>
          ) : (
            <HighlightedInformation>
              Registration is disabled until we go live.
            </HighlightedInformation>
          )}
        </Fragment>
      }
      actions={
        <Button
          type="submit"
          fullWidth
          variant="contained"
          size="large"
          color="secondary"
          disabled={isLoading}
        >
          Register
          {isLoading && <ButtonCircularProgress />}
        </Button>
      }
    />
  );
}

RegisterDialog.propTypes = {
  theme: PropTypes.object.isRequired,
  onClose: PropTypes.func.isRequired,
  openTermsDialog: PropTypes.func.isRequired,
  status: PropTypes.string,
  setStatus: PropTypes.func.isRequired,
  classes: PropTypes.object.isRequired,
};

export default withStyles(styles, { withTheme: true })(RegisterDialog);



================================================
FILE: src/logged_out/components/register_login/TermsOfServiceDialog.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Dialog, DialogTitle, DialogContent, DialogActions, Typography } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import ArrowBackIcon from "@mui/icons-material/ArrowBack";
import ColoredButton from "../../../shared/components/ColoredButton";

const styles = theme => ({
  termsConditionsListitem: {
    marginLeft: theme.spacing(3),
    marginTop: theme.spacing(1)
  },
  dialogActions: {
    justifyContent: "flex-start",
    paddingTop: theme.spacing(2),
    paddingBottom: theme.spacing(2),
    paddingRight: theme.spacing(2)
  },
  backIcon: {
    marginRight: theme.spacing(1)
  }
});

function TermsOfServiceDialog(props) {
  const { classes, onClose, theme } = props;
  return (
    <Dialog open scroll="paper" onClose={onClose} hideBackdrop>
      <DialogTitle>Terms and Conditions</DialogTitle>
      <DialogContent>
        <Typography variant="h6" color="primary" paragraph>
          Introduction
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
          ipsum dolor sit amet.
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren.
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Intellectual Property Rights
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren,
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Restrictions
        </Typography>
        <Typography paragraph>
          You are specifically restricted from all of the following:
        </Typography>
        <Typography className={classes.termsConditionsListitem}>
          - Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography className={classes.termsConditionsListitem}>
          - Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography className={classes.termsConditionsListitem}>
          - Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography className={classes.termsConditionsListitem}>
          - Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography className={classes.termsConditionsListitem}>
          - Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua.
        </Typography>
        <Typography className={classes.termsConditionsListitem}>
          - Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography className={classes.termsConditionsListitem}>
          - Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography className={classes.termsConditionsListitem} paragraph>
          - Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren,
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Your Content
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          No warranties
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua.
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Limitation of liability
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Indemnification
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Severability
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua.
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Variation of Terms
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Assignment
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Entire Agreement
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
        <Typography variant="h6" color="primary" paragraph>
          Governing Law & Jurisdiction
        </Typography>
        <Typography paragraph>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
        </Typography>
      </DialogContent>
      <DialogActions className={classes.dialogActions}>
        <ColoredButton
          onClick={onClose}
          variant="contained"
          color={theme.palette.common.black}
        >
          <ArrowBackIcon className={classes.backIcon} />
          Back
        </ColoredButton>
      </DialogActions>
    </Dialog>
  );
}

TermsOfServiceDialog.propTypes = {
  classes: PropTypes.object.isRequired,
  onClose: PropTypes.func.isRequired,
  theme: PropTypes.object.isRequired
};

export default withStyles(styles, { withTheme: true })(TermsOfServiceDialog);



================================================
FILE: src/logged_out/dummy_data/blogPosts.js
================================================
import React, { Fragment } from "react";
import { Typography } from "@mui/material";

const content = (
  <Fragment>
    <Typography variant="h6" paragraph>
      Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
      eirmod tempor invidunt ut labore.
    </Typography>
    <Typography paragraph>
      Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
      eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
      voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
      clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit
      amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
      nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed
      diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
      Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor
      sit amet.
    </Typography>
    <Typography paragraph>
      Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
      eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
      voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
      clita kasd gubergren, no sea takimata sanctus est Lorem.
    </Typography>
    <Typography variant="h6" paragraph>
      Title
    </Typography>
    <Typography paragraph>
      Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
      eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
      voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
      clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit
      amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
      nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed
      diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
      Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor
      sit amet.
    </Typography>
    <Typography paragraph>
      Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
      eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
      voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
      clita kasd gubergren, no sea takimata sanctus est Lorem.
    </Typography>
    <Typography paragraph>
      Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
      eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
      voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
      clita kasd gubergren, no sea takimata sanctus est Lorem.
    </Typography>
    <Typography paragraph>
      Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
      eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
      voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
      clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit
      amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
      nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed
      diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
      Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor
      sit amet.
    </Typography>
    <Typography variant="h6" paragraph>
      Title
    </Typography>
    <Typography paragraph>
      Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
      eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
      voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
      clita kasd gubergren, no sea takimata sanctus est Lorem.
    </Typography>
    <Typography paragraph>
      Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy
      eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
      voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
      clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit
      amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
      nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed
      diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
      Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor
      sit amet.
    </Typography>
  </Fragment>
);

const posts = [
  {
    title: "Post 1",
    id: 1,
    date: 1576281600,
    src: `${process.env.PUBLIC_URL}/images/logged_out/blogPost1.jpg`,
    snippet:
      "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.",
    content: content,
  },
  {
    title: "Post 2",
    id: 2,
    date: 1576391600,
    src: `${process.env.PUBLIC_URL}/images/logged_out/blogPost2.jpg`,
    snippet:
      "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.",
    content: content,
  },
  {
    title: "Post 3",
    id: 3,
    date: 1577391600,
    src: `${process.env.PUBLIC_URL}/images/logged_out/blogPost3.jpg`,
    snippet:
      "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.",
    content: content,
  },
  {
    title: "Post 4",
    id: 4,
    date: 1572281600,
    src: `${process.env.PUBLIC_URL}/images/logged_out/blogPost4.jpg`,
    snippet:
      "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.",
    content: content,
  },
  {
    title: "Post 5",
    id: 5,
    date: 1573281600,
    src: `${process.env.PUBLIC_URL}/images/logged_out/blogPost5.jpg`,
    snippet:
      "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.",
    content: content,
  },
  {
    title: "Post 6",
    id: 6,
    date: 1575281600,
    src: `${process.env.PUBLIC_URL}/images/logged_out/blogPost6.jpg`,
    snippet:
      "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.",
    content: content,
  },
];

export default posts;


================================================
FILE: src/shared/components/ActionPaper.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Paper, DialogTitle, DialogContent, DialogActions, Box } from "@mui/material";

import withStyles from '@mui/styles/withStyles';

const styles = theme => ({
  helpPadding: {
    "@media (max-width:  400px)": {
      paddingLeft: theme.spacing(1),
      paddingRight: theme.spacing(1)
    }
  },
  fullWidth: {
    width: "100%"
  }
});

function ActionPaper(props) {
  const {
    theme,
    classes,
    title,
    content,
    maxWidth,
    actions,
    helpPadding,
    fullWidthActions
  } = props;
  return (
    <Box pt={1}>
      <Paper style={{ maxWidth: theme.breakpoints.values[maxWidth] }}>
        {title && <DialogTitle>{title}</DialogTitle>}
        {content && (
          <DialogContent
            classes={helpPadding ? { root: classes.helpPadding } : null}
          >
            {content}
          </DialogContent>
        )}
        {actions && (
          <Box pb={2} pr={2}>
            <DialogActions
              classes={{ action: fullWidthActions ? classes.fullWidth : null }}
            >
              {actions}
            </DialogActions>
          </Box>
        )}
      </Paper>
    </Box>
  );
}

ActionPaper.propTypes = {
  theme: PropTypes.object.isRequired,
  classes: PropTypes.object.isRequired,
  title: PropTypes.oneOfType([
    PropTypes.element,
    PropTypes.func,
    PropTypes.string
  ]),
  content: PropTypes.element,
  maxWidth: PropTypes.string,
  actions: PropTypes.element,
  helpPadding: PropTypes.bool,
  fullWidthActions: PropTypes.bool
};

export default withStyles(styles, { withTheme: true })(ActionPaper);



================================================
FILE: src/shared/components/Bordered.js
================================================
import React from "react";
import PropTypes from "prop-types";
import withStyles from '@mui/styles/withStyles';

const styles = theme => ({
  wrapper: {
    border: `${theme.border.borderWidth}px solid ${theme.border.borderColor}`
  },
  greyed: {
    border: `${theme.border.borderWidth}px solid rgba(0, 0, 0, 0.23)`
  }
});

function Bordered(props) {
  const {
    classes,
    theme,
    disableVerticalPadding,
    disableBorderRadius,
    children,
    variant
  } = props;
  return (
    <div
      className={variant === "greyed" ? classes.greyed : classes.wrapper}
      style={{
        paddingLeft: disableVerticalPadding ? 0 : theme.spacing(2),
        paddingRight: disableVerticalPadding ? 0 : theme.spacing(2),
        borderRadius: disableBorderRadius ? 0 : theme.shape.borderRadius
      }}
    >
      {children}
    </div>
  );
}

Bordered.propTypes = {
  classes: PropTypes.object,
  theme: PropTypes.object,
  disableVerticalPadding: PropTypes.bool,
  disableBorderRadius: PropTypes.bool,
  children: PropTypes.oneOfType([
    PropTypes.element,
    PropTypes.func,
    PropTypes.array
  ]),
  variant: PropTypes.string
};

export default withStyles(styles, { withTheme: true })(Bordered);



================================================
FILE: src/shared/components/ButtonCircularProgress.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { CircularProgress, Box } from "@mui/material";

import withStyles from '@mui/styles/withStyles';

const styles = theme => ({
  circularProgress: {
    color: theme.palette.secondary.main
  }
});

function ButtonCircularProgress(props) {
  const { size, classes } = props;
  return (
    <Box color="secondary.main" pl={1.5} display="flex">
      <CircularProgress
        size={size ? size : 24}
        thickness={size ? (size / 5) * 24 : 5}
        className={classes.circularProgress}
      />
    </Box>
  );
}

ButtonCircularProgress.propTypes = {
  size: PropTypes.number,
  classes: PropTypes.object.isRequired
};

export default withStyles(styles, { withTheme: true })(ButtonCircularProgress);



================================================
FILE: src/shared/components/CardChart.js
================================================
import React, { useState, useCallback } from "react";
import PropTypes from "prop-types";
import {
  AreaChart,
  Area,
  XAxis,
  Tooltip,
  ResponsiveContainer,
  YAxis,
} from "recharts";
import format from "date-fns/format";
import { Card, CardContent, Typography, IconButton, Menu, MenuItem, Box } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import MoreVertIcon from "@mui/icons-material/MoreVert";

const styles = (theme) => ({
  cardContentInner: {
    marginTop: theme.spacing(-4),
  },
});

function labelFormatter(label) {
  return format(new Date(label * 1000), "MMMM d, p yyyy");
}

function calculateMin(data, yKey, factor) {
  let max = Number.POSITIVE_INFINITY;
  data.forEach((element) => {
    if (max > element[yKey]) {
      max = element[yKey];
    }
  });
  return Math.round(max - max * factor);
}

const itemHeight = 216;
const options = ["1 Week", "1 Month", "6 Months"];

function CardChart(props) {
  const { color, data, title, classes, theme, height } = props;
  const [anchorEl, setAnchorEl] = useState(null);
  const [selectedOption, setSelectedOption] = useState("1 Month");

  const handleClick = useCallback(
    (event) => {
      setAnchorEl(event.currentTarget);
    },
    [setAnchorEl]
  );

  const formatter = useCallback(
    (value) => {
      return [value, title];
    },
    [title]
  );

  const getSubtitle = useCallback(() => {
    switch (selectedOption) {
      case "1 Week":
        return "Last week";
      case "1 Month":
        return "Last month";
      case "6 Months":
        return "Last 6 months";
      default:
        throw new Error("No branch selected in switch-statement");
    }
  }, [selectedOption]);

  const processData = useCallback(() => {
    let seconds;
    switch (selectedOption) {
      case "1 Week":
        seconds = 60 * 60 * 24 * 7;
        break;
      case "1 Month":
        seconds = 60 * 60 * 24 * 31;
        break;
      case "6 Months":
        seconds = 60 * 60 * 24 * 31 * 6;
        break;
      default:
        throw new Error("No branch selected in switch-statement");
    }
    const minSeconds = new Date() / 1000 - seconds;
    const arr = [];
    for (let i = 0; i < data.length; i += 1) {
      if (minSeconds < data[i].timestamp) {
        arr.unshift(data[i]);
      }
    }
    return arr;
  }, [data, selectedOption]);

  const handleClose = useCallback(() => {
    setAnchorEl(null);
  }, [setAnchorEl]);

  const selectOption = useCallback(
    (selectedOption) => {
      setSelectedOption(selectedOption);
      handleClose();
    },
    [setSelectedOption, handleClose]
  );

  const isOpen = Boolean(anchorEl);
  return (
    <Card>
      <Box pt={2} px={2} pb={4}>
        <Box display="flex" justifyContent="space-between">
          <div>
            <Typography variant="subtitle1">{title}</Typography>
            <Typography variant="body2" color="textSecondary">
              {getSubtitle()}
            </Typography>
          </div>
          <div>
            <IconButton
              aria-label="More"
              aria-owns={isOpen ? "long-menu" : undefined}
              aria-haspopup="true"
              onClick={handleClick}
              size="large">
              <MoreVertIcon />
            </IconButton>
            <Menu
              id="long-menu"
              anchorEl={anchorEl}
              open={isOpen}
              onClose={handleClose}
              PaperProps={{
                style: {
                  maxHeight: itemHeight,
                  width: 200,
                },
              }}
              disableScrollLock
            >
              {options.map((option) => (
                <MenuItem
                  key={option}
                  selected={option === selectedOption}
                  onClick={() => {
                    selectOption(option);
                  }}
                  name={option}
                >
                  {option}
                </MenuItem>
              ))}
            </Menu>
          </div>
        </Box>
      </Box>
      <CardContent>
        <Box className={classes.cardContentInner} height={height}>
          <ResponsiveContainer width="100%" height="100%">
            <AreaChart data={processData()} type="number">
              <XAxis
                dataKey="timestamp"
                type="number"
                domain={["dataMin", "dataMax"]}
                hide
              />
              <YAxis
                domain={[calculateMin(data, "value", 0.05), "dataMax"]}
                hide
              />
              <Area
                type="monotone"
                dataKey="value"
                stroke={color}
                fill={color}
              />
              <Tooltip
                labelFormatter={labelFormatter}
                formatter={formatter}
                cursor={false}
                contentStyle={{
                  border: "none",
                  padding: theme.spacing(1),
                  borderRadius: theme.shape.borderRadius,
                  boxShadow: theme.shadows[1],
                }}
                labelStyle={theme.typography.body1}
                itemStyle={{
                  fontSize: theme.typography.body1.fontSize,
                  letterSpacing: theme.typography.body1.letterSpacing,
                  fontFamily: theme.typography.body1.fontFamily,
                  lineHeight: theme.typography.body1.lineHeight,
                  fontWeight: theme.typography.body1.fontWeight,
                }}
              />
            </AreaChart>
          </ResponsiveContainer>
        </Box>
      </CardContent>
    </Card>
  );
}

CardChart.propTypes = {
  color: PropTypes.string.isRequired,
  data: PropTypes.array.isRequired,
  title: PropTypes.string.isRequired,
  classes: PropTypes.object.isRequired,
  theme: PropTypes.object.isRequired,
  height: PropTypes.string.isRequired,
};

export default withStyles(styles, { withTheme: true })(CardChart);



================================================
FILE: src/shared/components/ColoredButton.js
================================================
import React, { memo } from "react";
import PropTypes from "prop-types";
import { Button, createTheme, ThemeProvider, StyledEngineProvider, adaptV4Theme } from "@mui/material";

function ColoredButton(props) {
  const { color, children, theme } = props;
  const buttonTheme = createTheme(adaptV4Theme({
    ...theme,
    palette: {
      primary: {
        main: color
      }
    }
  }));
  const buttonProps = (({ color, theme, children, ...o }) => o)(props);
  return (
    <StyledEngineProvider injectFirst>
      <ThemeProvider theme={buttonTheme}>
        <Button {...buttonProps} color="primary">
          {children}
        </Button>
      </ThemeProvider>
    </StyledEngineProvider>
  );
}

ColoredButton.propTypes = {
  color: PropTypes.string.isRequired
};

export default memo(ColoredButton);



================================================
FILE: src/shared/components/ColorfulChip.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Chip } from "@mui/material";
import shadeColor from "../functions/shadeColor";

function ColorfulChip(props) {
  const { color, label, className } = props;
  return (
    <Chip
      style={{
        color: color,
        backgroundColor: shadeColor(color, 0.7)
      }}
      label={label}
      className={className ? className : null}
    />
  );
}

ColorfulChip.propTypes = {
  color: PropTypes.string.isRequired,
  label: PropTypes.string.isRequired,
  className: PropTypes.oneOfType([PropTypes.object, PropTypes.string])
};

export default ColorfulChip;



================================================
FILE: src/shared/components/ConfirmationDialog.js
================================================
import React from "react";
import PropTypes from "prop-types";
import {
  Dialog,
  DialogTitle,
  DialogContent,
  DialogContentText,
  DialogActions,
  Button
} from "@mui/material";
import ButtonCircularProgress from "./ButtonCircularProgress";

function ConfirmationDialog(props) {
  const { open, onClose, loading, title, content, onConfirm } = props;
  return (
    <Dialog open={open} onClose={onClose} disableEscapeKeyDown={loading}>
      <DialogTitle>{title}</DialogTitle>
      <DialogContent>
        <DialogContentText>{content}</DialogContentText>
      </DialogContent>
      <DialogActions>
        <Button onClick={onClose} disabled={loading}>
          Close
        </Button>
        <Button
          color="secondary"
          onClick={onConfirm}
          variant="contained"
          disabled={loading}
        >
          Yes {loading && <ButtonCircularProgress />}
        </Button>
      </DialogActions>
    </Dialog>
  );
}

ConfirmationDialog.propTypes = {
  open: PropTypes.bool,
  onClose: PropTypes.func,
  loading: PropTypes.bool,
  title: PropTypes.string,
  content: PropTypes.oneOfType([PropTypes.string, PropTypes.node]),
  onConfirm: PropTypes.func
};

export default ConfirmationDialog;



================================================
FILE: src/shared/components/ConsecutiveSnackbarMessages.js
================================================
import React, { useCallback, useState, useRef, useEffect } from "react";
import PropTypes from "prop-types";
import { Snackbar } from "@mui/material";

import withStyles from '@mui/styles/withStyles';

const styles = (theme) => ({
  root: {
    backgroundColor: theme.palette.primary.main,
    paddingTop: 0,
    paddingBottom: 0,
  },
});

function ConsecutiveSnackbars(props) {
  const { classes, getPushMessageFromChild } = props;
  const [isOpen, setIsOpen] = useState(false);
  const [messageInfo, setMessageInfo] = useState({});
  const queue = useRef([]);

  const processQueue = useCallback(() => {
    if (queue.current.length > 0) {
      setMessageInfo(queue.current.shift());
      setIsOpen(true);
    }
  }, [setMessageInfo, setIsOpen, queue]);

  const handleClose = useCallback((_, reason) => {
    if (reason === "clickaway") {
      return;
    }
    setIsOpen(false);
  }, [setIsOpen]);

  const pushMessage = useCallback(message => {
    queue.current.push({
      message,
      key: new Date().getTime(),
    });
    if (isOpen) {
      // immediately begin dismissing current message
      // to start showing new one
      setIsOpen(false);
    } else {
      processQueue();
    }
  }, [queue, isOpen, setIsOpen, processQueue]);

  useEffect(() => {
    getPushMessageFromChild(pushMessage);
  }, [getPushMessageFromChild, pushMessage]);

  return (
    <Snackbar
      disableWindowBlurListener
      key={messageInfo.key}
      anchorOrigin={{
        vertical: "bottom",
        horizontal: "left",
      }}
      open={isOpen}
      autoHideDuration={6000}
      onClose={handleClose}
      ContentProps={{
        classes: {
          root: classes.root,
        },
      }}
      message={
        <span>{messageInfo.message ? messageInfo.message.text : null}</span>
      }
      TransitionProps={{
        onExited: processQueue
      }} />
  );

}

ConsecutiveSnackbars.propTypes = {
  getPushMessageFromChild: PropTypes.func.isRequired,
  classes: PropTypes.object.isRequired,
};

export default withStyles(styles, { withTheme: true })(ConsecutiveSnackbars);



================================================
FILE: src/shared/components/DateTimePicker.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { TextField } from "@mui/material";
import MobileDatePicker from "@mui/lab/MobileDatePicker";
import AdapterDateFns from "@mui/lab/AdapterDateFns";
import LocalizationProvider from "@mui/lab/LocalizationProvider";
import {
  ThemeProvider,
  StyledEngineProvider,
  createTheme,
  adaptV4Theme,
} from "@mui/material";
import withTheme from "@mui/styles/withTheme";
import AccessTime from "@mui/icons-material/AccessTime";
import KeyboardArrowLeft from "@mui/icons-material/KeyboardArrowLeft";
import KeyboardArrowRight from "@mui/icons-material/KeyboardArrowRight";
import DateRange from "@mui/icons-material/DateRange";

const Theme2 = (theme) =>
  createTheme(
    adaptV4Theme({
      ...theme,
      overrides: {
        MuiOutlinedInput: {
          root: {
            width: 190,
            "@media (max-width:  400px)": {
              width: 160,
            },
            "@media (max-width:  360px)": {
              width: 140,
            },
            "@media (max-width:  340px)": {
              width: 120,
            },
          },
          input: {
            padding: "9px 14.5px",
          },
        },
      },
    })
  );

function DTPicker(props) {
  const { disabled, value, onChange } = props;
  return (
    <StyledEngineProvider injectFirst>
      <ThemeProvider theme={Theme2}>
        <LocalizationProvider dateAdapter={AdapterDateFns}>
          <MobileDatePicker
            inputVariant="outlined"
            leftArrowIcon={<KeyboardArrowLeft />}
            rightArrowIcon={<KeyboardArrowRight />}
            timeIcon={<AccessTime />}
            dateRangeIcon={<DateRange />}
            variant="outlined"
            disabled={disabled}
            value={value}
            onChange={onChange}
            renderInput={(params) => <TextField {...params} />}
            {...props}
          />
        </LocalizationProvider>
      </ThemeProvider>
    </StyledEngineProvider>
  );
}

DTPicker.propTypes = {
  disabled: PropTypes.bool,
  value: PropTypes.instanceOf(Date),
  onChange: PropTypes.func,
};

export default withTheme(DTPicker);



================================================
FILE: src/shared/components/DialogTitleWithCloseIcon.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { IconButton, DialogTitle, Typography, Box } from "@mui/material";
import withTheme from '@mui/styles/withTheme';
import CloseIcon from "@mui/icons-material/Close";

function DialogTitleWithCloseIcon(props) {
  const {
    theme,
    paddingBottom,
    onClose,
    disabled,
    title,
    disablePadding
  } = props;
  return (
    <DialogTitle
      style={{
        paddingBottom: paddingBottom
          ? paddingBottom && disablePadding
            ? 0
            : paddingBottom
          : theme.spacing(3),
        paddingLeft: disablePadding ? 0 : null,
        paddingRight: disablePadding ? 0 : null,
        paddingTop: disablePadding ? 0 : theme.spacing(2),
        width: "100%"
      }}>
      <Box display="flex" justifyContent="space-between">
        <Typography variant="h5">{title}</Typography>
        <IconButton
          onClick={onClose}
          style={{ marginRight: -12, marginTop: -10 }}
          disabled={disabled}
          aria-label="Close"
          size="large">
          <CloseIcon />
        </IconButton>
      </Box>
    </DialogTitle>
  );
}

DialogTitleWithCloseIcon.propTypes = {
  theme: PropTypes.object,
  paddingBottom: PropTypes.number,
  onClose: PropTypes.func,
  disabled: PropTypes.bool,
  title: PropTypes.string,
  disablePadding: PropTypes.bool
};

export default withTheme(DialogTitleWithCloseIcon);



================================================
FILE: src/shared/components/Dropzone.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { useDropzone } from "react-dropzone";
import classNames from "classnames";
import { Box } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import ColoredButton from "./ColoredButton";

const styles = {
  button: {
    borderWidth: 1,
    borderColor: "rgba(0, 0, 0, 0.23)",
    borderTopLeftRadius: 0,
    borderBottomLeftRadius: 0
  },
  fullHeight: {
    height: "100%"
  }
};

function getColor(isDragAccept, isDragReject, theme) {
  if (isDragAccept) {
    return theme.palette.success.main;
  }
  if (isDragReject) {
    return theme.palette.error.dark;
  }
  return theme.palette.common.black;
}

function Dropzone(props) {
  const { onDrop, accept, fullHeight, children, classes, style, theme } = props;
  const {
    getRootProps,
    getInputProps,
    isDragAccept,
    isDragReject
  } = useDropzone({
    accept: accept,
    onDrop: onDrop
  });
  return (
    <Box {...getRootProps()} height="100%">
      <input {...getInputProps()} />
      <ColoredButton
        fullWidth
        className={classNames(
          fullHeight ? classes.fullHeight : null,
          classes.button
        )}
        variant="outlined"
        color={getColor(isDragAccept, isDragReject, theme)}
        style={style}
      >
        {children}
      </ColoredButton>
    </Box>
  );
}

Dropzone.propTypes = {
  classes: PropTypes.object.isRequired,
  theme: PropTypes.object.isRequired,
  onDrop: PropTypes.func,
  accept: PropTypes.string,
  fullHeight: PropTypes.bool,
  style: PropTypes.object,
  children: PropTypes.oneOfType([PropTypes.element, PropTypes.func])
};

export default withStyles(styles, { withTheme: true })(Dropzone);



================================================
FILE: src/shared/components/EmojiTextArea.js
================================================
import React, { Fragment, useState, useCallback } from "react";
import PropTypes from "prop-types";
import "emoji-mart/css/emoji-mart.css";
import { Picker } from "emoji-mart";
import { TextField, IconButton, Collapse, FormHelperText, Box, Grid } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import EmojiEmotionsIcon from "@mui/icons-material/EmojiEmotions";
import CloseIcon from "@mui/icons-material/Close";
import countWithEmojis from "../functions/countWithEmojis";

const styles = theme => ({
  "@global": {
    ".emoji-mart-category-label": theme.typography.body1,
    ".emoji-mart-bar": { display: "none !important" },
    ".emoji-mart-search input": {
      ...theme.typography.body1,
      ...theme.border
    },
    ".emoji-mart-search": {
      marginTop: `${theme.spacing(1)} !important`,
      paddingRight: `${theme.spacing(1)} !important`,
      paddingLeft: `${theme.spacing(1)} !important`,
      paddingBottom: `${theme.spacing(1)} !important`
    },
    ".emoji-mart-search-icon": {
      top: "5px !important",
      right: "14px !important",
      fontSize: 20
    },
    ".emoji-mart-scroll": {
      height: 240
    },
    ".emoji-mart": {
      ...theme.border
    }
  },
  floatButtonWrapper: {
    position: "absolute",
    bottom: 12,
    right: 12
  },
  floatButtonSVG: {
    color: theme.palette.primary.light
  },
  relative: {
    position: "relative"
  }
});

/**
 * Emojis whose unified is greater than 5 sometimes
 * are not displayed correcty in the browser.
 * We won't display them.
 */
const emojisToShowFilter = emoji => {
  if (emoji.unified.length > 5) {
    return false;
  }
  return true;
};

function EmojiTextarea(props) {
  const {
    theme,
    classes,
    rightContent,
    placeholder,
    maxCharacters,
    emojiSet,
    inputClassName,
    onChange
  } = props;
  const [open, setOpen] = useState(false);
  const [value, setValue] = useState("");
  const [characters, setCharacters] = useState(0);

  const onSelectEmoji = useCallback(
    emoji => {
      let _characters;
      let _value = value + emoji.native;
      if (maxCharacters) {
        _characters = countWithEmojis(_value);
        if (_characters > maxCharacters) {
          return;
        }
      }
      if (onChange) {
        onChange(_value, _characters);
      }
      setValue(_value);
      setCharacters(_characters);
    },
    [value, setValue, setCharacters, maxCharacters, onChange]
  );

  const handleTextFieldChange = useCallback(
    event => {
      const { target } = event;
      const { value } = target;
      let characters;
      if (maxCharacters) {
        characters = countWithEmojis(value);
        if (characters > maxCharacters) {
          return;
        }
      }
      if (onChange) {
        onChange(value, characters);
      }
      setValue(value);
      setCharacters(characters);
    },
    [maxCharacters, onChange, setValue, setCharacters]
  );

  const toggleOpen = useCallback(() => {
    setOpen(!open);
  }, [open, setOpen]);

  return (
    <Fragment>
      <Grid spacing={0} container>
        <Grid
          item
          xs={rightContent ? 8 : 12}
          sm={rightContent ? 9 : 12}
          lg={rightContent ? 10 : 12}
          className={classes.relative}
        >
          <TextField
            fullWidth
            multiline
            variant="outlined"
            rows={6}
            onInput={handleTextFieldChange}
            value={value}
            placeholder={placeholder}
            InputProps={{
              classes: {
                notchedOutline: inputClassName ? inputClassName : null
              }
            }}
          />
          <div className={classes.floatButtonWrapper}>
            <IconButton onClick={toggleOpen} size="large">
              {open ? (
                <CloseIcon color="primary" />
              ) : (
                <EmojiEmotionsIcon color="primary" />
              )}
            </IconButton>
          </div>
        </Grid>
        {rightContent && (
          <Grid item xs={4} sm={3} lg={2}>
            {rightContent}
          </Grid>
        )}
      </Grid>
      {maxCharacters && (
        <FormHelperText error={characters >= maxCharacters}>
          {`${characters}/${maxCharacters} characters`}
        </FormHelperText>
      )}
      <Collapse in={open}>
        <Box mt={1}>
          <Picker
            set={emojiSet}
            color={theme.palette.primary.main}
            style={{ width: "100%" }}
            onSelect={onSelectEmoji}
            emojisToShowFilter={emojisToShowFilter}
          />
        </Box>
      </Collapse>
    </Fragment>
  );
}

EmojiTextarea.propTypes = {
  theme: PropTypes.object.isRequired,
  classes: PropTypes.object.isRequired,
  emojiSet: PropTypes.string.isRequired,
  rightContent: PropTypes.element,
  placeholder: PropTypes.string,
  maxCharacters: PropTypes.number,
  onChange: PropTypes.func,
  inputClassName: PropTypes.string
};

export default withStyles(styles, { withTheme: true })(EmojiTextarea);



================================================
FILE: src/shared/components/EnhancedTableHead.js
================================================
import React, { useCallback } from "react";
import PropTypes from "prop-types";
import classNames from "classnames";
import { Typography, TableCell, TableHead, TableRow, TableSortLabel, Tooltip } from "@mui/material";

import withStyles from '@mui/styles/withStyles';

const styles = theme => ({
  tableSortLabel: {
    cursor: "text",
    userSelect: "auto",
    color: "inherit !important"
  },
  noIcon: {
    "& path": {
      display: "none !important"
    }
  },
  paddingFix: {
    paddingLeft: theme.spacing(3)
  }
});

function EnhancedTableHead(props) {
  const { order, orderBy, rows, onRequestSort, classes } = props;

  const createSortHandler = useCallback(
    property => event => {
      onRequestSort(event, property);
    },
    [onRequestSort]
  );

  return (
    <TableHead>
      <TableRow>
        {rows.map((row, index) => (
          <TableCell
            key={index}
            align={row.numeric ? "right" : "inherit"}
            padding="normal"
            sortDirection={orderBy === row.name ? order : false}
            className={index === 0 ? classes.paddingFix : null}
          >
            {onRequestSort ? (
              <Tooltip
                title="Sort"
                placement={row.numeric ? "bottom-end" : "bottom-start"}
                enterDelay={300}
              >
                <TableSortLabel
                  active={orderBy === row.id}
                  direction={order}
                  onClick={createSortHandler(row.id)}
                >
                  <Typography variant="body2">{row.label}</Typography>
                </TableSortLabel>
              </Tooltip>
            ) : (
              <TableSortLabel
                className={classNames(classes.tableSortLabel, classes.noIcon)}
              >
                <Typography variant="body2" className={classes.label}>
                  {row.label}
                </Typography>
              </TableSortLabel>
            )}
          </TableCell>
        ))}
      </TableRow>
    </TableHead>
  );
}
EnhancedTableHead.propTypes = {
  classes: PropTypes.object.isRequired,
  theme: PropTypes.object.isRequired,
  onRequestSort: PropTypes.func,
  order: PropTypes.string,
  orderBy: PropTypes.string,
  rows: PropTypes.arrayOf(PropTypes.object).isRequired
};

export default withStyles(styles, { withTheme: true })(EnhancedTableHead);



================================================
FILE: src/shared/components/FormDialog.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Dialog, DialogContent, Box } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import DialogTitleWithCloseIcon from "./DialogTitleWithCloseIcon";

const styles = theme => ({
  dialogPaper: {
    display: "flex",
    flexDirection: "column",
    alignItems: "center",
    paddingBottom: theme.spacing(3),
    maxWidth: 420
  },
  actions: {
    marginTop: theme.spacing(2)
  },
  dialogPaperScrollPaper: {
    maxHeight: "none"
  },
  dialogContent: {
    paddingTop: 0,
    paddingBottom: 0
  }
});

/**
 * A Wrapper around the Dialog component to create centered
 * Login, Register or other Dialogs.
 */
function FormDialog(props) {
  const {
    classes,
    open,
    onClose,
    loading,
    headline,
    onFormSubmit,
    content,
    actions,
    hideBackdrop
  } = props;
  return (
    <Dialog
      open={open}
      onClose={onClose}
      disableEscapeKeyDown={loading}
      classes={{
        paper: classes.dialogPaper,
        paperScrollPaper: classes.dialogPaperScrollPaper
      }}
      hideBackdrop={hideBackdrop ? hideBackdrop : false}>
      <DialogTitleWithCloseIcon
        title={headline}
        onClose={onClose}
        disabled={loading}
      />
      <DialogContent className={classes.dialogContent}>
        <form onSubmit={onFormSubmit}>
          <div>{content}</div>
          <Box width="100%" className={classes.actions}>
            {actions}
          </Box>
        </form>
      </DialogContent>
    </Dialog>
  );
}

FormDialog.propTypes = {
  classes: PropTypes.object.isRequired,
  open: PropTypes.bool.isRequired,
  onClose: PropTypes.func.isRequired,
  headline: PropTypes.string.isRequired,
  loading: PropTypes.bool.isRequired,
  onFormSubmit: PropTypes.func.isRequired,
  content: PropTypes.element.isRequired,
  actions: PropTypes.element.isRequired,
  hideBackdrop: PropTypes.bool.isRequired
};

export default withStyles(styles, { withTheme: true })(FormDialog);



================================================
FILE: src/shared/components/HelpIcon.js
================================================
import React, { useState, useCallback } from "react";
import PropTypes from "prop-types";
import { Tooltip, Typography } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import HelpIconOutline from "@mui/icons-material/HelpOutline";

const styles = theme => ({
  tooltipTypo: {
    whiteSpace: "pre-line !important",
    ...theme.typography.caption,
    color: theme.palette.common.white
  },
  tooltip: {
    verticalAlign: "middle",
    fontSize: "1.25rem"
  },
  helpIcon: {
    marginLeft: theme.spacing(1),
    "@media (max-width: 350px)": {
      marginLeft: theme.spacing(0.5)
    },
    transition: theme.transitions.create(["color"], {
      duration: theme.transitions.duration.short,
      easing: theme.transitions.easing.easeInOut
    })
  }
});

function HelpIcon(props) {
  const { classes, title } = props;
  const [isHovered, setIsHovered] = useState(false);

  const onMouseOver = useCallback(() => {
    setIsHovered(true);
  }, []);

  const onMouseLeave = useCallback(() => {
    setIsHovered(false);
  }, []);

  return (
    <Tooltip
      title={
        <Typography variant="body2" className={classes.tooltipTypo}>
          {title}
        </Typography>
      }
      className={classes.tooltip}
      enterTouchDelay={300}
    >
      <HelpIconOutline
        /**
         * We have to use onMouseOver and not onMouseEnter, because if we have overlapping
         * tooltips, the onMouseEnter wont fire when the old tooltip is fading
         * */
        onMouseOver={onMouseOver}
        onFocus={onMouseOver}
        onBlur={onMouseLeave}
        onMouseLeave={onMouseLeave}
        color={isHovered ? "primary" : "inherit"}
        className={classes.helpIcon}
        style={{ cursor: isHovered ? "pointer" : "auto" }}
      />
    </Tooltip>
  );
}

HelpIcon.propTypes = {
  classes: PropTypes.object,
  title: PropTypes.oneOfType([PropTypes.string, PropTypes.node])
};

export default withStyles(styles, { withTheme: true })(HelpIcon);



================================================
FILE: src/shared/components/HighlightedInformation.js
================================================
import React from "react";
import PropTypes from "prop-types";
import classNames from "classnames";
import { Typography } from "@mui/material";

import withStyles from '@mui/styles/withStyles';

const styles = theme => ({
  main: {
    backgroundColor: theme.palette.warning.light,
    border: `${theme.border.borderWidth}px solid ${theme.palette.warning.main}`,
    padding: theme.spacing(2),
    borderRadius: theme.shape.borderRadius
  }
});

function HighlighedInformation(props) {
  const { className, children, classes } = props;
  return (
    <div className={classNames(classes.main, className ? className : null)}>
      <Typography variant="body2">{children}</Typography>
    </div>
  );
}

HighlighedInformation.propTypes = {
  classes: PropTypes.object.isRequired,
  children: PropTypes.oneOfType([
    PropTypes.string,
    PropTypes.element,
    PropTypes.array
  ]).isRequired,
  className: PropTypes.string
};

export default withStyles(styles, { withTheme: true })(HighlighedInformation);



================================================
FILE: src/shared/components/ImageCropper.js
================================================
import React, { useRef, useCallback, useEffect } from "react";
import PropTypes from "prop-types";
import Cropper from "react-cropper";
import withStyles from '@mui/styles/withStyles';
import shadeColor from "../functions/shadeColor";

const styles = {
  cropperWrapper: {
    "& img": {
      height: "auto",
      width: "100%",
      maxWidth: "100%",
    },
  },
  "@global": {
    ".cropper-container": {
      direction: "ltr",
      fontSize: "0",
      lineHeight: "0",
      position: "relative",
      M: "none",
      touchAction: "none",
      W: "none",
      fallbacks: [
        {
          M: "none",
        },
        {
          M: "none",
        },
      ],
      userSelect: "none",
    },
    ".cropper-container img": {
      display: "block",
      height: "100%",
      imageOrientation: "0deg",
      maxHeight: "none !important",
      maxWidth: "none !important",
      minHeight: "0 !important",
      minWidth: "0 !important",
      width: "100%",
    },
    ".cropper-wrap-box, .cropper-canvas, .cropper-drag-box, .cropper-crop-box, .cropper-modal": {
      bottom: "0",
      left: "0",
      position: "absolute",
      right: "0",
      top: "0",
    },
    ".cropper-wrap-box, .cropper-canvas": {
      overflow: "hidden",
    },
    ".cropper-drag-box": {
      backgroundColor: "#fff",
      opacity: "0",
    },
    ".cropper-modal": {
      backgroundColor: "#000",
      opacity: "0.5",
    },
    ".cropper-view-box": {
      display: "block",
      height: "100%",
      outline: (props) => `1px solid ${props.color}`,
      outlineColor: (props) => `1px solid ${shadeColor(props.color, 0.75)}`,
      overflow: "hidden",
      width: "100%",
    },
    ".cropper-dashed": {
      border: "0 dashed #eee",
      display: "block",
      opacity: "0.5",
      position: "absolute",
    },
    ".cropper-dashed.dashed-h": {
      borderBottomWidth: 1,
      borderTopWidth: 1,
      height: "calc(100% / 3)",
      left: "0",
      top: "calc(100% / 3)",
      width: "100%",
    },
    ".cropper-dashed.dashed-v": {
      borderLeftWidth: 1,
      borderRightWidth: 1,
      height: "100%",
      left: "calc(100% / 3)",
      top: "0",
      width: "calc(100% / 3)",
    },
    ".cropper-center": {
      display: "block",
      height: "0",
      left: "50%",
      opacity: "0.75",
      position: "absolute",
      top: "50%",
      width: "0",
    },
    ".cropper-center::before, .cropper-center::after": {
      backgroundColor: "#eee",
      content: "' '",
      display: "block",
      position: "absolute",
    },
    ".cropper-center::before": {
      height: 1,
      left: -3,
      top: "0",
      width: 7,
    },
    ".cropper-center::after": {
      height: 7,
      left: "0",
      top: -3,
      width: 1,
    },
    ".cropper-face, .cropper-line, .cropper-point": {
      display: "block",
      height: "100%",
      opacity: "0.1",
      position: "absolute",
      width: "100%",
    },
    ".cropper-face": {
      backgroundColor: "#fff",
      left: "0",
      top: "0",
    },
    ".cropper-line": {
      backgroundColor: (props) => props.color,
    },
    ".cropper-line.line-e": {
      cursor: "ew-resize",
      right: -3,
      top: "0",
      width: 5,
    },
    ".cropper-line.line-n": {
      cursor: "ns-resize",
      height: 5,
      left: "0",
      top: -3,
    },
    ".cropper-line.line-w": {
      cursor: "ew-resize",
      left: -3,
      top: "0",
      width: 5,
    },
    ".cropper-line.line-s": {
      bottom: -3,
      cursor: "ns-resize",
      height: 5,
      left: "0",
    },
    ".cropper-point": {
      backgroundColor: (props) => props.color,
      height: 5,
      opacity: "0.75",
      width: 5,
    },
    ".cropper-point.point-e": {
      cursor: "ew-resize",
      marginTop: -3,
      right: -3,
      top: "50%",
    },
    ".cropper-point.point-n": {
      cursor: "ns-resize",
      left: "50%",
      marginLeft: -3,
      top: -3,
    },
    ".cropper-point.point-w": {
      cursor: "ew-resize",
      left: -3,
      marginTop: -3,
      top: "50%",
    },
    ".cropper-point.point-s": {
      bottom: -3,
      cursor: "s-resize",
      left: "50%",
      marginLeft: -3,
    },
    ".cropper-point.point-ne": {
      cursor: "nesw-resize",
      right: -3,
      top: -3,
    },
    ".cropper-point.point-nw": {
      cursor: "nwse-resize",
      left: -3,
      top: -3,
    },
    ".cropper-point.point-sw": {
      bottom: -3,
      cursor: "nesw-resize",
      left: -3,
    },
    ".cropper-point.point-se": {
      bottom: -3,
      cursor: "nwse-resize",
      height: 20,
      opacity: "1",
      right: -3,
      width: 20,
    },
    "@media (min-width: 768px)": {
      ".cropper-point.point-se": {
        height: 15,
        width: 15,
      },
    },
    "@media (min-width: 992px)": {
      ".cropper-point.point-se": {
        height: 10,
        width: 10,
      },
    },
    "@media (min-width: 1200px)": {
      ".cropper-point.point-se": {
        height: 5,
        opacity: "0.75",
        width: 5,
      },
    },
    ".cropper-point.point-se::before": {
      backgroundColor: (props) => props.color,
      bottom: "-50%",
      content: "' '",
      display: "block",
      height: "200%",
      opacity: "0",
      position: "absolute",
      right: "-50%",
      width: "200%",
    },
    ".cropper-invisible": {
      opacity: "0",
    },
    ".cropper-bg": {
      backgroundImage:
        "url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQAQMAAAAlPW0iAAAAA3NCSVQICAjb4U/gAAAABlBMVEXMzMz////TjRV2AAAACXBIWXMAAArrAAAK6wGCiw1aAAAAHHRFWHRTb2Z0d2FyZQBBZG9iZSBGaXJld29ya3MgQ1M26LyyjAAAABFJREFUCJlj+M/AgBVhF/0PAH6/D/HkDxOGAAAAAElFTkSuQmCC')",
    },
    ".cropper-hide": {
      display: "block",
      height: "0",
      position: "absolute",
      width: "0",
    },
    ".cropper-hidden": {
      display: "none !important",
    },
    ".cropper-move": {
      cursor: "move",
    },
    ".cropper-crop": {
      cursor: "crosshair",
    },
    ".cropper-disabled .cropper-drag-box, .cropper-disabled .cropper-face, .cropper-disabled .cropper-line, .cropper-disabled .cropper-point": {
      cursor: "not-allowed",
    },
  },
};

function ImageCropper(props) {
  const { onCrop, classes, src, aspectRatio, setCropFunction } = props;
  const cropper = useRef();

  const crop = useCallback(() => {
    onCrop(cropper.current.getCroppedCanvas().toDataURL());
  }, [onCrop, cropper]);

  useEffect(() => {
    setCropFunction(crop);
  }, [setCropFunction, crop]);

  return (
    <div className={classes.cropperWrapper}>
      <Cropper
        onInitialized={(cr) => (cropper.current = cr)}
        src={src}
        guides={false}
        zoomable={false}
        viewMode={3}
        aspectRatio={aspectRatio}
        cropmove={
          aspectRatio
            ? null
            : () => {
                const cropBoxData = cropper.current.getCropBoxData();
                const cropBoxWidth = cropBoxData.width;
                const aspRatio = cropBoxWidth / cropBoxData.height;
                if (aspRatio < 1) {
                  cropper.current.setCropBoxData({
                    height: cropBoxWidth / 1,
                  });
                } else if (aspRatio > 16 / 9) {
                  cropper.current.setCropBoxData({
                    height: cropBoxWidth / (16 / 9),
                  });
                }
              }
        }
      />
    </div>
  );
}

ImageCropper.propTypes = {
  classes: PropTypes.object.isRequired,
  color: PropTypes.string.isRequired,
  src: PropTypes.string,
  onCrop: PropTypes.func,
  setCropFunction: PropTypes.func,
  aspectRatio: PropTypes.number,
};

export default withStyles(styles)(ImageCropper);



================================================
FILE: src/shared/components/ImageCropperDialog.js
================================================
import React, { useState, useCallback } from "react";
import PropTypes from "prop-types";
import { Dialog, DialogContent, DialogActions, Button, Box } from "@mui/material";

import withStyles from '@mui/styles/withStyles';

const styles = (theme) => ({
  dialogPaper: { maxWidth: `${theme.breakpoints.values.md}px !important` },
  dialogContent: {
    paddingTop: theme.spacing(2),
    paddingRight: theme.spacing(2),
    paddingLeft: theme.spacing(2),
  },
});

function ImageCropperDialog(props) {
  const {
    ImageCropper,
    classes,
    onClose,
    open,
    src,
    onCrop,
    aspectRatio,
    theme,
  } = props;
  const [crop, setCrop] = useState(null);

  const getCropFunctionFromChild = useCallback(
    (cropFunction) => {
      setCrop(() => cropFunction);
    },
    [setCrop]
  );

  return (
    <Dialog
      open={open}
      onEscapeKeyDown={onClose}
      classes={{ paper: classes.dialogPaper }}
      style={{ overflowX: "visible" }}
    >
      <DialogContent className={classes.dialogContent}>
        <ImageCropper
          src={src}
          setCropFunction={getCropFunctionFromChild}
          onCrop={onCrop}
          aspectRatio={aspectRatio}
          color={theme.palette.primary.main}
        />
      </DialogContent>
      <DialogActions>
        <Box mr={1}>
          <Button onClick={onClose}>Close</Button>
        </Box>
        <Button variant="contained" color="secondary" onClick={crop}>
          Crop
        </Button>
      </DialogActions>
    </Dialog>
  );
}

ImageCropperDialog.propTypes = {
  ImageCropper: PropTypes.elementType,
  classes: PropTypes.object.isRequired,
  onClose: PropTypes.func.isRequired,
  open: PropTypes.bool.isRequired,
  onCrop: PropTypes.func.isRequired,
  src: PropTypes.string,
  aspectRatio: PropTypes.number,
};

export default withStyles(styles, { withTheme: true })(ImageCropperDialog);



================================================
FILE: src/shared/components/ModalBackdrop.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Backdrop } from "@mui/material";

import withStyles from '@mui/styles/withStyles';

const styles = {
  backdrop: {
    top: 0,
    left: 0,
    right: 0,
    bottom: 0,
    zIndex: 1200,
    position: "fixed",
    touchAction: "none",
    backgroundColor: "rgba(0, 0, 0, 0.5)"
  }
};

function ModalBackdrop(props) {
  const { classes, open } = props;
  return <Backdrop open={open} className={classes.backdrop} />;
}

ModalBackdrop.propTypes = {
  classes: PropTypes.object.isRequired,
  open: PropTypes.bool.isRequired
};

export default withStyles(styles)(ModalBackdrop);



================================================
FILE: src/shared/components/NavigationDrawer.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Link } from "react-router-dom";
import {
  List,
  ListItem,
  ListItemIcon,
  ListItemText,
  Drawer,
  IconButton,
  Typography,
  Toolbar,
} from "@mui/material";
import withStyles from "@mui/styles/withStyles";
import CloseIcon from "@mui/icons-material/Close";
import useMediaQuery from "@mui/material/useMediaQuery";

const styles = (theme) => ({
  closeIcon: {
    marginRight: theme.spacing(0.5),
  },
  headSection: {
    width: 200,
  },
  blackList: {
    backgroundColor: theme.palette.common.black,
    height: "100%",
  },
  noDecoration: {
    textDecoration: "none !important",
  },
});

function NavigationDrawer(props) {
  const { open, onClose, anchor, classes, menuItems, selectedItem, theme } =
    props;
  const isWidthUpSm = useMediaQuery(theme.breakpoints.up("sm"));

  window.onresize = () => {
    if (isWidthUpSm && open) {
      onClose();
    }
  };

  return (
    <Drawer variant="temporary" open={open} onClose={onClose} anchor={anchor}>
      <Toolbar className={classes.headSection}>
        <ListItem
          style={{
            paddingTop: theme.spacing(0),
            paddingBottom: theme.spacing(0),
            height: "100%",
            justifyContent: anchor === "left" ? "flex-start" : "flex-end",
          }}
          disableGutters
        >
          <ListItemIcon className={classes.closeIcon}>
            <IconButton
              onClick={onClose}
              aria-label="Close Navigation"
              size="large"
            >
              <CloseIcon color="primary" />
            </IconButton>
          </ListItemIcon>
        </ListItem>
      </Toolbar>
      <List className={classes.blackList}>
        {menuItems.map((element) => {
          if (element.link) {
            return (
              <Link
                key={element.name}
                to={element.link}
                className={classes.noDecoration}
                onClick={onClose}
              >
                <ListItem
                  button
                  selected={selectedItem === element.name}
                  /**
                   * We disable ripple as it will make a weird animation
                   * with primary and secondary color
                   */
                  disableRipple
                  disableTouchRipple
                >
                  <ListItemIcon>{element.icon}</ListItemIcon>
                  <ListItemText
                    primary={
                      <Typography variant="subtitle1" className="text-white">
                        {element.name}
                      </Typography>
                    }
                  />
                </ListItem>
              </Link>
            );
          }
          return (
            <ListItem button key={element.name} onClick={element.onClick}>
              <ListItemIcon>{element.icon}</ListItemIcon>
              <ListItemText
                primary={
                  <Typography variant="subtitle1" className="text-white">
                    {element.name}
                  </Typography>
                }
              />
            </ListItem>
          );
        })}
      </List>
    </Drawer>
  );
}

NavigationDrawer.propTypes = {
  anchor: PropTypes.string.isRequired,
  theme: PropTypes.object.isRequired,
  open: PropTypes.bool.isRequired,
  onClose: PropTypes.func.isRequired,
  menuItems: PropTypes.arrayOf(PropTypes.object).isRequired,
  classes: PropTypes.object.isRequired,
  selectedItem: PropTypes.string,
};

export default withStyles(styles, { withTheme: true })(NavigationDrawer);



================================================
FILE: src/shared/components/Pace.js
================================================
import PropTypes from "prop-types";
import withStyles from '@mui/styles/withStyles';

const styles = {
  "@global": {
    ".pace": {
      pointerEvents: "none",
      userSelect: "none"
    },
    ".pace-inactive": {
      display: "none"
    },
    ".pace .pace-progress": {
      background: props => props.color || null,
      position: "fixed",
      zIndex: 2000,
      top: 0,
      right: "100%",
      width: "100%",
      height: 3
    }
  }
};

function Pace() {
  activatePace.call(this);
  return null;
}

Pace.propTypes = {
  color: PropTypes.string.isRequired
};

export default withStyles(styles)(Pace);

/* eslint-disable */

/**
 * Pace has defaultly only GET requests enabled. Enable for Post requets too.
 */
window.paceOptions = {
  ajax: {
    trackMethods: ["GET", "POST"]
  }
};

/*! pace 1.0.0 */
function activatePace() {
  var a,
    b,
    c,
    d,
    e,
    f,
    g,
    h,
    i,
    j,
    k,
    l,
    m,
    n,
    o,
    p,
    q,
    r,
    s,
    t,
    u,
    v,
    w,
    x,
    y,
    z,
    A,
    B,
    C,
    D,
    E,
    F,
    G,
    H,
    I,
    J,
    K,
    L,
    M,
    N,
    O,
    P,
    Q,
    R,
    S,
    T,
    U,
    V,
    W,
    X = [].slice,
    Y = {}.hasOwnProperty,
    Z = function(a, b) {
      function c() {
        this.constructor = a;
      }
      for (var d in b) Y.call(b, d) && (a[d] = b[d]);
      return (
        (c.prototype = b.prototype),
        (a.prototype = new c()),
        (a.__super__ = b.prototype),
        a
      );
    },
    $ =
      [].indexOf ||
      function(a) {
        for (var b = 0, c = this.length; c > b; b++)
          if (b in this && this[b] === a) return b;
        return -1;
      };
  for (
    u = {
      catchupTime: 100,
      initialRate: 0.03,
      minTime: 250,
      ghostTime: 100,
      maxProgressPerFrame: 20,
      easeFactor: 1.25,
      startOnPageLoad: !0,
      restartOnPushState: !0,
      restartOnRequestAfter: 500,
      target: "body",
      elements: { checkInterval: 100, selectors: ["body"] },
      eventLag: { minSamples: 10, sampleCount: 3, lagThreshold: 3 },
      ajax: { trackMethods: ["GET"], trackWebSockets: !0, ignoreURLs: [] }
    },
      C = function() {
        var a;
        return null !=
          (a =
            "undefined" != typeof performance &&
            null !== performance &&
            "function" == typeof performance.now
              ? performance.now()
              : void 0)
          ? a
          : +new Date();
      },
      E =
        window.requestAnimationFrame ||
        window.mozRequestAnimationFrame ||
        window.webkitRequestAnimationFrame ||
        window.msRequestAnimationFrame,
      t = window.cancelAnimationFrame || window.mozCancelAnimationFrame,
      null == E &&
        ((E = function(a) {
          return setTimeout(a, 50);
        }),
        (t = function(a) {
          return clearTimeout(a);
        })),
      G = function(a) {
        var b, c;
        return (
          (b = C()),
          (c = function() {
            var d;
            return (
              (d = C() - b),
              d >= 33
                ? ((b = C()),
                  a(d, function() {
                    return E(c);
                  }))
                : setTimeout(c, 33 - d)
            );
          })()
        );
      },
      F = function() {
        var a, b, c;
        return (
          (c = arguments[0]),
          (b = arguments[1]),
          (a = 3 <= arguments.length ? X.call(arguments, 2) : []),
          "function" == typeof c[b] ? c[b].apply(c, a) : c[b]
        );
      },
      v = function() {
        var a, b, c, d, e, f, g;
        for (
          b = arguments[0],
            d = 2 <= arguments.length ? X.call(arguments, 1) : [],
            f = 0,
            g = d.length;
          g > f;
          f++
        )
          if ((c = d[f]))
            for (a in c)
              Y.call(c, a) &&
                ((e = c[a]),
                null != b[a] &&
                "object" == typeof b[a] &&
                null != e &&
                "object" == typeof e
                  ? v(b[a], e)
                  : (b[a] = e));
        return b;
      },
      q = function(a) {
        var b, c, d, e, f;
        for (c = b = 0, e = 0, f = a.length; f > e; e++)
          (d = a[e]), (c += Math.abs(d)), b++;
        return c / b;
      },
      x = function(a, b) {
        var c, d, e;
        if (
          (null == a && (a = "options"),
          null == b && (b = !0),
          (e = document.querySelector("[data-pace-" + a + "]")))
        ) {
          if (((c = e.getAttribute("data-pace-" + a)), !b)) return c;
          try {
            return JSON.parse(c);
          } catch (f) {
            return (
              (d = f),
              "undefined" != typeof console && null !== console
                ? console.error("Error parsing inline pace options", d)
                : void 0
            );
          }
        }
      },
      g = (function() {
        function a() {}
        return (
          (a.prototype.on = function(a, b, c, d) {
            var e;
            return (
              null == d && (d = !1),
              null == this.bindings && (this.bindings = {}),
              null == (e = this.bindings)[a] && (e[a] = []),
              this.bindings[a].push({ handler: b, ctx: c, once: d })
            );
          }),
          (a.prototype.once = function(a, b, c) {
            return this.on(a, b, c, !0);
          }),
          (a.prototype.off = function(a, b) {
            var c, d, e;
            if (null != (null != (d = this.bindings) ? d[a] : void 0)) {
              if (null == b) return delete this.bindings[a];
              for (c = 0, e = []; c < this.bindings[a].length; )
                e.push(
                  this.bindings[a][c].handler === b
                    ? this.bindings[a].splice(c, 1)
                    : c++
                );
              return e;
            }
          }),
          (a.prototype.trigger = function() {
            var a, b, c, d, e, f, g, h, i;
            if (
              ((c = arguments[0]),
              (a = 2 <= arguments.length ? X.call(arguments, 1) : []),
              null != (g = this.bindings) ? g[c] : void 0)
            ) {
              for (e = 0, i = []; e < this.bindings[c].length; )
                (h = this.bindings[c][e]),
                  (d = h.handler),
                  (b = h.ctx),
                  (f = h.once),
                  d.apply(null != b ? b : this, a),
                  i.push(f ? this.bindings[c].splice(e, 1) : e++);
              return i;
            }
          }),
          a
        );
      })(),
      j = window.Pace || {},
      window.Pace = j,
      v(j, g.prototype),
      D = j.options = v({}, u, window.paceOptions, x()),
      U = ["ajax", "document", "eventLag", "elements"],
      Q = 0,
      S = U.length;
    S > Q;
    Q++
  )
    (K = U[Q]), D[K] === !0 && (D[K] = u[K]);
  (i = (function(a) {
    function b() {
      return (V = b.__super__.constructor.apply(this, arguments));
    }
    return Z(b, a), b;
  })(Error)),
    (b = (function() {
      function a() {
        this.progress = 0;
      }
      return (a.prototype.getElement = function() {
        var a;
        if (null == this.el) {
          if (((a = document.querySelector(D.target)), !a)) throw new i();
          (this.el = document.createElement("div")),
            (this.el.className = "pace pace-active"),
            (document.body.className = document.body.className.replace(
              /pace-done/g,
              ""
            )),
            (document.body.className += " pace-running"),
            (this.el.innerHTML =
              '<div class="pace-progress">\n  <div class="pace-progress-inner"></div>\n</div>\n<div class="pace-activity"></div>'),
            null != a.firstChild
              ? a.insertBefore(this.el, a.firstChild)
              : a.appendChild(this.el);
        }
        return this.el;
      }),
      (a.prototype.finish = function() {
        var a;
        return (
          (a = this.getElement()),
          (a.className = a.className.replace("pace-active", "")),
          (a.className += " pace-inactive"),
          (document.body.className = document.body.className.replace(
            "pace-running",
            ""
          )),
          (document.body.className += " pace-done")
        );
      }),
      (a.prototype.update = function(a) {
        return (this.progress = a), this.render();
      }),
      (a.prototype.destroy = function() {
        try {
          this.getElement().parentNode.removeChild(this.getElement());
        } catch (a) {
          i = a;
        }
        return (this.el = void 0);
      }),
      (a.prototype.render = function() {
        var a, b, c, d, e, f, g;
        if (null == document.querySelector(D.target)) return !1;
        for (
          a = this.getElement(),
            d = "translate3d(" + this.progress + "%, 0, 0)",
            g = ["webkitTransform", "msTransform", "transform"],
            e = 0,
            f = g.length;
          f > e;
          e++
        )
          (b = g[e]), (a.children[0].style[b] = d);
        return (
          (!this.lastRenderedProgress ||
            this.lastRenderedProgress | (0 !== this.progress) | 0) &&
            (a.children[0].setAttribute(
              "data-progress-text",
              "" + (0 | this.progress) + "%"
            ),
            this.progress >= 100
              ? (c = "99")
              : ((c = this.progress < 10 ? "0" : ""),
                (c += 0 | this.progress)),
            a.children[0].setAttribute("data-progress", "" + c)),
          (this.lastRenderedProgress = this.progress)
        );
      }),
      (a.prototype.done = function() {
        return this.progress >= 100;
      }),
      a;
    })()),
    (h = (function() {
      function a() {
        this.bindings = {};
      }
      return (
        (a.prototype.trigger = function(a, b) {
          var c, d, e, f, g;
          if (null != this.bindings[a]) {
            for (f = this.bindings[a], g = [], d = 0, e = f.length; e > d; d++)
              (c = f[d]), g.push(c.call(this, b));
            return g;
          }
        }),
        (a.prototype.on = function(a, b) {
          var c;
          return (
            null == (c = this.bindings)[a] && (c[a] = []),
            this.bindings[a].push(b)
          );
        }),
        a
      );
    })()),
    (P = window.XMLHttpRequest),
    (O = window.XDomainRequest),
    (N = window.WebSocket),
    (w = function(a, b) {
      var c, d, e, f;
      f = [];
      for (d in b.prototype)
        try {
          (e = b.prototype[d]),
            f.push(
              null == a[d] && "function" != typeof e ? (a[d] = e) : void 0
            );
        } catch (g) {
          c = g;
        }
      return f;
    }),
    (A = []),
    (j.ignore = function() {
      var a, b, c;
      return (
        (b = arguments[0]),
        (a = 2 <= arguments.length ? X.call(arguments, 1) : []),
        A.unshift("ignore"),
        (c = b.apply(null, a)),
        A.shift(),
        c
      );
    }),
    (j.track = function() {
      var a, b, c;
      return (
        (b = arguments[0]),
        (a = 2 <= arguments.length ? X.call(arguments, 1) : []),
        A.unshift("track"),
        (c = b.apply(null, a)),
        A.shift(),
        c
      );
    }),
    (J = function(a) {
      var b;
      if ((null == a && (a = "GET"), "track" === A[0])) return "force";
      if (!A.length && D.ajax) {
        if ("socket" === a && D.ajax.trackWebSockets) return !0;
        if (((b = a.toUpperCase()), $.call(D.ajax.trackMethods, b) >= 0))
          return !0;
      }
      return !1;
    }),
    (k = (function(a) {
      function b() {
        var a,
          c = this;
        b.__super__.constructor.apply(this, arguments),
          (a = function(a) {
            var b;
            return (
              (b = a.open),
              (a.open = function(d, e) {
                return (
                  J(d) && c.trigger("request", { type: d, url: e, request: a }),
                  b.apply(a, arguments)
                );
              })
            );
          }),
          (window.XMLHttpRequest = function(b) {
            var c;
            return (c = new P(b)), a(c), c;
          });
        try {
          w(window.XMLHttpRequest, P);
        } catch (d) {}
        if (null != O) {
          window.XDomainRequest = function() {
            var b;
            return (b = new O()), a(b), b;
          };
          try {
            w(window.XDomainRequest, O);
          } catch (d) {}
        }
        if (null != N && D.ajax.trackWebSockets) {
          window.WebSocket = function(a, b) {
            var d;
            return (
              (d = null != b ? new N(a, b) : new N(a)),
              J("socket") &&
                c.trigger("request", {
                  type: "socket",
                  url: a,
                  protocols: b,
                  request: d
                }),
              d
            );
          };
          try {
            w(window.WebSocket, N);
          } catch (d) {}
        }
      }
      return Z(b, a), b;
    })(h)),
    (R = null),
    (y = function() {
      return null == R && (R = new k()), R;
    }),
    (I = function(a) {
      var b, c, d, e;
      for (e = D.ajax.ignoreURLs, c = 0, d = e.length; d > c; c++)
        if (((b = e[c]), "string" == typeof b)) {
          if (-1 !== a.indexOf(b)) return !0;
        } else if (b.test(a)) return !0;
      return !1;
    }),
    y().on("request", function(b) {
      var c, d, e, f, g;
      return (
        (f = b.type),
        (e = b.request),
        (g = b.url),
        I(g)
          ? void 0
          : j.running || (D.restartOnRequestAfter === !1 && "force" !== J(f))
          ? void 0
          : ((d = arguments),
            (c = D.restartOnRequestAfter || 0),
            "boolean" == typeof c && (c = 0),
            setTimeout(function() {
              var b, c, g, h, i, k;
              if (
                (b =
                  "socket" === f
                    ? e.readyState < 2
                    : 0 < (h = e.readyState) && 4 > h)
              ) {
                for (
                  j.restart(), i = j.sources, k = [], c = 0, g = i.length;
                  g > c;
                  c++
                ) {
                  if (((K = i[c]), K instanceof a)) {
                    K.watch.apply(K, d);
                    break;
                  }
                  k.push(void 0);
                }
                return k;
              }
            }, c))
      );
    }),
    (a = (function() {
      function a() {
        var a = this;
        (this.elements = []),
          y().on("request", function() {
            return a.watch.apply(a, arguments);
          });
      }
      return (
        (a.prototype.watch = function(a) {
          var b, c, d, e;
          return (
            (d = a.type),
            (b = a.request),
            (e = a.url),
            I(e)
              ? void 0
              : ((c = "socket" === d ? new n(b) : new o(b)),
                this.elements.push(c))
          );
        }),
        a
      );
    })()),
    (o = (function() {
      function a(a) {
        var b,
          c,
          d,
          e,
          f,
          g,
          h = this;
        if (((this.progress = 0), null != window.ProgressEvent))
          for (
            c = null,
              a.addEventListener(
                "progress",
                function(a) {
                  return (h.progress = a.lengthComputable
                    ? (100 * a.loaded) / a.total
                    : h.progress + (100 - h.progress) / 2);
                },
                !1
              ),
              g = ["load", "abort", "timeout", "error"],
              d = 0,
              e = g.length;
            e > d;
            d++
          )
            (b = g[d]),
              a.addEventListener(
                b,
                function() {
                  return (h.progress = 100);
                },
                !1
              );
        else
          (f = a.onreadystatechange),
            (a.onreadystatechange = function() {
              var b;
              return (
                0 === (b = a.readyState) || 4 === b
                  ? (h.progress = 100)
                  : 3 === a.readyState && (h.progress = 50),
                "function" == typeof f ? f.apply(null, arguments) : void 0
              );
            });
      }
      return a;
    })()),
    (n = (function() {
      function a(a) {
        var b,
          c,
          d,
          e,
          f = this;
        for (
          this.progress = 0, e = ["error", "open"], c = 0, d = e.length;
          d > c;
          c++
        )
          (b = e[c]),
            a.addEventListener(
              b,
              function() {
                return (f.progress = 100);
              },
              !1
            );
      }
      return a;
    })()),
    (d = (function() {
      function a(a) {
        var b, c, d, f;
        for (
          null == a && (a = {}),
            this.elements = [],
            null == a.selectors && (a.selectors = []),
            f = a.selectors,
            c = 0,
            d = f.length;
          d > c;
          c++
        )
          (b = f[c]), this.elements.push(new e(b));
      }
      return a;
    })()),
    (e = (function() {
      function a(a) {
        (this.selector = a), (this.progress = 0), this.check();
      }
      return (
        (a.prototype.check = function() {
          var a = this;
          return document.querySelector(this.selector)
            ? this.done()
            : setTimeout(function() {
                return a.check();
              }, D.elements.checkInterval);
        }),
        (a.prototype.done = function() {
          return (this.progress = 100);
        }),
        a
      );
    })()),
    (c = (function() {
      function a() {
        var a,
          b,
          c = this;
        (this.progress =
          null != (b = this.states[document.readyState]) ? b : 100),
          (a = document.onreadystatechange),
          (document.onreadystatechange = function() {
            return (
              null != c.states[document.readyState] &&
                (c.progress = c.states[document.readyState]),
              "function" == typeof a ? a.apply(null, arguments) : void 0
            );
          });
      }
      return (
        (a.prototype.states = { loading: 0, interactive: 50, complete: 100 }), a
      );
    })()),
    (f = (function() {
      function a() {
        var a,
          b,
          c,
          d,
          e,
          f = this;
        (this.progress = 0),
          (a = 0),
          (e = []),
          (d = 0),
          (c = C()),
          (b = setInterval(function() {
            var g;
            return (
              (g = C() - c - 50),
              (c = C()),
              e.push(g),
              e.length > D.eventLag.sampleCount && e.shift(),
              (a = q(e)),
              ++d >= D.eventLag.minSamples && a < D.eventLag.lagThreshold
                ? ((f.progress = 100), clearInterval(b))
                : (f.progress = 100 * (3 / (a + 3)))
            );
          }, 50));
      }
      return a;
    })()),
    (m = (function() {
      function a(a) {
        (this.source = a),
          (this.last = this.sinceLastUpdate = 0),
          (this.rate = D.initialRate),
          (this.catchup = 0),
          (this.progress = this.lastProgress = 0),
          null != this.source && (this.progress = F(this.source, "progress"));
      }
      return (
        (a.prototype.tick = function(a, b) {
          var c;
          return (
            null == b && (b = F(this.source, "progress")),
            b >= 100 && (this.done = !0),
            b === this.last
              ? (this.sinceLastUpdate += a)
              : (this.sinceLastUpdate &&
                  (this.rate = (b - this.last) / this.sinceLastUpdate),
                (this.catchup = (b - this.progress) / D.catchupTime),
                (this.sinceLastUpdate = 0),
                (this.last = b)),
            b > this.progress && (this.progress += this.catchup * a),
            (c = 1 - Math.pow(this.progress / 100, D.easeFactor)),
            (this.progress += c * this.rate * a),
            (this.progress = Math.min(
              this.lastProgress + D.maxProgressPerFrame,
              this.progress
            )),
            (this.progress = Math.max(0, this.progress)),
            (this.progress = Math.min(100, this.progress)),
            (this.lastProgress = this.progress),
            this.progress
          );
        }),
        a
      );
    })()),
    (L = null),
    (H = null),
    (r = null),
    (M = null),
    (p = null),
    (s = null),
    (j.running = !1),
    (z = function() {
      return D.restartOnPushState ? j.restart() : void 0;
    }),
    null != window.history.pushState &&
      ((T = window.history.pushState),
      (window.history.pushState = function() {
        return z(), T.apply(window.history, arguments);
      })),
    null != window.history.replaceState &&
      ((W = window.history.replaceState),
      (window.history.replaceState = function() {
        return z(), W.apply(window.history, arguments);
      })),
    (l = { ajax: a, elements: d, document: c, eventLag: f }),
    (B = function() {
      var a, c, d, e, f, g, h, i;
      for (
        j.sources = L = [],
          g = ["ajax", "elements", "document", "eventLag"],
          c = 0,
          e = g.length;
        e > c;
        c++
      )
        (a = g[c]), D[a] !== !1 && L.push(new l[a](D[a]));
      for (
        i = null != (h = D.extraSources) ? h : [], d = 0, f = i.length;
        f > d;
        d++
      )
        (K = i[d]), L.push(new K(D));
      return (j.bar = r = new b()), (H = []), (M = new m());
    })(),
    (j.stop = function() {
      return (
        j.trigger("stop"),
        (j.running = !1),
        r.destroy(),
        (s = !0),
        null != p && ("function" == typeof t && t(p), (p = null)),
        B()
      );
    }),
    (j.restart = function() {
      return j.trigger("restart"), j.stop(), j.start();
    }),
    (j.go = function() {
      var a;
      return (
        (j.running = !0),
        r.render(),
        (a = C()),
        (s = !1),
        (p = G(function(b, c) {
          var d, e, f, g, h, i, k, l, n, o, p, q, t, u, v, w;
          for (
            l = 100 - r.progress, e = p = 0, f = !0, i = q = 0, u = L.length;
            u > q;
            i = ++q
          )
            for (
              K = L[i],
                o = null != H[i] ? H[i] : (H[i] = []),
                h = null != (w = K.elements) ? w : [K],
                k = t = 0,
                v = h.length;
              v > t;
              k = ++t
            )
              (g = h[k]),
                (n = null != o[k] ? o[k] : (o[k] = new m(g))),
                (f &= n.done),
                n.done || (e++, (p += n.tick(b)));
          return (
            (d = p / e),
            r.update(M.tick(b, d)),
            r.done() || f || s
              ? (r.update(100),
                j.trigger("done"),
                setTimeout(function() {
                  return r.finish(), (j.running = !1), j.trigger("hide");
                }, Math.max(D.ghostTime, Math.max(D.minTime - (C() - a), 0))))
              : c()
          );
        }))
      );
    }),
    (j.start = function(a) {
      v(D, a), (j.running = !0);
      try {
        r.render();
      } catch (b) {
        i = b;
      }
      return document.querySelector(".pace")
        ? (j.trigger("start"), j.go())
        : setTimeout(j.start, 50);
    }),
    "function" == typeof define && define.amd
      ? define(function() {
          return j;
        })
      : "object" == typeof exports
      ? (module.exports = j)
      : D.startOnPageLoad && j.start();
}



================================================
FILE: src/shared/components/PropsRoute.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Route } from "react-router-dom";

const renderMergedProps = (component, ...rest) => {
  const finalProps = Object.assign({}, ...rest);
  return React.createElement(component, finalProps);
};

/**
 * Wrapper around the Router component, which makes it pass the properties
 * to it's child.
 * Taken from https://github.com/ReactTraining/react-router/issues/4105
 */
const PropsRoute = ({ component, ...rest }) => (
  <Route
    {...rest}
    render={routeProps => renderMergedProps(component, routeProps, rest)}
  />
);

PropsRoute.propTypes = {
  component: PropTypes.oneOfType([PropTypes.elementType, PropTypes.node])
};

export default PropsRoute;



================================================
FILE: src/shared/components/SelfAligningImage.js
================================================
import React, { useState, useRef, useCallback } from "react";
import PropTypes from "prop-types";
import format from "date-fns/format";
import { ImageListItemBar } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import VertOptions from "./VertOptions";

const styles = {
  imageContainer: {
    width: "100%",
    paddingTop: "100%",
    overflow: "hidden",
    position: "relative",
  },
  image: {
    position: "absolute",
    top: 0,
    bottom: 0,
    left: 0,
    right: 0,
    margin: "auto",
  },
};

function SelfAligningImage(props) {
  const {
    classes,
    src,
    title,
    timeStamp,
    options,
    roundedBorder,
    theme,
  } = props;
  const img = useRef();
  const [hasMoreWidthThanHeight, setHasMoreWidthThanHeight] = useState(null);
  const [hasLoaded, setHasLoaded] = useState(false);

  const onLoad = useCallback(() => {
    if (img.current.naturalHeight < img.current.naturalWidth) {
      setHasMoreWidthThanHeight(true);
    } else {
      setHasMoreWidthThanHeight(false);
    }
    setHasLoaded(true);
  }, [img, setHasLoaded, setHasMoreWidthThanHeight]);

  return (
    <div className={classes.imageContainer}>
      <img
        style={{
          height: hasMoreWidthThanHeight ? "100%" : "auto",
          width: hasMoreWidthThanHeight ? "auto" : "100%",
          display: hasLoaded ? "block" : "none",
          borderRadius: roundedBorder ? theme.shape.borderRadius : 0,
        }}
        ref={img}
        className={classes.image}
        onLoad={onLoad}
        src={src}
        alt=""
      />
      {title && (
        <ImageListItemBar
          title={title}
          subtitle={format(new Date(timeStamp * 1000), "PP - k:mm", {
            awareOfUnicodeTokens: true,
          })}
          actionIcon={
            options.length > 0 && (
              <VertOptions color={theme.palette.common.white} items={options} />
            )
          }
        />
      )}
    </div>
  );
}

SelfAligningImage.propTypes = {
  classes: PropTypes.object.isRequired,
  src: PropTypes.string.isRequired,
  theme: PropTypes.object.isRequired,
  title: PropTypes.string,
  timeStamp: PropTypes.number,
  roundedBorder: PropTypes.bool,
  options: PropTypes.arrayOf(PropTypes.object),
};

export default withStyles(styles, { withTheme: true })(SelfAligningImage);



================================================
FILE: src/shared/components/ShareButton.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { SvgIcon } from "@mui/material";
import ColoredButton from "./ColoredButton";

/**
 * Losely based on: https://sharingbuttons.io/
 */
function ShareButton(props) {
  let { type, title, description, ...rest } = props;
  const site = window.location.href;
  title = encodeURIComponent(title);
  description = encodeURIComponent(description);
  switch (type) {
    case "Facebook":
      return (
        <ColoredButton
          color="#3b5998"
          href={`https://facebook.com/sharer/sharer.php?u=${site}`}
          startIcon={
            <SvgIcon>
              <path d="M18.77 7.46H14.5v-1.9c0-.9.6-1.1 1-1.1h3V.5h-4.33C10.24.5 9.5 3.44 9.5 5.32v2.15h-3v4h3v12h5v-12h3.85l.42-4z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on Facebook
        </ColoredButton>
      );
    case "Twitter": {
      return (
        <ColoredButton
          color="#55acee"
          href={`https://twitter.com/intent/tweet/?text=${description}&amp;url=${site}`}
          startIcon={
            <SvgIcon>
              <path d="M23.44 4.83c-.8.37-1.5.38-2.22.02.93-.56.98-.96 1.32-2.02-.88.52-1.86.9-2.9 1.1-.82-.88-2-1.43-3.3-1.43-2.5 0-4.55 2.04-4.55 4.54 0 .36.03.7.1 1.04-3.77-.2-7.12-2-9.36-4.75-.4.67-.6 1.45-.6 2.3 0 1.56.8 2.95 2 3.77-.74-.03-1.44-.23-2.05-.57v.06c0 2.2 1.56 4.03 3.64 4.44-.67.2-1.37.2-2.06.08.58 1.8 2.26 3.12 4.25 3.16C5.78 18.1 3.37 18.74 1 18.46c2 1.3 4.4 2.04 6.97 2.04 8.35 0 12.92-6.92 12.92-12.93 0-.2 0-.4-.02-.6.9-.63 1.96-1.22 2.56-2.14z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on Twitter
        </ColoredButton>
      );
    }
    case "Tumblr": {
      return (
        <ColoredButton
          color="#35465c"
          href={`https://www.tumblr.com/widgets/share/tool/preview?posttype=link&title=${title}&caption=${description}&content=${site}&canonicalUrl=${site}&shareSource=tumblr_share_button`}
          startIcon={
            <SvgIcon>
              <path d="M13.5.5v5h5v4h-5V15c0 5 3.5 4.4 6 2.8v4.4c-6.7 3.2-12 0-12-4.2V9.5h-3V6.7c1-.3 2.2-.7 3-1.3.5-.5 1-1.2 1.4-2 .3-.7.6-1.7.7-3h3.8z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on Tumblr
        </ColoredButton>
      );
    }
    case "E-Mail": {
      return (
        <ColoredButton
          color="#777"
          href={`mailto:?subject=${title}&amp;body=${site}`}
          startIcon={
            <SvgIcon>
              <path d="M22 4H2C.9 4 0 4.9 0 6v12c0 1.1.9 2 2 2h20c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zM7.25 14.43l-3.5 2c-.08.05-.17.07-.25.07-.17 0-.34-.1-.43-.25-.14-.24-.06-.55.18-.68l3.5-2c.24-.14.55-.06.68.18.14.24.06.55-.18.68zm4.75.07c-.1 0-.2-.03-.27-.08l-8.5-5.5c-.23-.15-.3-.46-.15-.7.15-.22.46-.3.7-.14L12 13.4l8.23-5.32c.23-.15.54-.08.7.15.14.23.07.54-.16.7l-8.5 5.5c-.08.04-.17.07-.27.07zm8.93 1.75c-.1.16-.26.25-.43.25-.08 0-.17-.02-.25-.07l-3.5-2c-.24-.13-.32-.44-.18-.68s.44-.32.68-.18l3.5 2c.24.13.32.44.18.68z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share by E-Mail
        </ColoredButton>
      );
    }
    case "Pinterest": {
      return (
        <ColoredButton
          color="#bd081c"
          href={`https://pinterest.com/pin/create/button/?url=${site}&amp;media=${site}&amp;description=${description}`}
          startIcon={
            <SvgIcon>
              <path d="M12.14.5C5.86.5 2.7 5 2.7 8.75c0 2.27.86 4.3 2.7 5.05.3.12.57 0 .66-.33l.27-1.06c.1-.32.06-.44-.2-.73-.52-.62-.86-1.44-.86-2.6 0-3.33 2.5-6.32 6.5-6.32 3.55 0 5.5 2.17 5.5 5.07 0 3.8-1.7 7.02-4.2 7.02-1.37 0-2.4-1.14-2.07-2.54.4-1.68 1.16-3.48 1.16-4.7 0-1.07-.58-1.98-1.78-1.98-1.4 0-2.55 1.47-2.55 3.42 0 1.25.43 2.1.43 2.1l-1.7 7.2c-.5 2.13-.08 4.75-.04 5 .02.17.22.2.3.1.14-.18 1.82-2.26 2.4-4.33.16-.58.93-3.63.93-3.63.45.88 1.8 1.65 3.22 1.65 4.25 0 7.13-3.87 7.13-9.05C20.5 4.15 17.18.5 12.14.5z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on Pinterest
        </ColoredButton>
      );
    }
    case "LinkedIn": {
      return (
        <ColoredButton
          color="#0077b5"
          href={`https://www.linkedin.com/shareArticle?mini=true&amp;url=${site}&amp;title=${title}&amp;summary=${description}&amp;source=${site}`}
          startIcon={
            <SvgIcon>
              <path d="M6.5 21.5h-5v-13h5v13zM4 6.5C2.5 6.5 1.5 5.3 1.5 4s1-2.4 2.5-2.4c1.6 0 2.5 1 2.6 2.5 0 1.4-1 2.5-2.6 2.5zm11.5 6c-1 0-2 1-2 2v7h-5v-13h5V10s1.6-1.5 4-1.5c3 0 5 2.2 5 6.3v6.7h-5v-7c0-1-1-2-2-2z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on LinkedIn
        </ColoredButton>
      );
    }
    case "Reddit": {
      return (
        <ColoredButton
          color="#5f99cf"
          href={`https://reddit.com/submit/?url=${site}&amp;resubmit=true&amp;&title=${title}`}
          startIcon={
            <SvgIcon>
              <path d="M24 11.5c0-1.65-1.35-3-3-3-.96 0-1.86.48-2.42 1.24-1.64-1-3.75-1.64-6.07-1.72.08-1.1.4-3.05 1.52-3.7.72-.4 1.73-.24 3 .5C17.2 6.3 18.46 7.5 20 7.5c1.65 0 3-1.35 3-3s-1.35-3-3-3c-1.38 0-2.54.94-2.88 2.22-1.43-.72-2.64-.8-3.6-.25-1.64.94-1.95 3.47-2 4.55-2.33.08-4.45.7-6.1 1.72C4.86 8.98 3.96 8.5 3 8.5c-1.65 0-3 1.35-3 3 0 1.32.84 2.44 2.05 2.84-.03.22-.05.44-.05.66 0 3.86 4.5 7 10 7s10-3.14 10-7c0-.22-.02-.44-.05-.66 1.2-.4 2.05-1.54 2.05-2.84zM2.3 13.37C1.5 13.07 1 12.35 1 11.5c0-1.1.9-2 2-2 .64 0 1.22.32 1.6.82-1.1.85-1.92 1.9-2.3 3.05zm3.7.13c0-1.1.9-2 2-2s2 .9 2 2-.9 2-2 2-2-.9-2-2zm9.8 4.8c-1.08.63-2.42.96-3.8.96-1.4 0-2.74-.34-3.8-.95-.24-.13-.32-.44-.2-.68.15-.24.46-.32.7-.18 1.83 1.06 4.76 1.06 6.6 0 .23-.13.53-.05.67.2.14.23.06.54-.18.67zm.2-2.8c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2zm5.7-2.13c-.38-1.16-1.2-2.2-2.3-3.05.38-.5.97-.82 1.6-.82 1.1 0 2 .9 2 2 0 .84-.53 1.57-1.3 1.87z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on Reddit
        </ColoredButton>
      );
    }
    case "XING": {
      return (
        <ColoredButton
          color="#1a7576"
          href={`https://www.xing.com/app/user?op=share;url=${site};title=${description}`}
          startIcon={
            <SvgIcon>
              <path d="M10.2 9.7l-3-5.4C7.2 4 7 4 6.8 4h-5c-.3 0-.4 0-.5.2v.5L4 10 .4 16v.5c0 .2.2.3.4.3h5c.3 0 .4 0 .5-.2l4-6.6v-.5zM24 .2l-.5-.2H18s-.2 0-.3.3l-8 14v.4l5.2 9c0 .2 0 .3.3.3h5.4s.3 0 .4-.2c.2-.2.2-.4 0-.5l-5-8.8L24 .7V.2z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on XING
        </ColoredButton>
      );
    }
    case "WhatsApp": {
      return (
        <ColoredButton
          color="#25d366"
          href={`whatsapp://send?text=${description}`}
          startIcon={
            <SvgIcon>
              <path d="M20.1 3.9C17.9 1.7 15 .5 12 .5 5.8.5.7 5.6.7 11.9c0 2 .5 3.9 1.5 5.6L.6 23.4l6-1.6c1.6.9 3.5 1.3 5.4 1.3 6.3 0 11.4-5.1 11.4-11.4-.1-2.8-1.2-5.7-3.3-7.8zM12 21.4c-1.7 0-3.3-.5-4.8-1.3l-.4-.2-3.5 1 1-3.4L4 17c-1-1.5-1.4-3.2-1.4-5.1 0-5.2 4.2-9.4 9.4-9.4 2.5 0 4.9 1 6.7 2.8 1.8 1.8 2.8 4.2 2.8 6.7-.1 5.2-4.3 9.4-9.5 9.4zm5.1-7.1c-.3-.1-1.7-.9-1.9-1-.3-.1-.5-.1-.7.1-.2.3-.8 1-.9 1.1-.2.2-.3.2-.6.1s-1.2-.5-2.3-1.4c-.9-.8-1.4-1.7-1.6-2-.2-.3 0-.5.1-.6s.3-.3.4-.5c.2-.1.3-.3.4-.5.1-.2 0-.4 0-.5C10 9 9.3 7.6 9 7c-.1-.4-.4-.3-.5-.3h-.6s-.4.1-.7.3c-.3.3-1 1-1 2.4s1 2.8 1.1 3c.1.2 2 3.1 4.9 4.3.7.3 1.2.5 1.6.6.7.2 1.3.2 1.8.1.6-.1 1.7-.7 1.9-1.3.2-.7.2-1.2.2-1.3-.1-.3-.3-.4-.6-.5z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on WhatsApp
        </ColoredButton>
      );
    }
    case "Hacker News": {
      return (
        <ColoredButton
          color="#ff6600"
          href={`https://news.ycombinator.com/submitlink?u=${site}&amp;&t=${description}`}
          startIcon={
            <SvgIcon>
              <path
                fill-rule="evenodd"
                d="M60.94 82.314L17 0h20.08l25.85 52.093c.397.927.86 1.888 1.39 2.883.53.994.995 2.02 1.393 3.08.265.4.463.764.596 1.095.13.334.262.63.395.898.662 1.325 1.26 2.618 1.79 3.877.53 1.26.993 2.42 1.39 3.48 1.06-2.254 2.22-4.673 3.48-7.258 1.26-2.585 2.552-5.27 3.877-8.052L103.49 0h18.69L77.84 83.308v53.087h-16.9v-54.08z"
              ></path>
            </SvgIcon>
          }
          {...rest}
        >
          Share on Hacker News
        </ColoredButton>
      );
    }
    case "VK": {
      return (
        <ColoredButton
          color="#507299"
          href={`https://vk.com/share.php?title=${description}&amp;&url=${site}`}
          startIcon={
            <SvgIcon>
              <path d="M21.547 7h-3.29a.743.743 0 0 0-.655.392s-1.312 2.416-1.734 3.23C14.734 12.813 14 12.126 14 11.11V7.603A1.104 1.104 0 0 0 12.896 6.5h-2.474a1.982 1.982 0 0 0-1.75.813s1.255-.204 1.255 1.49c0 .42.022 1.626.04 2.64a.73.73 0 0 1-1.272.503 21.54 21.54 0 0 1-2.498-4.543.693.693 0 0 0-.63-.403h-2.99a.508.508 0 0 0-.48.685C3.005 10.175 6.918 18 11.38 18h1.878a.742.742 0 0 0 .742-.742v-1.135a.73.73 0 0 1 1.23-.53l2.247 2.112a1.09 1.09 0 0 0 .746.295h2.953c1.424 0 1.424-.988.647-1.753-.546-.538-2.518-2.617-2.518-2.617a1.02 1.02 0 0 1-.078-1.323c.637-.84 1.68-2.212 2.122-2.8.603-.804 1.697-2.507.197-2.507z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on VK
        </ColoredButton>
      );
    }
    case "Telegram": {
      return (
        <ColoredButton
          color="#54A9EB"
          href={`https://telegram.me/share/url?text=${description}&amp;&url=${site}`}
          startIcon={
            <SvgIcon>
              <path d="M.707 8.475C.275 8.64 0 9.508 0 9.508s.284.867.718 1.03l5.09 1.897 1.986 6.38a1.102 1.102 0 0 0 1.75.527l2.96-2.41a.405.405 0 0 1 .494-.013l5.34 3.87a1.1 1.1 0 0 0 1.046.135 1.1 1.1 0 0 0 .682-.803l3.91-18.795A1.102 1.102 0 0 0 22.5.075L.706 8.475z" />
            </SvgIcon>
          }
          {...rest}
        >
          Share on Telegram
        </ColoredButton>
      );
    }
    default: {
      throw new Error(
        `No branch taken in switch-statement: ${type} is not a valid type.`
      );
    }
  }
}

ShareButton.propTypes = {
  type: PropTypes.string.isRequired,
  title: PropTypes.string.isRequired,
  description: PropTypes.string.isRequired
};

export default ShareButton;



================================================
FILE: src/shared/components/ShareButtons.js
================================================
import React from "react";
import PropTypes from "prop-types";
import { Grid, SvgIcon } from "@mui/material";
import ColoredButton from "./ColoredButton";

/**
 * Losely based on: https://sharingbuttons.io/
 */
function ShareButtons(props) {
  const { types, forceWhite } = props;
  let { title, description } = props;
  const site = window.location.href;
  title = encodeURIComponent(title);
  description = encodeURIComponent(description);
  return (
    <Grid container spacing={1}>
      {types.map((element, index) => {
        switch (element) {
          case "Facebook":
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#3b5998"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://facebook.com/sharer/sharer.php?u=${site}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M18.77 7.46H14.5v-1.9c0-.9.6-1.1 1-1.1h3V.5h-4.33C10.24.5 9.5 3.44 9.5 5.32v2.15h-3v4h3v12h5v-12h3.85l.42-4z" />
                    </SvgIcon>
                  }
                >
                  Share on Facebook
                </ColoredButton>
              </Grid>
            );
          case "Twitter": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#55acee"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://twitter.com/intent/tweet/?text=${description}&amp;url=${site}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M23.44 4.83c-.8.37-1.5.38-2.22.02.93-.56.98-.96 1.32-2.02-.88.52-1.86.9-2.9 1.1-.82-.88-2-1.43-3.3-1.43-2.5 0-4.55 2.04-4.55 4.54 0 .36.03.7.1 1.04-3.77-.2-7.12-2-9.36-4.75-.4.67-.6 1.45-.6 2.3 0 1.56.8 2.95 2 3.77-.74-.03-1.44-.23-2.05-.57v.06c0 2.2 1.56 4.03 3.64 4.44-.67.2-1.37.2-2.06.08.58 1.8 2.26 3.12 4.25 3.16C5.78 18.1 3.37 18.74 1 18.46c2 1.3 4.4 2.04 6.97 2.04 8.35 0 12.92-6.92 12.92-12.93 0-.2 0-.4-.02-.6.9-.63 1.96-1.22 2.56-2.14z" />
                    </SvgIcon>
                  }
                >
                  Share on Twitter
                </ColoredButton>
              </Grid>
            );
          }
          case "Tumblr": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#35465c"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://www.tumblr.com/widgets/share/tool/preview?posttype=link&title=${title}&caption=${description}&content=${site}&canonicalUrl=${site}&shareSource=tumblr_share_button`}
                  startIcon={
                    <SvgIcon>
                      <path d="M13.5.5v5h5v4h-5V15c0 5 3.5 4.4 6 2.8v4.4c-6.7 3.2-12 0-12-4.2V9.5h-3V6.7c1-.3 2.2-.7 3-1.3.5-.5 1-1.2 1.4-2 .3-.7.6-1.7.7-3h3.8z" />
                    </SvgIcon>
                  }
                >
                  Share on Tumblr
                </ColoredButton>
              </Grid>
            );
          }
          case "E-Mail": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#777"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`mailto:?subject=${title}&amp;body=${site}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M22 4H2C.9 4 0 4.9 0 6v12c0 1.1.9 2 2 2h20c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zM7.25 14.43l-3.5 2c-.08.05-.17.07-.25.07-.17 0-.34-.1-.43-.25-.14-.24-.06-.55.18-.68l3.5-2c.24-.14.55-.06.68.18.14.24.06.55-.18.68zm4.75.07c-.1 0-.2-.03-.27-.08l-8.5-5.5c-.23-.15-.3-.46-.15-.7.15-.22.46-.3.7-.14L12 13.4l8.23-5.32c.23-.15.54-.08.7.15.14.23.07.54-.16.7l-8.5 5.5c-.08.04-.17.07-.27.07zm8.93 1.75c-.1.16-.26.25-.43.25-.08 0-.17-.02-.25-.07l-3.5-2c-.24-.13-.32-.44-.18-.68s.44-.32.68-.18l3.5 2c.24.13.32.44.18.68z" />
                    </SvgIcon>
                  }
                >
                  Share by E-Mail
                </ColoredButton>
              </Grid>
            );
          }
          case "Pinterest": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#bd081c"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://pinterest.com/pin/create/button/?url=${site}&amp;media=${site}&amp;description=${description}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M12.14.5C5.86.5 2.7 5 2.7 8.75c0 2.27.86 4.3 2.7 5.05.3.12.57 0 .66-.33l.27-1.06c.1-.32.06-.44-.2-.73-.52-.62-.86-1.44-.86-2.6 0-3.33 2.5-6.32 6.5-6.32 3.55 0 5.5 2.17 5.5 5.07 0 3.8-1.7 7.02-4.2 7.02-1.37 0-2.4-1.14-2.07-2.54.4-1.68 1.16-3.48 1.16-4.7 0-1.07-.58-1.98-1.78-1.98-1.4 0-2.55 1.47-2.55 3.42 0 1.25.43 2.1.43 2.1l-1.7 7.2c-.5 2.13-.08 4.75-.04 5 .02.17.22.2.3.1.14-.18 1.82-2.26 2.4-4.33.16-.58.93-3.63.93-3.63.45.88 1.8 1.65 3.22 1.65 4.25 0 7.13-3.87 7.13-9.05C20.5 4.15 17.18.5 12.14.5z" />
                    </SvgIcon>
                  }
                >
                  Share on Pinterest
                </ColoredButton>
              </Grid>
            );
          }
          case "LinkedIn": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#0077b5"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://www.linkedin.com/shareArticle?mini=true&amp;url=${site}&amp;title=${title}&amp;summary=${description}&amp;source=${site}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M6.5 21.5h-5v-13h5v13zM4 6.5C2.5 6.5 1.5 5.3 1.5 4s1-2.4 2.5-2.4c1.6 0 2.5 1 2.6 2.5 0 1.4-1 2.5-2.6 2.5zm11.5 6c-1 0-2 1-2 2v7h-5v-13h5V10s1.6-1.5 4-1.5c3 0 5 2.2 5 6.3v6.7h-5v-7c0-1-1-2-2-2z" />
                    </SvgIcon>
                  }
                >
                  Share on LinkedIn
                </ColoredButton>
              </Grid>
            );
          }
          case "Reddit": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#5f99cf"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://reddit.com/submit/?url=${site}&amp;resubmit=true&amp;&title=${title}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M24 11.5c0-1.65-1.35-3-3-3-.96 0-1.86.48-2.42 1.24-1.64-1-3.75-1.64-6.07-1.72.08-1.1.4-3.05 1.52-3.7.72-.4 1.73-.24 3 .5C17.2 6.3 18.46 7.5 20 7.5c1.65 0 3-1.35 3-3s-1.35-3-3-3c-1.38 0-2.54.94-2.88 2.22-1.43-.72-2.64-.8-3.6-.25-1.64.94-1.95 3.47-2 4.55-2.33.08-4.45.7-6.1 1.72C4.86 8.98 3.96 8.5 3 8.5c-1.65 0-3 1.35-3 3 0 1.32.84 2.44 2.05 2.84-.03.22-.05.44-.05.66 0 3.86 4.5 7 10 7s10-3.14 10-7c0-.22-.02-.44-.05-.66 1.2-.4 2.05-1.54 2.05-2.84zM2.3 13.37C1.5 13.07 1 12.35 1 11.5c0-1.1.9-2 2-2 .64 0 1.22.32 1.6.82-1.1.85-1.92 1.9-2.3 3.05zm3.7.13c0-1.1.9-2 2-2s2 .9 2 2-.9 2-2 2-2-.9-2-2zm9.8 4.8c-1.08.63-2.42.96-3.8.96-1.4 0-2.74-.34-3.8-.95-.24-.13-.32-.44-.2-.68.15-.24.46-.32.7-.18 1.83 1.06 4.76 1.06 6.6 0 .23-.13.53-.05.67.2.14.23.06.54-.18.67zm.2-2.8c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2zm5.7-2.13c-.38-1.16-1.2-2.2-2.3-3.05.38-.5.97-.82 1.6-.82 1.1 0 2 .9 2 2 0 .84-.53 1.57-1.3 1.87z" />
                    </SvgIcon>
                  }
                >
                  Share on Reddit
                </ColoredButton>
              </Grid>
            );
          }
          case "XING": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#1a7576"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://www.xing.com/app/user?op=share;url=${site};title=${description}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M10.2 9.7l-3-5.4C7.2 4 7 4 6.8 4h-5c-.3 0-.4 0-.5.2v.5L4 10 .4 16v.5c0 .2.2.3.4.3h5c.3 0 .4 0 .5-.2l4-6.6v-.5zM24 .2l-.5-.2H18s-.2 0-.3.3l-8 14v.4l5.2 9c0 .2 0 .3.3.3h5.4s.3 0 .4-.2c.2-.2.2-.4 0-.5l-5-8.8L24 .7V.2z" />
                    </SvgIcon>
                  }
                >
                  Share on XING
                </ColoredButton>
              </Grid>
            );
          }
          case "WhatsApp": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#25d366"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`whatsapp://send?text=${description}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M20.1 3.9C17.9 1.7 15 .5 12 .5 5.8.5.7 5.6.7 11.9c0 2 .5 3.9 1.5 5.6L.6 23.4l6-1.6c1.6.9 3.5 1.3 5.4 1.3 6.3 0 11.4-5.1 11.4-11.4-.1-2.8-1.2-5.7-3.3-7.8zM12 21.4c-1.7 0-3.3-.5-4.8-1.3l-.4-.2-3.5 1 1-3.4L4 17c-1-1.5-1.4-3.2-1.4-5.1 0-5.2 4.2-9.4 9.4-9.4 2.5 0 4.9 1 6.7 2.8 1.8 1.8 2.8 4.2 2.8 6.7-.1 5.2-4.3 9.4-9.5 9.4zm5.1-7.1c-.3-.1-1.7-.9-1.9-1-.3-.1-.5-.1-.7.1-.2.3-.8 1-.9 1.1-.2.2-.3.2-.6.1s-1.2-.5-2.3-1.4c-.9-.8-1.4-1.7-1.6-2-.2-.3 0-.5.1-.6s.3-.3.4-.5c.2-.1.3-.3.4-.5.1-.2 0-.4 0-.5C10 9 9.3 7.6 9 7c-.1-.4-.4-.3-.5-.3h-.6s-.4.1-.7.3c-.3.3-1 1-1 2.4s1 2.8 1.1 3c.1.2 2 3.1 4.9 4.3.7.3 1.2.5 1.6.6.7.2 1.3.2 1.8.1.6-.1 1.7-.7 1.9-1.3.2-.7.2-1.2.2-1.3-.1-.3-.3-.4-.6-.5z" />
                    </SvgIcon>
                  }
                >
                  Share on WhatsApp
                </ColoredButton>
              </Grid>
            );
          }
          case "Hacker News": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#ff6600"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://news.ycombinator.com/submitlink?u=${site}&amp;&t=${description}`}
                  startIcon={
                    <SvgIcon>
                      <path
                        fill-rule="evenodd"
                        d="M60.94 82.314L17 0h20.08l25.85 52.093c.397.927.86 1.888 1.39 2.883.53.994.995 2.02 1.393 3.08.265.4.463.764.596 1.095.13.334.262.63.395.898.662 1.325 1.26 2.618 1.79 3.877.53 1.26.993 2.42 1.39 3.48 1.06-2.254 2.22-4.673 3.48-7.258 1.26-2.585 2.552-5.27 3.877-8.052L103.49 0h18.69L77.84 83.308v53.087h-16.9v-54.08z"
                      ></path>
                    </SvgIcon>
                  }
                >
                  Share on Hacker News
                </ColoredButton>
              </Grid>
            );
          }
          case "VK": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#507299"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://vk.com/share.php?title=${description}&amp;&url=${site}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M21.547 7h-3.29a.743.743 0 0 0-.655.392s-1.312 2.416-1.734 3.23C14.734 12.813 14 12.126 14 11.11V7.603A1.104 1.104 0 0 0 12.896 6.5h-2.474a1.982 1.982 0 0 0-1.75.813s1.255-.204 1.255 1.49c0 .42.022 1.626.04 2.64a.73.73 0 0 1-1.272.503 21.54 21.54 0 0 1-2.498-4.543.693.693 0 0 0-.63-.403h-2.99a.508.508 0 0 0-.48.685C3.005 10.175 6.918 18 11.38 18h1.878a.742.742 0 0 0 .742-.742v-1.135a.73.73 0 0 1 1.23-.53l2.247 2.112a1.09 1.09 0 0 0 .746.295h2.953c1.424 0 1.424-.988.647-1.753-.546-.538-2.518-2.617-2.518-2.617a1.02 1.02 0 0 1-.078-1.323c.637-.84 1.68-2.212 2.122-2.8.603-.804 1.697-2.507.197-2.507z" />
                    </SvgIcon>
                  }
                >
                  Share on VK
                </ColoredButton>
              </Grid>
            );
          }
          case "Telegram": {
            return (
              <Grid item key={index}>
                <ColoredButton
                  color="#54A9EB"
                  className={forceWhite ? "text-white" : null}
                  classes={{ label: forceWhite ? "text-white" : null }}
                  variant="contained"
                  disableElevation
                  href={`https://telegram.me/share/url?text=${description}&amp;&url=${site}`}
                  startIcon={
                    <SvgIcon>
                      <path d="M.707 8.475C.275 8.64 0 9.508 0 9.508s.284.867.718 1.03l5.09 1.897 1.986 6.38a1.102 1.102 0 0 0 1.75.527l2.96-2.41a.405.405 0 0 1 .494-.013l5.34 3.87a1.1 1.1 0 0 0 1.046.135 1.1 1.1 0 0 0 .682-.803l3.91-18.795A1.102 1.102 0 0 0 22.5.075L.706 8.475z" />
                    </SvgIcon>
                  }
                >
                  Share on Telegram
                </ColoredButton>
              </Grid>
            );
          }
          default: {
            throw new Error(
              `No branch taken in switch-statement: ${element} is not a valid type.`
            );
          }
        }
      })}
    </Grid>
  );
}

ShareButtons.propTypes = {
  types: PropTypes.arrayOf(PropTypes.string).isRequired,
  description: PropTypes.string.isRequired,
  title: PropTypes.string.isRequired,
  forceWhite: PropTypes.bool
};

export default ShareButtons;



================================================
FILE: src/shared/components/VertOptions.js
================================================
import React, { Fragment, useState, useCallback, useRef } from "react";
import PropTypes from "prop-types";
import { Popover, IconButton, MenuList, ListItemText, ListItemIcon, MenuItem } from "@mui/material";
import withStyles from '@mui/styles/withStyles';
import MoreVertIcon from "@mui/icons-material/MoreVert";

const styles = {
  listItemtext: {
    paddingLeft: "0 !important",
  },
};

function VertOptions(props) {
  const { items, classes, color } = props;
  const anchorEl = useRef();
  const [isOpen, setIsOpen] = useState(false);

  const handleClose = useCallback(() => {
    setIsOpen(false);
  }, [setIsOpen]);

  const handleOpen = useCallback(() => {
    setIsOpen(true);
  }, [setIsOpen]);

  const id = isOpen ? "scroll-playground" : null;
  return (
    <Fragment>
      <IconButton
        onClick={handleOpen}
        buttonRef={anchorEl}
        style={{ color: color ? color : null }}
        aria-describedby={id}
        aria-label="More Options"
        size="large">
        <MoreVertIcon style={{ color: color ? color : null }} />
      </IconButton>
      <Popover
        id={id}
        open={isOpen}
        anchorEl={anchorEl.current}
        anchorOrigin={{
          vertical: "bottom",
          horizontal: "center",
        }}
        transformOrigin={{
          vertical: "top",
          horizontal: "center",
        }}
        onClose={handleClose}
        disableScrollLock
      >
        <MenuList dense>
          {items.map((item) => (
            <MenuItem
              key={item.name}
              onClick={() => {
                handleClose();
                item.onClick();
              }}
            >
              <ListItemIcon>{item.icon}</ListItemIcon>
              <ListItemText className={classes.listItemtext}>
                {item.name}
              </ListItemText>
            </MenuItem>
          ))}
        </MenuList>
      </Popover>
    </Fragment>
  );
}

VertOptions.propTypes = {
  items: PropTypes.arrayOf(PropTypes.object).isRequired,
  classes: PropTypes.object.isRequired,
  color: PropTypes.string,
};

export default withStyles(styles)(VertOptions);



================================================
FILE: src/shared/components/VisibilityPasswordTextField.js
================================================
import React from "react";
import { TextField, InputAdornment, IconButton } from "@mui/material";
import VisibilityIcon from "@mui/icons-material/Visibility";
import VisibilityOffIcon from "@mui/icons-material/VisibilityOff";

function VisibilityPasswordTextField(props) {
  const { isVisible, onVisibilityChange, ...rest } = props;
  return (
    <TextField
      {...rest}
      type={isVisible ? "text" : "password"}
      InputProps={{
        endAdornment: (
          <InputAdornment position="end">
            <IconButton
              aria-label="Toggle password visibility"
              onClick={() => {
                onVisibilityChange(!isVisible);
              }}
              onMouseDown={(event) => {
                event.preventDefault();
              }}
              size="large">
              {isVisible ? <VisibilityIcon /> : <VisibilityOffIcon />}
            </IconButton>
          </InputAdornment>
        ),
      }}
    ></TextField>
  );
}

export default VisibilityPasswordTextField;



================================================
FILE: src/shared/components/WaveBorder.js
================================================
import React from "react";
import PropTypes from "prop-types";
import withStyles from '@mui/styles/withStyles';

const styles = {
  waves: {
    position: "relative",
    width: "100%",
    marginBottom: -7,
    height: "7vw",
    minHeight: "7vw"
  },
  "@keyframes moveForever": {
    from: { transform: "translate3d(-90px, 0, 0)" },
    to: { transform: "translate3d(85px, 0, 0)" }
  },
  parallax: {
    "& > use": {
      animation: "$moveForever 4s cubic-bezier(0.62, 0.5, 0.38, 0.5) infinite",
      animationDelay: props => `-${props.animationNegativeDelay}s`
    }
  }
};

/**
 *  https://codepen.io/csspoints/pen/WNeOEqd
 */
function WaveBorder(props) {
  const id = String(Math.random());
  const {
    className,
    lowerColor,
    upperColor,
    classes,
    animationNegativeDelay,
    ...rest
  } = props;
  return (
    <div className={className} style={{ background: upperColor }} {...rest}>
      <svg
        className={classes.waves}
        xmlns="http://www.w3.org/2000/svg"
        xlink="http://www.w3.org/1999/xlink"
        viewBox="0 24 150 28"
        preserveAspectRatio="none"
        shapeRendering="auto"
      >
        <defs>
          <path
            id={id}
            d="M-160 44c30 0 58-18 88-18s 58 18 88 18 58-18 88-18 58 18 88 18 v44h-352z"
          />
        </defs>
        <g className={classes.parallax}>
          <use href={`#${id}`} x="48" y="0" fill={lowerColor} />
        </g>
      </svg>
    </div>
  );
}

WaveBorder.propTypes = {
  lowerColor: PropTypes.string.isRequired,
  upperColor: PropTypes.string.isRequired,
  classes: PropTypes.object.isRequired,
  animationNegativeDelay: PropTypes.number.isRequired
};

export default withStyles(styles)(WaveBorder);



================================================
FILE: src/shared/components/ZoomImage.js
================================================
import React, { Fragment, useState, useCallback, useEffect } from "react";
import PropTypes from "prop-types";
import { Portal, Backdrop } from "@mui/material";
import withStyles from "@mui/styles/withStyles";
import ScrollbarSize from "@mui/material/Tabs/ScrollbarSize";
import classNames from "classnames";

const styles = (theme) => ({
  backdrop: {
    zIndex: theme.zIndex.modal,
    backgroundColor: "rgba(0, 0, 0, 0.8)",
  },
  portalImgWrapper: {
    position: "fixed",
    top: "0",
    left: "0",
    width: "100%",
    height: "100%",
    zIndex: theme.zIndex.modal,
    cursor: "pointer",
  },
  portalImgInnerWrapper: {
    display: "flex",
    justifyContent: "center",
    alignItems: "center",
    width: "100%",
    height: "100%",
    paddingLeft: theme.spacing(1),
    paddingRight: theme.spacing(1),
    paddingTop: theme.spacing(1),
    paddingBottom: theme.spacing(1),
  },
  portalImg: {
    objectFit: "contain",
    maxWidth: "100%",
    maxHeight: "100%",
  },
  zoomedOutImage: {
    cursor: "pointer",
  },
});

function ZoomImage(props) {
  const { alt, src, zoomedImgProps, classes, className, ...rest } = props;
  const [zoomedIn, setZoomedIn] = useState(false);
  const [scrollbarSize, setScrollbarSize] = useState(null);

  const zoomIn = useCallback(() => {
    setZoomedIn(true);
  }, [setZoomedIn]);

  const zoomOut = useCallback(() => {
    setZoomedIn(false);
  }, [setZoomedIn]);

  useEffect(() => {
    if (zoomedIn) {
      document.body.style.overflow = "hidden";
      document.body.style.paddingRight = `${scrollbarSize}px`;
      document.querySelector(
        "header"
      ).style.paddingRight = `${scrollbarSize}px`;
    } else {
      document.body.style.overflow = "auto";
      document.body.style.paddingRight = "0px";
      document.querySelector("header").style.paddingRight = "0px";
    }
  }, [zoomedIn, scrollbarSize]);

  return (
    <Fragment>
      <ScrollbarSize onChange={setScrollbarSize}></ScrollbarSize>
      {zoomedIn && (
        <Portal>
          <Backdrop
            open={zoomedIn}
            className={classes.backdrop}
            onClick={zoomOut}
          ></Backdrop>
          <div onClick={zoomOut} className={classes.portalImgWrapper}>
            <div className={classes.portalImgInnerWrapper}>
              <img
                alt={alt}
                src={src}
                className={classes.portalImg}
                {...zoomedImgProps}
              ></img>
            </div>
          </div>
        </Portal>
      )}
      <img
        alt={alt}
        src={src}
        onClick={zoomIn}
        className={classNames(className, classes.zoomedOutImage)}
        {...rest}
      ></img>
    </Fragment>
  );
}

ZoomImage.propTypes = {
  classes: PropTypes.object.isRequired,
  alt: PropTypes.string.isRequired,
  src: PropTypes.string.isRequired,
  theme: PropTypes.object.isRequired,
  zoomedImgProps: PropTypes.object,
  className: PropTypes.string,
};

export default withStyles(styles, { withTheme: true })(ZoomImage);



================================================
FILE: src/shared/functions/countWithEmojis.js
================================================
import toArray from "./toArray";

/**
 * Counts the characters in a string and counts emojis correctly.
 *
 * @param {string} str The string to count characters from.
 * @return {number} The number of characters in the string.
 */
function countWithEmojis(str) {
  return toArray(str).length;
}

export default countWithEmojis;



================================================
FILE: src/shared/functions/currencyPrettyPrint.js
================================================
function currencyPrettyPrint(cents) {
  const dollars = cents / 100;
  return dollars.toLocaleString("en-US", {
    style: "currency",
    currency: "USD"
  });
}

export default currencyPrettyPrint;



================================================
FILE: src/shared/functions/getSorting.js
================================================
function desc(a, b, orderBy) {
  if (b[orderBy] < a[orderBy]) {
    return -1;
  }
  if (b[orderBy] > a[orderBy]) {
    return 1;
  }
  return 0;
}

function getSorting(order, orderBy) {
  return order === "desc"
    ? (a, b) => desc(a, b, orderBy)
    : (a, b) => -desc(a, b, orderBy);
}
export default getSorting;



================================================
FILE: src/shared/functions/shadeColor.js
================================================
function shadeColor(color, percent) {
  const f = parseInt(color.slice(1), 16);
  const t = percent < 0 ? 0 : 255;
  const p = percent < 0 ? percent * -1 : percent;
  const R = f >> 16;
  const G = (f >> 8) & 0x00ff;
  const B = f & 0x0000ff;
  return `#${(
    0x1000000 +
    (Math.round((t - R) * p) + R) * 0x10000 +
    (Math.round((t - G) * p) + G) * 0x100 +
    (Math.round((t - B) * p) + B)
  )
    .toString(16)
    .slice(1)}`;
}

export default shadeColor;



================================================
FILE: src/shared/functions/smoothScrollTop.js
================================================
/**
 * When called scrolls smooth to the top of the page.
 * globLastC prevents shaky animations when scrolling to
 * bottom while topscrolling.
 */
let globLastC = Infinity;

function smoothScrollTopRec() {
  const c = document.documentElement.scrollTop || document.body.scrollTop;
  if (c > 0 && globLastC > c) {
    globLastC = c;
    window.requestAnimationFrame(smoothScrollTopRec);
    window.scrollTo(0, c - c / 8);
  } else {
    globLastC = Infinity;
  }
}

function smoothScrollTop() {
  /**
   * Normally this gets called from componentDidMount()
   * Not waiting a tiny fraction of time can lead
   * to shaky behaviour
   */
  setTimeout(() => {
    smoothScrollTopRec();
  }, 10);
}

export default smoothScrollTop;



================================================
FILE: src/shared/functions/stableSort.js
================================================
function stableSort(array, cmp) {
  const stabilizedThis = array.map((el, index) => [el, index]);
  stabilizedThis.sort((a, b) => {
    const order = cmp(a[0], b[0]);
    if (order !== 0) return order;
    return a[1] - b[1];
  });
  return stabilizedThis.map(el => el[0]);
}
export default stableSort;



================================================
FILE: src/shared/functions/toArray.js
================================================
/* eslint-disable */

/**
 * lodash (Custom Build) <https://lodash.com/>
 * Build: `lodash modularize exports="npm" -o ./`
 * Copyright jQuery Foundation and other contributors <https://jquery.org/>
 * Released under MIT license <https://lodash.com/license>
 * Based on Underscore.js 1.8.3 <http://underscorejs.org/LICENSE>
 * Copyright Jeremy Ashkenas, DocumentCloud and Investigative Reporters & Editors
 */

/** Used as references for various `Number` constants. */
const MAX_SAFE_INTEGER = 9007199254740991;

/** `Object#toString` result references. */
const argsTag = "[object Arguments]";

const funcTag = "[object Function]";

const genTag = "[object GeneratorFunction]";

const mapTag = "[object Map]";

const objectTag = "[object Object]";

const promiseTag = "[object Promise]";

const setTag = "[object Set]";

const stringTag = "[object String]";

const weakMapTag = "[object WeakMap]";

const dataViewTag = "[object DataView]";

/**
 * Used to match `RegExp`
 * [syntax characters](http://ecma-international.org/ecma-262/7.0/#sec-patterns).
 */
const reRegExpChar = /[\\^$.*+?()[\]{}|]/g;

/** Used to detect host constructors (Safari). */
const reIsHostCtor = /^\[object .+?Constructor\]$/;

/** Used to detect unsigned integer values. */
const reIsUint = /^(?:0|[1-9]\d*)$/;

/** Used to compose unicode character classes. */
const rsAstralRange = "\\ud800-\\udfff";

const rsComboMarksRange = "\\u0300-\\u036f\\ufe20-\\ufe23";

const rsComboSymbolsRange = "\\u20d0-\\u20f0";

const rsVarRange = "\\ufe0e\\ufe0f";

/** Used to compose unicode capture groups. */
const rsAstral = `[${rsAstralRange}]`;

const rsCombo = `[${rsComboMarksRange}${rsComboSymbolsRange}]`;

const rsFitz = "\\ud83c[\\udffb-\\udfff]";

const rsModifier = `(?:${rsCombo}|${rsFitz})`;

const rsNonAstral = `[^${rsAstralRange}]`;

const rsRegional = "(?:\\ud83c[\\udde6-\\uddff]){2}";

const rsSurrPair = "[\\ud800-\\udbff][\\udc00-\\udfff]";

const rsZWJ = "\\u200d";

/** Used to compose unicode regexes. */
const reOptMod = `${rsModifier}?`;

const rsOptVar = `[${rsVarRange}]?`;

const rsOptJoin = `(?:${rsZWJ}(?:${[rsNonAstral, rsRegional, rsSurrPair].join(
  "|"
)})${rsOptVar}${reOptMod})*`;

const rsSeq = rsOptVar + reOptMod + rsOptJoin;

const rsSymbol = `(?:${[
  `${rsNonAstral + rsCombo}?`,
  rsCombo,
  rsRegional,
  rsSurrPair,
  rsAstral
].join("|")})`;

/** Used to match [string symbols](https://mathiasbynens.be/notes/javascript-unicode). */
const reUnicode = RegExp(`${rsFitz}(?=${rsFitz})|${rsSymbol}${rsSeq}`, "g");

/** Used to detect strings with [zero-width joiners or code points from the astral planes](http://eev.ee/blog/2015/09/12/dark-corners-of-unicode/). */
const reHasUnicode = RegExp(
  `[${rsZWJ}${rsAstralRange}${rsComboMarksRange}${rsComboSymbolsRange}${rsVarRange}]`
);

/** Detect free variable `global` from Node.js. */
const freeGlobal =
  typeof global === "object" && global && global.Object === Object && global;

/** Used as a reference to the global object. */
var root = freeGlobal || Function("return this")();

/**
 * A specialized version of `_.map` for arrays without support for iteratee
 * shorthands.
 *
 * @private
 * @param {Array} [array] The array to iterate over.
 * @param {Function} iteratee The function invoked per iteration.
 * @returns {Array} Returns the new mapped array.
 */
function arrayMap(array, iteratee) {
  let index = -1;

  const length = array ? array.length : 0;

  const result = Array(length);

  while (++index < length) {
    result[index] = iteratee(array[index], index, array);
  }
  return result;
}

/**
 * Converts an ASCII `string` to an array.
 *
 * @private
 * @param {string} string The string to convert.
 * @returns {Array} Returns the converted array.
 */
function asciiToArray(string) {
  return string.split("");
}

/**
 * The base implementation of `_.times` without support for iteratee shorthands
 * or max array length checks.
 *
 * @private
 * @param {number} n The number of times to invoke `iteratee`.
 * @param {Function} iteratee The function invoked per iteration.
 * @returns {Array} Returns the array of results.
 */
function baseTimes(n, iteratee) {
  let index = -1;

  const result = Array(n);

  while (++index < n) {
    result[index] = iteratee(index);
  }
  return result;
}

/**
 * The base implementation of `_.values` and `_.valuesIn` which creates an
 * array of `object` property values corresponding to the property names
 * of `props`.
 *
 * @private
 * @param {Object} object The object to query.
 * @param {Array} props The property names to get values for.
 * @returns {Object} Returns the array of property values.
 */
function baseValues(object, props) {
  return arrayMap(props, key => object[key]);
}

/**
 * Gets the value at `key` of `object`.
 *
 * @private
 * @param {Object} [object] The object to query.
 * @param {string} key The key of the property to get.
 * @returns {*} Returns the property value.
 */
function getValue(object, key) {
  return object == null ? undefined : object[key];
}

/**
 * Checks if `string` contains Unicode symbols.
 *
 * @private
 * @param {string} string The string to inspect.
 * @returns {boolean} Returns `true` if a symbol is found, else `false`.
 */
function hasUnicode(string) {
  return reHasUnicode.test(string);
}

/**
 * Checks if `value` is a host object in IE < 9.
 *
 * @private
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is a host object, else `false`.
 */
function isHostObject(value) {
  // Many host objects are `Object` objects that can coerce to strings
  // despite having improperly defined `toString` methods.
  let result = false;
  if (value !== null && typeof value.toString !== "function") {
    try {
      result = !!`${value}`;
    } catch (e) {}
  }
  return result;
}

/**
 * Converts `iterator` to an array.
 *
 * @private
 * @param {Object} iterator The iterator to convert.
 * @returns {Array} Returns the converted array.
 */
function iteratorToArray(iterator) {
  let data;

  const result = [];

  while (!(data = iterator.next()).done) {
    result.push(data.value);
  }
  return result;
}

/**
 * Converts `map` to its key-value pairs.
 *
 * @private
 * @param {Object} map The map to convert.
 * @returns {Array} Returns the key-value pairs.
 */
function mapToArray(map) {
  let index = -1;

  const result = Array(map.size);

  map.forEach((value, key) => {
    result[++index] = [key, value];
  });
  return result;
}

/**
 * Creates a unary function that invokes `func` with its argument transformed.
 *
 * @private
 * @param {Function} func The function to wrap.
 * @param {Function} transform The argument transform.
 * @returns {Function} Returns the new function.
 */
function overArg(func, transform) {
  return function(arg) {
    return func(transform(arg));
  };
}

/**
 * Converts `set` to an array of its values.
 *
 * @private
 * @param {Object} set The set to convert.
 * @returns {Array} Returns the values.
 */
function setToArray(set) {
  let index = -1;

  const result = Array(set.size);

  set.forEach(value => {
    result[++index] = value;
  });
  return result;
}

/**
 * Converts `string` to an array.
 *
 * @private
 * @param {string} string The string to convert.
 * @returns {Array} Returns the converted array.
 */
function stringToArray(string) {
  return hasUnicode(string) ? unicodeToArray(string) : asciiToArray(string);
}

/**
 * Converts a Unicode `string` to an array.
 *
 * @private
 * @param {string} string The string to convert.
 * @returns {Array} Returns the converted array.
 */
function unicodeToArray(string) {
  return string.match(reUnicode) || [];
}

/** Used for built-in method references. */
const funcProto = Function.prototype;

const objectProto = Object.prototype;

/** Used to detect overreaching core-js shims. */
const coreJsData = root["__core-js_shared__"];

/** Used to detect methods masquerading as native. */
const maskSrcKey = (function() {
  const uid = /[^.]+$/.exec(
    (coreJsData && coreJsData.keys && coreJsData.keys.IE_PROTO) || ""
  );
  return uid ? `Symbol(src)_1.${uid}` : "";
})();

/** Used to resolve the decompiled source of functions. */
const funcToString = funcProto.toString;

/** Used to check objects for own properties. */
const hasOwnProperty = objectProto.hasOwnProperty;

/**
 * Used to resolve the
 * [`toStringTag`](http://ecma-international.org/ecma-262/7.0/#sec-object.prototype.tostring)
 * of values.
 */
const objectToString = objectProto.toString;

/** Used to detect if a method is native. */
const reIsNative = RegExp(
  `^${funcToString
    .call(hasOwnProperty)
    .replace(reRegExpChar, "\\$&")
    .replace(
      /hasOwnProperty|(function).*?(?=\\\()| for .+?(?=\\\])/g,
      "$1.*?"
    )}$`
);

/** Built-in value references. */
const Symbol = root.Symbol;

const iteratorSymbol = Symbol ? Symbol.iterator : undefined;

const propertyIsEnumerable = objectProto.propertyIsEnumerable;

/* Built-in method references for those with the same name as other `lodash` methods. */
const nativeKeys = overArg(Object.keys, Object);

/* Built-in method references that are verified to be native. */
const DataView = getNative(root, "DataView");

const Map = getNative(root, "Map");

const Promise = getNative(root, "Promise");

const Set = getNative(root, "Set");

const WeakMap = getNative(root, "WeakMap");

/** Used to detect maps, sets, and weakmaps. */
const dataViewCtorString = toSource(DataView);

const mapCtorString = toSource(Map);

const promiseCtorString = toSource(Promise);

const setCtorString = toSource(Set);

const weakMapCtorString = toSource(WeakMap);

/**
 * Creates an array of the enumerable property names of the array-like `value`.
 *
 * @private
 * @param {*} value The value to query.
 * @param {boolean} inherited Specify returning inherited property names.
 * @returns {Array} Returns the array of property names.
 */
function arrayLikeKeys(value, inherited) {
  // Safari 8.1 makes `arguments.callee` enumerable in strict mode.
  // Safari 9 makes `arguments.length` enumerable in strict mode.
  const result =
    isArray(value) || isArguments(value) ? baseTimes(value.length, String) : [];

  const length = result.length;

  const skipIndexes = !!length;

  for (const key in value) {
    if (
      (inherited || hasOwnProperty.call(value, key)) &&
      !(skipIndexes && (key === "length" || isIndex(key, length)))
    ) {
      result.push(key);
    }
  }
  return result;
}

/**
 * The base implementation of `getTag`.
 *
 * @private
 * @param {*} value The value to query.
 * @returns {string} Returns the `toStringTag`.
 */
function baseGetTag(value) {
  return objectToString.call(value);
}

/**
 * The base implementation of `_.isNative` without bad shim checks.
 *
 * @private
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is a native function,
 *  else `false`.
 */
function baseIsNative(value) {
  if (!isObject(value) || isMasked(value)) {
    return false;
  }
  const pattern =
    isFunction(value) || isHostObject(value) ? reIsNative : reIsHostCtor;
  return pattern.test(toSource(value));
}

/**
 * The base implementation of `_.keys` which doesn't treat sparse arrays as dense.
 *
 * @private
 * @param {Object} object The object to query.
 * @returns {Array} Returns the array of property names.
 */
function baseKeys(object) {
  if (!isPrototype(object)) {
    return nativeKeys(object);
  }
  const result = [];
  for (const key in Object(object)) {
    if (hasOwnProperty.call(object, key) && key !== "constructor") {
      result.push(key);
    }
  }
  return result;
}

/**
 * Copies the values of `source` to `array`.
 *
 * @private
 * @param {Array} source The array to copy values from.
 * @param {Array} [array=[]] The array to copy values to.
 * @returns {Array} Returns `array`.
 */
function copyArray(source, array) {
  let index = -1;

  const length = source.length;

  array || (array = Array(length));
  while (++index < length) {
    array[index] = source[index];
  }
  return array;
}

/**
 * Gets the native function at `key` of `object`.
 *
 * @private
 * @param {Object} object The object to query.
 * @param {string} key The key of the method to get.
 * @returns {*} Returns the function if it's native, else `undefined`.
 */
function getNative(object, key) {
  const value = getValue(object, key);
  return baseIsNative(value) ? value : undefined;
}

/**
 * Gets the `toStringTag` of `value`.
 *
 * @private
 * @param {*} value The value to query.
 * @returns {string} Returns the `toStringTag`.
 */
let getTag = baseGetTag;

// Fallback for data views, maps, sets, and weak maps in IE 11,
// for data views in Edge < 14, and promises in Node.js.
if (
  (DataView && getTag(new DataView(new ArrayBuffer(1))) !== dataViewTag) ||
  (Map && getTag(new Map()) !== mapTag) ||
  (Promise && getTag(Promise.resolve()) !== promiseTag) ||
  (Set && getTag(new Set()) !== setTag) ||
  (WeakMap && getTag(new WeakMap()) !== weakMapTag)
) {
  getTag = function(value) {
    const result = objectToString.call(value);

    const Ctor = result === objectTag ? value.constructor : undefined;

    const ctorString = Ctor ? toSource(Ctor) : undefined;

    if (ctorString) {
      switch (ctorString) {
        case dataViewCtorString:
          return dataViewTag;
        case mapCtorString:
          return mapTag;
        case promiseCtorString:
          return promiseTag;
        case setCtorString:
          return setTag;
        case weakMapCtorString:
          return weakMapTag;
        default:
          return;
      }
    }
    return result;
  };
}

/**
 * Checks if `value` is a valid array-like index.
 *
 * @private
 * @param {*} value The value to check.
 * @param {number} [length=MAX_SAFE_INTEGER] The upper bounds of a valid index.
 * @returns {boolean} Returns `true` if `value` is a valid index, else `false`.
 */
function isIndex(value, length) {
  length = length == null ? MAX_SAFE_INTEGER : length;
  return (
    !!length &&
    (typeof value === "number" || reIsUint.test(value)) &&
    (value > -1 && value % 1 === 0 && value < length)
  );
}

/**
 * Checks if `func` has its source masked.
 *
 * @private
 * @param {Function} func The function to check.
 * @returns {boolean} Returns `true` if `func` is masked, else `false`.
 */
function isMasked(func) {
  return !!maskSrcKey && maskSrcKey in func;
}

/**
 * Checks if `value` is likely a prototype object.
 *
 * @private
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is a prototype, else `false`.
 */
function isPrototype(value) {
  const Ctor = value && value.constructor;

  const proto = (typeof Ctor === "function" && Ctor.prototype) || objectProto;

  return value === proto;
}

/**
 * Converts `func` to its source code.
 *
 * @private
 * @param {Function} func The function to process.
 * @returns {string} Returns the source code.
 */
function toSource(func) {
  if (func !== null) {
    try {
      return funcToString.call(func);
    } catch (e) {}
    try {
      return `${func}`;
    } catch (e) {}
  }
  return "";
}

/**
 * Checks if `value` is likely an `arguments` object.
 *
 * @static
 * @memberOf _
 * @since 0.1.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is an `arguments` object,
 *  else `false`.
 * @example
 *
 * _.isArguments(function() { return arguments; }());
 * // => true
 *
 * _.isArguments([1, 2, 3]);
 * // => false
 */
function isArguments(value) {
  // Safari 8.1 makes `arguments.callee` enumerable in strict mode.
  return (
    isArrayLikeObject(value) &&
    hasOwnProperty.call(value, "callee") &&
    (!propertyIsEnumerable.call(value, "callee") ||
      objectToString.call(value) === argsTag)
  );
}

/**
 * Checks if `value` is classified as an `Array` object.
 *
 * @static
 * @memberOf _
 * @since 0.1.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is an array, else `false`.
 * @example
 *
 * _.isArray([1, 2, 3]);
 * // => true
 *
 * _.isArray(document.body.children);
 * // => false
 *
 * _.isArray('abc');
 * // => false
 *
 * _.isArray(_.noop);
 * // => false
 */
var isArray = Array.isArray;

/**
 * Checks if `value` is array-like. A value is considered array-like if it's
 * not a function and has a `value.length` that's an integer greater than or
 * equal to `0` and less than or equal to `Number.MAX_SAFE_INTEGER`.
 *
 * @static
 * @memberOf _
 * @since 4.0.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is array-like, else `false`.
 * @example
 *
 * _.isArrayLike([1, 2, 3]);
 * // => true
 *
 * _.isArrayLike(document.body.children);
 * // => true
 *
 * _.isArrayLike('abc');
 * // => true
 *
 * _.isArrayLike(_.noop);
 * // => false
 */
function isArrayLike(value) {
  return value != null && isLength(value.length) && !isFunction(value);
}

/**
 * This method is like `_.isArrayLike` except that it also checks if `value`
 * is an object.
 *
 * @static
 * @memberOf _
 * @since 4.0.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is an array-like object,
 *  else `false`.
 * @example
 *
 * _.isArrayLikeObject([1, 2, 3]);
 * // => true
 *
 * _.isArrayLikeObject(document.body.children);
 * // => true
 *
 * _.isArrayLikeObject('abc');
 * // => false
 *
 * _.isArrayLikeObject(_.noop);
 * // => false
 */
function isArrayLikeObject(value) {
  return isObjectLike(value) && isArrayLike(value);
}

/**
 * Checks if `value` is classified as a `Function` object.
 *
 * @static
 * @memberOf _
 * @since 0.1.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is a function, else `false`.
 * @example
 *
 * _.isFunction(_);
 * // => true
 *
 * _.isFunction(/abc/);
 * // => false
 */
function isFunction(value) {
  // The use of `Object#toString` avoids issues with the `typeof` operator
  // in Safari 8-9 which returns 'object' for typed array and other constructors.
  const tag = isObject(value) ? objectToString.call(value) : "";
  return tag === funcTag || tag === genTag;
}

/**
 * Checks if `value` is a valid array-like length.
 *
 * **Note:** This method is loosely based on
 * [`ToLength`](http://ecma-international.org/ecma-262/7.0/#sec-tolength).
 *
 * @static
 * @memberOf _
 * @since 4.0.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is a valid length, else `false`.
 * @example
 *
 * _.isLength(3);
 * // => true
 *
 * _.isLength(Number.MIN_VALUE);
 * // => false
 *
 * _.isLength(Infinity);
 * // => false
 *
 * _.isLength('3');
 * // => false
 */
function isLength(value) {
  return (
    typeof value === "number" &&
    value > -1 &&
    value % 1 === 0 &&
    value <= MAX_SAFE_INTEGER
  );
}

/**
 * Checks if `value` is the
 * [language type](http://www.ecma-international.org/ecma-262/7.0/#sec-ecmascript-language-types)
 * of `Object`. (e.g. arrays, functions, objects, regexes, `new Number(0)`, and `new String('')`)
 *
 * @static
 * @memberOf _
 * @since 0.1.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is an object, else `false`.
 * @example
 *
 * _.isObject({});
 * // => true
 *
 * _.isObject([1, 2, 3]);
 * // => true
 *
 * _.isObject(_.noop);
 * // => true
 *
 * _.isObject(null);
 * // => false
 */
function isObject(value) {
  const type = typeof value;
  return !!value && (type === "object" || type === "function");
}

/**
 * Checks if `value` is object-like. A value is object-like if it's not `null`
 * and has a `typeof` result of "object".
 *
 * @static
 * @memberOf _
 * @since 4.0.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is object-like, else `false`.
 * @example
 *
 * _.isObjectLike({});
 * // => true
 *
 * _.isObjectLike([1, 2, 3]);
 * // => true
 *
 * _.isObjectLike(_.noop);
 * // => false
 *
 * _.isObjectLike(null);
 * // => false
 */
function isObjectLike(value) {
  return !!value && typeof value === "object";
}

/**
 * Checks if `value` is classified as a `String` primitive or object.
 *
 * @static
 * @since 0.1.0
 * @memberOf _
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns `true` if `value` is a string, else `false`.
 * @example
 *
 * _.isString('abc');
 * // => true
 *
 * _.isString(1);
 * // => false
 */
function isString(value) {
  return (
    typeof value === "string" ||
    (!isArray(value) &&
      isObjectLike(value) &&
      objectToString.call(value) === stringTag)
  );
}

/**
 * Converts `value` to an array.
 *
 * @static
 * @since 0.1.0
 * @memberOf _
 * @category Lang
 * @param {*} value The value to convert.
 * @returns {Array} Returns the converted array.
 * @example
 *
 * _.toArray({ 'a': 1, 'b': 2 });
 * // => [1, 2]
 *
 * _.toArray('abc');
 * // => ['a', 'b', 'c']
 *
 * _.toArray(1);
 * // => []
 *
 * _.toArray(null);
 * // => []
 */
function toArray(value) {
  if (!value) {
    return [];
  }
  if (isArrayLike(value)) {
    return isString(value) ? stringToArray(value) : copyArray(value);
  }
  if (iteratorSymbol && value[iteratorSymbol]) {
    return iteratorToArray(value[iteratorSymbol]());
  }
  const tag = getTag(value);

  const func =
    tag === mapTag ? mapToArray : tag === setTag ? setToArray : values;

  return func(value);
}

/**
 * Creates an array of the own enumerable property names of `object`.
 *
 * **Note:** Non-object values are coerced to objects. See the
 * [ES spec](http://ecma-international.org/ecma-262/7.0/#sec-object.keys)
 * for more details.
 *
 * @static
 * @since 0.1.0
 * @memberOf _
 * @category Object
 * @param {Object} object The object to query.
 * @returns {Array} Returns the array of property names.
 * @example
 *
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.keys(new Foo);
 * // => ['a', 'b'] (iteration order is not guaranteed)
 *
 * _.keys('hi');
 * // => ['0', '1']
 */
function keys(object) {
  return isArrayLike(object) ? arrayLikeKeys(object) : baseKeys(object);
}

/**
 * Creates an array of the own enumerable string keyed property values of `object`.
 *
 * **Note:** Non-object values are coerced to objects.
 *
 * @static
 * @since 0.1.0
 * @memberOf _
 * @category Object
 * @param {Object} object The object to query.
 * @returns {Array} Returns the array of property values.
 * @example
 *
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.values(new Foo);
 * // => [1, 2] (iteration order is not guaranteed)
 *
 * _.values('hi');
 * // => ['h', 'i']
 */
function values(object) {
  return object ? baseValues(object, keys(object)) : [];
}

module.exports = toArray;



================================================
FILE: src/shared/functions/unixToDateString.js
================================================
function unixToDateString(unix) {
  const date = new Date(unix * 1000);
  return (
    `${date.getDate()}.${date.getMonth() + 1}.${date.getFullYear()}`
  );
}

export default unixToDateString;



================================================
FILE: src/shared/functions/useLocationBlocker.js
================================================
import { useHistory } from "react-router-dom";
import { useEffect } from "react";


const useLocationBlocker = () => {
  /** 
   * Prevents react-router from pushing the same
   * page to the history twice which leads to
   * multiple clicks on the back icon of the browser
   * being necessary to go back into the history.
  */
  const history = useHistory();
  useEffect(
    () =>
      history.block(
        (location, action) =>
          action !== "PUSH" ||
          getLocationId(location) !== getLocationId(history.location)
      ),
    [] // eslint-disable-line react-hooks/exhaustive-deps
  );
}

const getLocationId = ({ pathname, search, hash }) => {
  return pathname + (search ? "?" + search : "") + (hash ? "#" + hash : "");
}

export default useLocationBlocker;


================================================
FILE: src/shared/functions/useWidth.js
================================================
import { useTheme } from "@mui/material/styles";
import useMediaQuery from "@mui/material/useMediaQuery";

/**
 * Be careful using this hook. It only works because the number of
 * breakpoints in theme is static. It will break once you change the number of
 * breakpoints. See https://reactjs.org/docs/hooks-rules.html#only-call-hooks-at-the-top-level
 */
function useWidth() {
  const theme = useTheme();
  const keys = [...theme.breakpoints.keys].reverse();
  return (
    keys.reduce((output, key) => {
      // eslint-disable-next-line react-hooks/rules-of-hooks
      const matches = useMediaQuery(theme.breakpoints.up(key));
      return !output && matches ? key : output;
    }, null) || "xs"
  );
}

export default useWidth;



================================================
FILE: .github/dependabot.yml
================================================
version: 2
updates:
- package-ecosystem: npm
  directory: "/"
  schedule:
    interval: daily
    time: "04:00"
  open-pull-requests-limit: 10
  reviewers:
  - dunky11
  ignore:
  - dependency-name: "@date-io/date-fns"
    versions:
    - ">= 2.3.a, < 2.4"
  - dependency-name: "@date-io/date-fns"
    versions:
    - ">= 2.4.a, < 2.5"
  - dependency-name: "@date-io/date-fns"
    versions:
    - ">= 2.a, < 3"
  - dependency-name: workbox-strategies
    versions:
    - 6.1.5
  - dependency-name: "@testing-library/react"
    versions:
    - 11.2.6
  - dependency-name: "@testing-library/user-event"
    versions:
    - 12.6.3
    - 12.7.2
    - 13.0.10
    - 13.0.13
    - 13.0.6
    - 13.0.7
  - dependency-name: workbox-google-analytics
    versions:
    - 6.1.1




================================================
FILE: .github/workflows/nodejs.yml
================================================
name: Node.js CI

on:
  push:
    branches: 
      - master 

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [12.x]

    steps:
    - uses: actions/checkout@v2
    - name: Use Node.js ${{ matrix.node-version }}
      uses: actions/setup-node@v1
      with:
        node-version: ${{ matrix.node-version }}
    - run: npm install
    - run: ./node_modules/eslint/bin/eslint.js src --max-warnings=0
    - run: npm run build
    - run: npm run test
      env:
        CI: true

