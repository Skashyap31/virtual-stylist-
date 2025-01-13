# Virtual Stylist Application

The **Virtual Stylist Application** is an interactive tool designed to provide personalized outfit, makeup, and accessory recommendations based on user inputs. This application combines user preferences, measurements, and optional photo uploads to deliver tailored fashion advice for different occasions.

---

## Features

- **Body Shape Classification:**
  Determines your body shape (Hourglass, Pear, Apple, or Rectangle) based on your chest, waist, and hip measurements.

- **Tailored Recommendations:**
  Offers suggestions for:
  - Outfits
  - Makeup styles
  - Accessories

- **Occasion-Based Suggestions:**
  Provides specific recommendations for casual, office, party, or formal functions.

- **Image Display:**
  Uses OpenCV to display uploaded images, allowing users to visualize their options.

- **Customizable Image Uploads:**
  Users can upload their own images for outfits, makeup, and accessories.

---
## How It Works

1. **User Input:**
   - Enter body measurements (height, chest, waist, hips).
   - Specify skin tone (light, medium, dark).
   - Choose an occasion type (casual, office, party, function).

2. **Body Shape Classification:**
   - The application classifies your body shape based on measurements.

3. **Recommendations:**
   - Provides suggestions for outfits, makeup, and accessories tailored to your inputs.

4. **Optional Photo Upload:**
   - Users can upload a photo to enhance the recommendation experience.
   - ---

## Instructions for Image Uploads

### 1. **Uploading Custom Images**
Users can replace or add their own images for outfits, makeup, and accessories:

- **Image Requirements:**
  - File formats: `.jpg`, `.png`, or other standard image formats.
  - Store images in logical folders for easier access (e.g., `images/casual/`).

- **Updating the Code:**
  Add the file paths of your images to the `data` dictionary in the script. For example:
  ```python
  "outfits": {
      "casual": ["images/casual/new_casual_outfit.jpg", "images/casual/casual_outfit2.jpg"],
  }
  ```
  Make sure to upload images according to your preferences, and update the file paths in the `data` dictionary to reflect their location.

### 2. **Path Configuration**
Ensure the file paths in the `data` dictionary match the location of your uploaded images. Uploading custom images that align with your choices will lead to more personalized and accurate results.

### 3. **Error Handling**
- The application will display an error message if an image file is missing or the path is incorrect.
- Double-check paths before running the application.

---

## Installation

### Prerequisites

1. Python 3.7 or higher
2. Install the required libraries:
   ```bash
   pip install opencv-python
   ```

### Running the Application

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/virtual-stylist.git
   ```

2. Navigate to the project directory:
   ```bash
   cd virtual-stylist
   ```

3. Run the application:
   ```bash
   python main.py
   ```

---

## Example

Here is an example of how to use the application:

1. Start the program and follow the prompts.
2. Enter your body measurements, skin tone, and occasion.
3. View the recommendations for outfits, makeup, and accessories.
4. Optionally, upload a photo for a more personalized experience.

---

## Notes

- Ensure the OpenCV library is correctly installed for image display.
- Customize the `data` dictionary to include your preferred images.
- Upload images based on your choices and update the paths to enhance the output.
- If you encounter issues, check the file paths for uploaded images.

---

## Feedback

We value your feedback! Let us know if you have suggestions to improve this application.

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.
