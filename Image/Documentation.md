# Image Steganography Tool

### User Guide

When you select the image steganography technique, the following window will appear:

<p align="center">
  <img src="https://i.imgur.com/15IqIXS.png" alt="Image Steganography Tool Window">
</p>

## Instructions

1. **Start by Selecting a Cover Picture File:**
   - Click the **"Search"** button.
   - Choose the image file that will serve as your cover text.

2. **Select Your Preferred Method:**
   - Use the combo box to select your preferred steganography method.
   - **Note for DCT Method:** If you select the DCT method, an additional field will appear:
   
     <p align="center">
       <img src="https://i.imgur.com/BwxeCCN.png" alt="DCT Method Field">
     </p>
   
   - The field where it says: "Enter DCT Number" is when you select **Steganography = False** as it is used to indicate how many characters the secret message has (if the number is incorrect, then you will not get the right secret text from the image).

3. **Encryption Settings:**
   - In the **"Encryption"** section, use the radio buttons to indicate if you want to encrypt the secret message before embedding it.
     - **True:** Encrypt the secret message.
     - **False:** Do not encrypt the secret message.

4. **Steganography Settings:**
   - In the **"Steganography"** section, use the radio buttons to specify the operation:
     - **Steganography = True:** Hide data in the image file.
     - **Steganography = False:** Extract data from the image file.

5. **Input Your Secret Message:**
   - Enter the secret message you want to hide in the second text box.

6. **Feedback on Completion:**
   - Upon completion, a popup window will display feedback indicating that the process has finished.
