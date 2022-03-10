#image-to-text-ocr

# Grab Text from an Image

Python script to grab text from all the images in the directory and save a subdirectory **(/converted-text)** as text files using **PyTesser module**. It is an Optical Character Recognition module for Python.

```python
python main.py <directory_path>
```

Python project that reads text from an image and prints in a text file. Implementation of Tesseract-OCR engine.

#PyTesser

PyTesser is an Optical Character Recognition module for Python. It takes as input an image or image file and outputs a string.

PyTesser uses the Tesseract OCR engine, converting images to an accepted format and calling the Tesseract executable as an external script. A Windows executable is provided along with the Python scripts. The scripts should work in other operating systems as well. For more information: please visit https://pypi.python.org/pypi/PyTesser

#Dependencies

PIL is required to work with images in memory. PyTesser has been tested with Python 2.7.13 and PIL 1.1.7 in Windows 7. The Python Imaging Library (PIL) adds image processing capabilities to your Python interpreter. This library supports many file formats, and provides powerful image processing and graphics capabilities.

Install Python: https://www.python.org/downloads/

Usage Example


from pytesser import * 
image = 
Image.open('fnord.tif') 
# Open image object 
using PIL print 
image_to_string(image) 
# Run tesseract.exe on 
image fnord print 
image_file_to_string('fnord.tif') 
>>fnord ```




## PyTesser
PyTesser is an Optical Character Recognition module for Python. It takes 
as input an image or image file and outputs a string.

PyTesser uses the Tesseract OCR engine (an Open Source project at Google), 
converting images to an accepted format and calling the Tesseract 
executable as an external script. A Windows executable is provided 
along with the Python scripts. The scripts should work in Linux as well. 

+ [PyTesser](http://code.google.com/p/pytesser/)
+ [Tesseract](http://code.google.com/p/tesseract-ocr/)
+ [README](/pytesser/README)
+ [LICENSE](/pytesser/LICENSE)
+ [NOTICE](/pytesser/NOTICE)
"# image-to-text-ocr" 
