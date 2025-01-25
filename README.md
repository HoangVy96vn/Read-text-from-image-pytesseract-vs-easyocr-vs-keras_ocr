# Read-text-from-image-pytesseract-vs-easyocr-vs-keras_ocr

Learn from Rob Mullar tutorial: https://www.youtube.com/watch?v=oyqNdcbKhew
Rob Kaggle link: https://www.kaggle.com/code/robikscube/extracting-text-from-images-youtube-tutorial

Purpose: run pytessaract, easyocr and keras_ocr method to read text from images.
The result:
- pytessaract shows not effective on complex images.
- easyocr is the most effective (I think) because it read text in full context while keras break text into small words and sometime it shows seperated letters which could not provide any useful information.
