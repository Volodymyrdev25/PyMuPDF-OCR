# PyMuPDF-OCR
* PDF2PNG.py：Complete the conversion from PDF to PNG, using the PyMuPDF library
* OCR.py：Use Baidu OCR-api to realize text recognition of PNG images, convert them to export.txt files and save them
* FileRename.py：Use regular matching to extract key information from txt files, and use it to rename the original PDF file

```
Run:
1. Run PDF2PNG first to convert the PDF in the folder into PNG files in the same folder
2. Then put all PNGs in the newly created picture folder in the original folder, and then run OCR to recognize the pictures
3. The recognition results will be saved in export.txt in the original folder
4. Next, run FileRename, read the txt file, match the regular expression, extract key information, and complete the file renaming
