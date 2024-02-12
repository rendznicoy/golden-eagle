# GIEASE (Golden Eagle)
### A Web App with an automated GIS classification system underpinned by Region-based Convolutional Neural Network
### Target:  GE.A00.001
### Main Application Link: [Golden Eagle](https://github.com/rendznicoy/GoldenEagle)
_______________________________________
# [AI](https://github.com/rendznicoy/golden-eagle/edit/main/Details/AI.md)
**CNN Architecture**

![AI](https://github.com/rendznicoy/golden-eagle/blob/main/Mockups/CNN%20Architecture.png)

**Image Classification Feature**

* This feature is used to classify the land types and water bodies inside the image.

**Input:**
* The system shall initiate the image classification process.
  
**Process:**
+ The system shall review the contents inside the image
- The system shall classify each land type and water body inside the image.
- The system shall prepare the image for segmentation.

**Output:**
*  The land types inside the image are classified by the system.

**Image Segmentation Feature**

* This feature is used to segment and color the land types insidetheimage after the contents are classified.

**Input:**
* The system shall segment the classified contents of the image.
  
**Process:**
- The system shall review the classified contents of the image.
- The system shall segment and color each land type inside the image.
- The system shall prepare the image for map generation.

**Output:**
*  Each of the land types inside the image are segmented and colored.

**Map Generation Feature**

* * This feature is used to generate a map and the generated map will either be sent via email or saved on a local file folder.

**Input:**
* The system shall finalize and render the segmented image.
  
**Process:**
- The system shall review the contents inside the image. 
- The system shall finalize each land type inside the image.
- The system shall prepare the image for download and will either be sent via email or saved into a local file folder.

**Output:**
*  The image segmentation is finalized, rendered, and the generated map is sent via email.

**Data Dictionary**
| Element ID | Element Text      | Element Type | Data Type                | Required?          | Rules         |
|----------|------------|-------------------|----------------------------|-------------------------|----------------------|
| ClassificationResults     | Land Type Classification Result       | Text               | Text               | ...              | ...               | 

# [Revisions](https://github.com/rendznicoy/golden-eagle/blob//main/Details/REVISIONS.md)

# [Homepage](https://github.com/rendznicoy/golden-eagle/blob/main/Details/HOMEPAGE.md)

# [Sign Up Feature](https://github.com/rendznicoy/golden-eagle/blob//main/Details/SIGNUP.md)

# [Login Feature](https://github.com/rendznicoy/golden-eagle/blob//main/Details/LOGIN.md)

# [Upload Feature](https://github.com/rendznicoy/golden-eagle/blob//main/Details/UPLOAD.md)

# [Download Feature](https://github.com/rendznicoy/golden-eagle/blob//main/Details/DOWNLOAD.md)

