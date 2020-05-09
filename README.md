# Vehicle-Number-Plate-Reading

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                  [![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)          [![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)

 [![GitHub forks](https://img.shields.io/github/forks/arbazkhan4712/Number-Plate-Recognition?style=social)](https://GitHub.com/Naereen/StrapDown.js/network/)                 [![GitHub star](https://img.shields.io/github/stars/arbazkhan4712/Number-Plate-Recognition?style=social)](https://GitHub.com/Naereen/StrapDown.js/network/)




This project is used to read the images of the vehicle licence number, convert that licence number to text and store the licence of it in a CSV file with date and time.

## Application
This project can be used in parking area to keep track of every vehicle and make parking process easier. 

## Demo
![Image](https://github.com/vjgpt/Vehicle-Number-Plate-Reading/blob/c06ff5289654afb5360c4d97ef66c448e43e4b5e/output.png)

## Dependencies
- OpenCV
- Pandas
- [Tesseract 4](https://github.com/tesseract-ocr/tesseract/wiki)

## Usage

- `data.csv` contains the date, time and vehicle licence number.
- Tesseract is a library which uses OCR engine.
- Tesseract contain more than hundred languages to choose, if you want to change:
  - Open `test.py` and change the`config` variable.
  - In `config` variable change **'eng'** to your preferred language.
- Use Tesseract 4 as this is the latest version which uses LSTM network.


Run the following:

    python test.py
    
 
## License & Copyright
© [Arbaz Khan](https://arbazkhan4712.github.io/Contact.html)

Licensed under the [MIT License](License)
