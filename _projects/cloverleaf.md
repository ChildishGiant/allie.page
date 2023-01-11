---
layout: project
title: Cloverleaf
description: A smart solution to the problem of passwords.
img: assets/img/cloverleaf.png
importance: 1
category: current
github: https://github.com/cloverleaf/web
---

Cloverleaf is a complete redesign of the traditional password generator/storage system. Instead of relying on a hard drive
to not to fail, or that backup you keep forgetting to make, Cloverleaf makes a password based on your master password and
the application you want a password for. This generated password will be the same every time, no matter what device you're
on. You can then copy this and paste it into the app you want to log into.

Cloverleaf is my pet project and certainly the project I've sunk the most time and effort into. Not only with the
actual web dev but branding and considering each feature. The website itself is, however, PWA compliant so can
*magically* act as if it were a native app on different operating systems. Sadly that's just in theory and in reality,
non-native apps stick out like a sore thumb as of recently so I've been putting off completely remaking it.
So far I've split it off into an NPM module so it can be integrated into different environments (so far just web and a browser extension).


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0 align-middle d-flex">
        {% include figure.html path="assets/img/cloverleaf-screenshot.png" title="cloverleaf screenshot" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0 align-middle d-flex">
        {% include figure.html path="assets/img/cloverleaf-mobile.png" title="cloverleaf mobile screenshot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
		Screenshots of Cloverleaf on both desktop and mobile, in a white theme and a dark purple theme.
</div>

### Technologies used include:

- Node.js [(repo)](https://github.com/cloverleaf/npm)
- Python & Selenium [(repo)](https://github.com/cloverleaf/web/tree/master/unit_tests)
- Chai [(repo)](https://github.com/cloverleaf/npm/tree/master/test)
- esbuild [(repo)](https://github.com/cloverleaf/web/tree/master/config/esbuild)
- GitHub Actions for deployment and CI