# Processing-DICOM-Images
Read and convert medical images present in DICOM format

DICOM is a format used generally in medical images.
Along with the image, a DICOM file contails other information too like Patient Name etc.

The notebooks created in this repository are :
DCMtoCSV : This takes information present in data elements of dataset in .dcm files and stores it to .csv format.
dcmToJpg : This takes images for all .dcm files and converts them to .jpg formats.
ReadDCM : In this .dcm files have been read. The image in file is plotted and other data elements have been read.

dicomFields.csv contains the data elements fields that are present in a .dcm file
