Checkout my other widgets:

https://github.com/moshirfakhoury/edgetx-preflighttest-widget

https://github.com/moshirfakhoury/edgetx-flightdash-widget

https://github.com/moshirfakhoury/edgetx-postflight-widget

https://github.com/moshirfakhoury/edgetx-servicechecklist-widget

Overview

This is a full-screen image widget for EdgeTX 2.11+ radios with large color displays (e.g., RadioMaster TX16S). The widget displays PNG images scaled to fit the screen and supports multiple images selectable via widget options. It is simple, stable, and flexible, allowing easy customization without editing the Lua code. A key feature is the built-in slideshow, which can automatically cycle through multiple images every 8 seconds.

Features
- Full-screen image display (480×272)
- User-selectable image filenames via widget options (up to 8 images)
- Automatic .png file extension handling
- Slideshow mode: automatically cycles through non-empty images every 8 seconds
- Numeric selection of a single image via the Select parameter (1–8)
- Images are automatically scaled and centered
- Optimized for use in APP widget layout
- No telemetry or model dependencies
- Compatible with EdgeTX 2.11+
- Image files must be stored inside the images folder
- Image names can be up to 12 characters long; .png is automatically appended if omitted


Possible Use Cases
- Screen Saver: Display a custom image when the radio is idle, such as a logo, call sign, or dark-themed background.
- Notes / Reference Page: Show important information like switch assignments, failsafe notes, battery limits, or setup reminders.
- Model Photo: Display a photo or rendered image of the currently selected model for quick visual identification.
- Branding or Personalization: Add a personal logo, club branding, or event-specific image.

Usage Notes
- Image names can be up to 12 characters long; .png is automatically appended if omitted
- Empty image slots are ignored in slideshow mode
- If a specified image file cannot be found, an empty widget is returned - no errors
- The slideshow loops continuously through available images

Installation
- Download the ZIP file
- Extract the contents of the ZIP file
- Find the last folder named Images (it contains main.lua, README.txt, and images folder)
- Copy only the Images folder
- Paste it into your SDCard/WIDGETS directory

<img width="493" height="287" alt="image" src="https://github.com/user-attachments/assets/c6520b4d-965b-462d-a982-126b94d89599" />

