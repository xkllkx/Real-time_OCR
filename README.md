# Real-time OCR
This repository will capture screenshots of the selected area on the website and perform OCR to extract target data.

# Derivative side-project [Tradingveiw_data_scraper](<https://github.com/xkllkx/Tradingveiw_data_scraper>)

# Installation
- Python requirements
```bash
pip install opencv-python
pip install pytesseract
pip install Pillow
pip install pynput
```
- [Tesseract](<https://github.com/tesseract-ocr/tesseract>)
  - Tesseract Path, e.g., C://Program Files//Tesseract-OCR//tesseract.exe

# How to use this repo
1. Remember to update Tesseract Path
```python
pytesseract.pytesseract.tesseract_cmd = 'C://Program Files//Tesseract-OCR//tesseract.exe'
```

2. Run picture_detect_word.py.
```bash
python picture_detect_word.py
```
3. Select Screenshot Area.
When prompted, select the top-left and bottom-right corners of the area you want to capture on the screen.
Confirm the selection by typing Y or y.

# Note
- Ensure the selected area for screenshots does not include Chinese characters or paths with special characters to avoid issues.
- The script captures and processes images in real-time, so make sure your system has sufficient resources for smooth operation.
