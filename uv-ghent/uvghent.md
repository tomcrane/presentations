15 minutes; allow 1-2 mins for questions at end

# The brief

> We would greatly appreciate it if you would speak at the IIIF dissemination event in Ghent in December about the Universal Viewer, particularly with a focus on the implementation of the Presentation API. The aim for the presentation is to be inspirational and demonstrate the value of IIIF adoption, rather than any technical details.  Compared to the DC event, it would be great to focus on the features and uses of the viewer, rather than the ease of installation.

>You would again have a 15 minute slot, with the possibility of one question, and the rest being held for the Q&A session afterwards.

# The Presentation

No slides - just live demos

## Background (very brief)

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

(DEMOS) - use http://tomcrane.github.io/presentations/uv-ghent/manifests/wunder-dds.json
* Digirati make Universal Viewer with BL
* Convert Existing features:
  * Deep Zoom
  * Thumbnails
  * Contents
  * Page Navigation
* Lots of new features, IIIF support
  * Super thumbs, scalable
  * 2-up
  * Theming (show the same book at http://wellcomelibrary.org/item/b18035723)
  * metadata, rights and licensing
  * settings
* New home at github.com/universalviewer

## 2015: National Library of Wales

* Add Internationalisation support (DEMO)

## 2015: Wellcome Library

* Aim for feature parity with Player, so Wellcome can go fully IIIF
* Event firing (for GA, bookmarking etc)
* requires non-IIIF features: (DEMOS)
  * Authentication http://wellcomelibrary.org/item/b19831079 (CAS - sign in with Twitter)
  * Search http://wellcomelibrary.org/item/b18246813 (MoH report, not too big)
    * These two inform the newest IIIF specs
  * Audio
  * Video
  * Born-Digital
  * (explain how the Presentation API is extensible; these are manifests too! Bare minimum to meet Wellcome reqt)

## 2015 - community

* More features (DEMOS)
  * Download menu
  * config editing
  * Collections
    * To model multi-volume works
    * navDate for date UI (Chemist and Druggist)
  * ...more
* Adopted by: (brief flash of examples from different places)
https://github.com/UniversalViewer/universalviewer/wiki/Examples-of-Use
  * Wellcome Library
  * British Library
  * National Library of Wales
  * Digital.Bodleian
  * Villanova
  * etc (add more)

## 2016

* Adopt IxIF as it emerges
* More Features - annotations
* Save our Sounds (ask BL about this first)
* More adoption
* More collaborators


## And another thing...

* 3D
