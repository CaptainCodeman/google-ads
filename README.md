[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/CaptainCodeman/google-ads)

_[Demo and API docs](http://captaincodeman.github.io/google-ads/)_

# Google-Ads

Polymer elements to show Google ads.

Normal attempts to insert Adsense or Dfp ads into sites that user Polymer /
WebComponents will often fail due to the ad-scripts being incompatible with
shadow-dom.

These elements work by creating a div in the page root to shadow the ad
element within any view (keeping it positioned correctly etc...)

## \<dfp-lite-ad\>

`dfp-lite-ad` is an element to show Google Dfp lite ads within Polymer apps.

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="dfp-lite.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<dfp-lite-ad ad-unit-path="/559809888/polymer"></dfp-lite-ad>
```

### Options

* adUnitPath
* clickUrl
* pageUrl
* cookieOptOut
* targeting
* categoryExclusions
* tagForChildDirectedTreatment

## \<adsense-ad\>

`adsense-ad` is an element to show Google Adsense ads within Polymer apps.

(not yet implemented)
