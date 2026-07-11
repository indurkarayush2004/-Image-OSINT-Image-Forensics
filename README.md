# -Image-OSINT-Image-Forensics

<img width="1536" height="1024" alt="imageosint" src="https://github.com/user-attachments/assets/fd709d47-e2d1-4d33-ad48-b3aa986d3e61" />

### Introduction to Image Forensics

- Image Forensics is the process of examining digital images to determine their authenticity, origin, and any modifications they may have undergone. It combines techniques from computer vision, digital forensics, and Open Source Intelligence (OSINT) to extract valuable information hidden within or associated with an image.

- Using image forensic techniques, investigators and researchers can analyze metadata (EXIF), detect image manipulation, identify the device used to capture the image, recover hidden details, perform reverse image searches, extract embedded text (OCR), and gather clues about the location, date, and context of an image.

- Image forensics plays a crucial role in cybersecurity, digital investigations, journalism, law enforcement, fact-checking, and social media verification. As manipulated and AI-generated images become increasingly common, the ability to verify the authenticity of digital images has become an essential skill.

- This repository is designed to provide practical knowledge, tools, and techniques for learning image forensic analysis in an ethical and responsible manner.

## The Very Basic Thing to Know abou any image for OSINT, important question to Know about image

- ✅ When was the photo taken? (Date & Time)
- ✅ Which mobile phone or camera was used to take it?
- ✅ Has the image been edited? If yes, who edited it (if detectable)?
- ✅ What is the location (GPS coordinates), if it is saved in the metadata?
- ✅ Is it the original image or a fake/manipulated one?
- ✅ Has this image been uploaded to the internet before?
- ✅ Where else has the same image been used?
- ✅ Is the image AI-generated or a real photograph?
- ✅ What objects are present in the image?
- ✅ Can you extract any text visible in the image? (OCR)

Types of Image Investigation

1️⃣ Metadata (EXIF Analysis)
👉 This tells technical details stored inside the image.
You can find:

Date & Time photo was taken
Camera/Mobile model
Lens information
GPS Location (if enabled)
Image Resolution
ISO, Aperture, Shutter Speed
Software used for editing

⚠️ Note: WhatsApp, Instagram, Facebook, etc. usually remove most EXIF data.

2️⃣ Reverse Image Search
Purpose:

Find where the image was uploaded.
Original source.
Similar images.
Fake or edited image detection.

Tools:

Google Lens
Bing Visual Search
Yandex Images
TinEye

3️⃣ Visual Analysis
By looking at the image you can identify:

Location
Language on boards
Vehicle numbers
Buildings
Weather
Season
Time of day
Clothes
Uniforms
Brands
Logos
Objects

4️⃣ Image Forensics
Used to check:

Is image edited?
Photoshop used?
AI Generated?
Cropped?
Manipulated?

Methods:

Error Level Analysis (ELA)
Noise Analysis
Shadow Analysis
Compression Analysis
Clone Detection

5️⃣ Geolocation
Find where image was taken.

Use:

Google Maps
Google Earth
Street View
Mapillary

Compare:

Buildings
Roads
Mountains
Trees
Shops
Sign Boards

6️⃣ People Identification
Possible Information:

Public profile (only if publicly available)
Celebrity
Profession
Uniform
Organization

⚠️ You can't reliably identify private people from a photo alone, and doing so may not be possible or appropriate.

7️⃣ Object Identification
Identify:

Car Model
Bike
Animals
Plants
Products
Electronics
Food
Weapons (for general recognition only)

Tools:

Google Lens
ChatGPT
Image Recognition AI

8️⃣ Text Extraction (OCR)
Extract text from image.

Can detect:

Phone Numbers
Addresses
Emails
Documents
Bills
Sign Boards

Tools:

Google Lens
OCR Software
ChatGPT

9️⃣ AI Detection
Check whether image is AI generated.

Look for:

Weird fingers
Strange shadows
Extra objects
Unrealistic reflections
Inconsistent text

🔟 Editing History
Sometimes you can detect:

Cropping
Filters
Screenshot
Editing software
Compression

📚 Complete Investigation Steps

Step 1 ✅ Observe image carefully.

Step 2 ✅ Check Metadata (EXIF).

Step 3 ✅ Do Reverse Image Search.

Step 4 ✅ Zoom and inspect every corner.

Step 5 ✅ Extract all visible text (OCR).

Step 6 ✅ Identify objects.

Step 7 ✅ Check location clues.

Step 8 ✅ Verify date/time if available.

Step 9 ✅ Check if image is edited.

Step 10 ✅ Cross-check everything with trusted sources.

🛠️ Useful Tools

✔ Google Lens
✔ TinEye
✔ Yandex Images
✔ Bing Visual Search
✔ EXIF Viewer
✔ ExifTool
✔ Jeffrey's EXIF Viewer
✔ FotoForensics
✔ Google Maps
✔ Google Earth
✔ Street View

🎯 What can REALLY be found from an image?

- ✅ Camera Model
- ✅ Mobile Model
- ✅ Date Taken (if EXIF exists)
- ✅ Time Taken
- ✅ GPS Location (if available)
- ✅ Resolution
- ✅ Camera Settings
- ✅ Software Used
- ✅ Editing Clues
- ✅ Original Upload Source
- ✅ Similar Images
- ✅ Visible Text
- ✅ Objects
- ✅ Landmarks
- ✅ Possible Location
- ✅ Weather Clues
- ✅ Approximate Time of Day

- ❌ What usually CANNOT be found from an image alone?

- ❌ Photographer's name (unless recorded or publicly known)
- ❌ Exact address (unless visible or GPS exists)u
- ❌ Owner's personal details
- ❌ Passwords
- ❌ Deleted information
- ❌ Hidden information that was never stored

## Let's Get started With the hands-on real Project.
