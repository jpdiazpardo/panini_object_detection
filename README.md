# panini_object_detection
For this computer vision (CV) project I developed an automatic image detection system capable of recognizing and tagging player images from the official Qatar 2022 Panini® sticker album. To achieve this, I built a training dataset leveraged mostly on an eBay web scrapping algorithm to retrieve player stickers from various participating countries including the official extra legend stickers. Each image was labeled to detect a 'panini' object and the corresponding player 'name'. Once the model reaches an acceptable confidence threshold, I use an optical character recognition (OCR) engine to 'read' the text from the 'name' label and tag automatically the corresponding player image. Finally, I deployed the model on live footage to validate my AI product and obtained very good results based on my initial objectives.

**NOTE:** For this project, other types of stickers included in the Qatar 2022 album such as: team crests, stadiums, team pictures and other miscellaneous stickers are out of scope. Past editions of Panini® sticker albums i.e. Russia 2018, Brazil 2014, South Africa 2010, etc. are out of scope as well.

## Image detection
![Alt text](images/cr7_image_detection.png?raw=true)
