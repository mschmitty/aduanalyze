This code is a Python script designed to process a folder of **FITS files** (Flexible Image Transport System files, commonly used in astronomy for storing image data and metadata) and analyze them. Specifically, it reads exposure times and calculates the average ADU (Analog-to-Digital Unit) values for the image data in each FITS file. The results are saved to a CSV file, and a scatter plot is created to visualize the relationship between exposure time and average ADU.
### **Code Description**
#### 1. **Purpose**
- Process FITS files in a specified folder.
- Extract metadata (`EXPTIME`, or exposure time) from the header of each FITS file.
- Compute the mean ADU value of the image data (representing the pixel intensity or brightness).
- Save the extracted data (filename, exposure time, mean ADU) to a CSV file.
- Create a scatter plot showing the relationship between exposure time (X-axis) and mean ADU (Y-axis).
