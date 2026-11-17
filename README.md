# Bobby Argenis Galleria

Website: https://propmt.argenis.net

## Run locally

No installation or build step. Run `python3 -m http.server 3000` in this repository and open http://localhost:3000.

## Deployment

Netlify deploys main and publishes the repository root. `.netlify/` is excluded from Git. index.html contains semantic HTML, optimized still artwork, styles, navigation, water/fog effects and playback controls. flight-media.js contains the optimized H.264 flight clip as a data URL, hosted with the site. No runtime API key or Fal connection is required.

## Experience

The fixed hero is the entire navigation interface. Six showcase floors, Selected work, Approach and Contact open in-place panels. No scrolling or pointer parallax. The waterfall and pool use masked animated SVG displacement. Forest fog uses a softly masked procedural atmosphere. The spacecraft takeoff comes from Fal, with tracking compensation to hold the rooftop in place. Flight plays once, while the environment continues. Pause scene and Replay flight are available. Reduced-motion preference starts with the still image. Hidden pages pause movement. The poster and navigation remain available if video fails.

## Media provenance

Fal endpoint: lightricks/ltx-2.5/image-to-video/pro. Request: 01a1ea89-889a-7870-b3cc-a2db33c68b85. Ten-second silent architectural animation generated from the approved gallery artwork. The camera in the generated take required stabilization. Only the rooftop/sky region is composited from the video, preserving the building geometry for navigation. The clip was encoded to web-friendly H.264 and included in the repository.

## Content awaiting review

Project descriptions, approved screenshots, release links and public contact details remain placeholders. Exhibit screens are illustrative generated artwork.
