Intro:

## Background

Couple of static images showing player, blog posts with embedded, etc.
(these are slide-like)

* How it all started, Digirati, Wellcome, DDS, Player... v brief
* Wellcome Player - Silo, bespoke data format
* Audio, Video, Born-Digital: Explain how Player design modular from the start which sets up nicely for IxIF later
* Heard about IIIF and did an Image API test
* Made Player open source (some adoption)

## 2014

* BL do a competitive design review of viewers
* They like the Wellcome Player; see that it can be basis of their "Universal Viewer" project
* BL were there at the start of IIIF, skin in the game
* The **Universal Viewer** is born, as a concept

## Late 2014-early 2015: British Library

[(DEMOS) - Wunder der Vererbung](http://universalviewer.io/examples/?manifest=http://tomcrane.github.io/presentations/uv-ghent/manifests/wunder-dds.json)
* Digirati make Universal Viewer with BL
* Convert Existing features:
  * Deep Zoom
  * Thumbnails
  * Contents
  * Page Navigation
* Lots of new features, IIIF support
  * Super thumbs, scalable
  * 2-up
  * Theming (show the [same book](http://wellcomelibrary.org/item/b18035723) at Wellcome)
  * metadata, rights and licensing
  * settings
* New home at github.com/universalviewer

## 2015: National Library of Wales

* Add Internationalisation support (DEMO) - Glen add one, otherwise use W der V

## 2015: Wellcome Library

* Aim for feature parity with Player, so Wellcome can go fully IIIF
* Event firing (for GA, bookmarking etc)
* requires non-IIIF features: (DEMOS)
  * Authentication:
    * b19831079 -  ["A Protein: Miscellaneous"](http://wellcomelibrary.org/item/b19831079) (CAS - sign in at Wellcome)
    * b11599820 -  [Sixteen feet in profile, of women and men](http://wellcomelibrary.org/item/b11599820) (Degraded)
    * b19831122 -  ["6th Layer Line"](http://wellcomelibrary.org/item/b19831122) (Clickthrough)
    * b18174942 -  ['1989 Neural Edelmanism'](http://wellcomelibrary.org/item/b18174942) ("Pure" clickthrough)
    * mention: "AVOID POPUPS" because mobile...
  * Search: b18246813 - [(MoH report)](http://universalviewer.io/examples/?manifest=http://wellcomelibrary.org/iiif/b18246813/manifest)
  * (Auth and Search inform the newest IIIF specs)
  * Audio b17307922 - [(Florence Nightingale)](http://universalviewer.io/examples/?manifest=http://wellcomelibrary.org/iiif/b17307922/manifest)
  * Video b16659090 - [(The story of the Wellcome Foundation)](http://universalviewer.io/examples/?manifest=http://wellcomelibrary.org/iiif/b16659090/manifest)
  * Born-Digital b17502792 - [(Science and the public)](http://universalviewer.io/examples/?manifest=http://wellcomelibrary.org/iiif/b17502792/manifest)
  * (explain how the Presentation API is extensible; these are manifests too! Bare minimum to meet Wellcome reqt)

## 2015 - community

* More features (DEMOS)
  * Back to [Wunder der Vererbung](http://universalviewer.io/examples/?manifest=http://tomcrane.github.io/presentations/uv-ghent/manifests/wunder-dds.json)
  * Download menu
  * config editing
  * Collections allow us to model:
    * [multi-volume works](http://universalviewer.io/examples/?manifest=http://wellcomelibrary.org/iiif/collection/b18031511)
    * [Periodicals](http://wellcomelibrary.org/iiif/collection/b19974760) (Chemist and Druggist)
  * ...more
* UV in use: [(updates)](https://github.com/UniversalViewer/universalviewer/wiki/Examples-of-Use)
  * Wellcome Library
  * [British Library](http://access.bl.uk/item/viewer/ark:/81055/vdc_100022545251.0x000002)
  * National Library of Wales (Get good example from Glen)
  * [Digital.Bodleian](http://digital.bodleian.ox.ac.uk/inquire/Discover/Search/#/?p=c+2,t+euclid,rsrs+0,rsps+10,fa+,so+ox%3Asort%5Easc,scids+,pid+,vi+)
  * [Villanova University](http://digital.library.villanova.edu/Item/vudl:24299/Viewer#?si=0&ci=0)
  * more...

## 2016

* Adopt IxIF as it emerges
* More Features - annotations
* Save our Sounds (ask BL about this first)
* More adoption
* More collaborators


## To finish
