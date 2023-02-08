# Text Watermark Remover Images
This Script uses keras_ocr and cv2 modules in python to remove specific text from images.
## How it works:
- It uses Keras_ocr to process the image and detect all texts with coordinates on each letter
- It will process each letter to get the word and then a paragraph if it exists
- User will be promped with an input which will ask for specific works or paragraphs to be removes
- It will search for those paragraphs and if it finds it, it will get coordinates.
- Those coordinates will be processed with "cv2" mask feature which basically will remove the text and will match the background
