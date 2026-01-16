Overview

This is a simple full-screen image widget for EdgeTX 2.11+ radios with large color displays (such as the RadioMaster TX16S).
The widget displays a single PNG image scaled to fit the screen. The image filename is user-selectable via the widget settings, allowing easy customization without editing the Lua code.
This widget is intentionally minimal and stable, focusing on reliable image loading and display using the EdgeTX widget API.

Features
- Full-screen image display (480×272)
- User-selectable image filename via widget options
- Automatic scaling and centering
- Optimized to load using the APP widget layout
- No telemetry or model dependencies
- Works on EdgeTX 2.11+
- Image files must be stored inside the images folder

Possible Use Cases
- Screen Saver: Display a custom image when the radio is idle, such as a logo, call sign, or dark-themed background.
- Notes / Reference Page: Show important information like switch assignments, failsafe notes, battery limits, or setup reminders.
- Model Photo: Display a photo or rendered image of the currently selected model for quick visual identification.
- Branding or Personalization: Add a personal logo, club branding, or event-specific image.
