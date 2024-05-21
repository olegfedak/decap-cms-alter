# Alternative Decap CMS Package
This package is built on top of the [forked Decap CMS](https://github.com/olegfedak/decap-cms). 
As a new version of Decap interface is being implemented, I would like to preserve the existing user experience.

## General changes
1. Optimized for the mobile screens:
    - Content page
    - Editor
    - Workflow
    - Media 
2. Widgets are displayed in a single view.
3. Minor visual design updates to interface elements.

## Just try it
For the testing include the link into your `admin/index.html` instead of the official: 

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="robots" content="noindex" />
    <title>Content Manager</title>
  </head>
  <body>
    <!-- <script src="https://unpkg.com/decap-cms@^3.1.10/dist/decap-cms.js"></script> -->
    <script src="https://olegfedak.github.io/decap-cms-alter/decap-cms.js"></script>
  </body>
</html>
```
[Official Install Decap CMS](https://decapcms.org/docs/install-decap-cms/)

## Versions 
Currently are tested on v3.1.10
