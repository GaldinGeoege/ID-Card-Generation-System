## ID Card Generation System

# Objective:
The ID Card Generation System is a Python script designed to automate the creation of personalized identification cards. The system takes input from a CSV file containing details such as name, job title, ID number, email, mobile number, photo path, and validity period. It then uses this information to generate visually appealing ID cards with embedded barcodes for efficient identification, adhering to a template size of 54x85.


# Dependencies:
- Pillow (PIL): Image processing library for handling image-related tasks.
- python-barcode: Library for creating barcodes.
- pandas: Data manipulation library for reading and processing CSV data.

  
# Key Features:
1. Customizable Templates: The system utilizes customizable ID card templates with dimensions of 54x85, allowing users to design the layout and appearance of the ID cards according to their preferences.

2. Barcode Integration: Each ID card includes a unique barcode generated from the ID number. Barcodes facilitate quick and accurate scanning for identification purposes.

3. Photo Inclusion: The ID card incorporates a circular photo of the individual, enhancing visual recognition and personalization.

4. Details Display: Essential details such as name, job title, ID number, email, and mobile number are prominently displayed on the ID card, ensuring clarity and accessibility of information.

5. Validity Period: The system includes a feature to display the validity period on the ID card, indicating the duration for which the ID card is valid.

6. Batch Processing: The script supports batch processing, allowing users to generate multiple ID cards in a single run based on the information provided in the CSV file.


# Usage:
1. Data Input: Users provide input details through a CSV file containing information for each ID card recipient.

2. Template Configuration: Customize the ID card template and font styles according to specific design requirements, keeping in mind the template size of 54x85.

3. Automation: Execute the script to automatically generate ID cards, including barcodes, photos, and relevant details, adhering to the specified template dimensions.

4. Output: The generated ID cards are saved as image files in a specified output folder for distribution or further use.



