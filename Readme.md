# Devanagari Handwritten Digits Dataset in CSV

The dataset's authors are S. Acharya, A.K. Pant and P.K. Gyawali. The original dataset consists of images of all the characters in devanagari script. 

The dataset in this repo however, consists of only digits. The images of the digits have been converted to two CSV files: one for training purpose and one for testing.

There are 17,000 examples in the training dataset, and 3,000 examples in the testing dataset. Each CSV file has 1025 columns, where the first column contains the actual digit whereas the next 1024 columns contain the image's pixel information. 

[Read more about the dataset.](http://www.thelacunablog.com/?p=9240)

## What's inside
* train.csv : Dataset for training.
* test.csv  : Dataset for testing.
* tocsv.py  : Python script that I had used to convert the images to CSV format, just so, you may use it to redistribute the other characters in the original dataset in CSV format as well. Requires pandas, scipy and numpy library.


