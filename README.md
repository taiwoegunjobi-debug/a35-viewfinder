# A35 Viewfinder Pro

A practical smartphone viewfinder designed around an ARRI ALEXA 35 + Super 35 anamorphic workflow.

## What is new
- ALEXA 35 sensor-mode selector using official active-image dimensions.
- ARRI/ZEISS Master Anamorphic library: 28/35/40/50/60/75/100/135/180mm.
- Atlas Orion anamorphic library: 18/21/25/28/32/40/50/65/80/100/135/200mm.
- Horizontal AOV data for the lens libraries.
- Pixel 6 Pro camera profiles (main, telephoto, ultrawide) and custom FOV calibration.
- Automatic phone crop/zoom estimate to approximate the selected ALEXA 35 lens framing.
- 2.39:1 monitoring frame.
- Reference still overlay.
- Shot metadata and local shot library.
- Depth-of-field calculator.
- Camera height, subject distance and focus-distance fields.
- FPS and movement/notes fields.
- PWA installability.

## Accuracy note
The ALEXA 35 calculations are based on ARRI's published sensor dimensions. The phone view is still a simulation: browser camera streams, stabilization, lens correction and manufacturer processing mean it cannot reproduce the optical rendering, distortion, bokeh, flare, breathing or focus characteristics of a physical anamorphic lens.

## Deploy
Upload the files to Vercel or connect the folder/repository to Vercel. Camera access requires HTTPS. On Android Chrome, open the deployed site and install it from the browser menu.

## Next native upgrade
A native Android/CameraX/Camera2 version can access more camera controls, query camera characteristics, lock exposure/focus where supported, and calibrate each physical phone camera more precisely.
