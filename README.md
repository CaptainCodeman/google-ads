_[Demo and API docs](http://captaincodeman.github.io/google-ads/)_

# Google-Ads

Elements to show Google ads within Polymer apps.

Normal attempts to insert Adsense or Dfp ads into sites that user Polymer /
WebComponents will often fail due to the ad-scripts being incompatible with
shadow-dom.

These elements work by creating a div in the page root to shadow the ad
element within any view (keeping it positioned correctly etc...)

## \<dfp-lite-ad\>

`dfp-lite-ad` is an element to show Google Dfp lite ads within Polymer apps.

```
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
