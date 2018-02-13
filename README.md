# RussianOCR
This bash script will prompt user to submit an image of Russian text in terminal window. Then the script will convert the image into a workable text document. This will run on both Mac and Linux. This is version 2. Notes: accuracy of conversion depends on quality of the image, as well as the limitations of the tesseract OCR engine.

For this script to work, the tesseract OCR engine must be installed. The instructions for installation vary from OS and OS variant, but below is an example for Debian/Ubuntu distros:
1. Install tesseract: sudo apt update sudo apt install tesseract-ocr
2. Install Russian language package:sudo apt-get install tesseract-ocr-rus
3. If your system does not already have imagemagick, it can be installed: sudo apt-get install imagemagick
4. Make the script executable: chmod +x /path/to/RussianOCR

Instructions for use:
1. For best results, scans should be set to 300 dpi or better.
1. Add script to $PATH or place script in location where image is.
2. Open terminal and navigate to the location in step 1.
3. Execute the script: ./RussianOCR
4. type the name of script without extension.
5. In a moment, a file will appear labeled "Русский-текст"
