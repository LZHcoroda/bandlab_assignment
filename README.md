# README

## Pre-empt

The code in the HTML pages uses in-browser babel and the dev-build of React in the browser.

## Why Babel?

Babel allow the use of more advanced JavaScript feature by converting code written in 
ECMAScript2015+ into backwards-compatible JavaScript that the browser can understand and
enables me to code React in JSX

## Why React?

Developing in React helps me build a more maintainable and scalable application while leveraging the feature offered by React Hooks. In this small demo, it may not add a whole lot but if we needed to change the requirements (e.g. add more samples) I will be able to do that easily and quickly.

## Netlify Link

See the web application without running on a local web server!

Link: https://astonishing-rabanadas-eff294.netlify.app/

## Running on a local web server

Issue: if opened locally from the **filesystem**, outbound requests will fail because of CORS restrictions in the browser, so a local web server using serve or http-server or similar is needed.

reference: https://www.mozilla.org/en-US/security/advisories/mfsa2019-21/#CVE-2019-11730

### Node.js

If you use Node.js and have already installed it along with NPM, the http-server module can be a good choice for this purpose.

Run the following command to install the http-server module globally on your machine so that you can run it from any directory via the command line:

```
$  npm install http-server -g
```

Once the installation is completed, you can run the http-server command inside any directory to launch a web server.

### VS Code

If you are using visual studio code, you can quickly start a local live server using the "Live Server" extension.

Link: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer