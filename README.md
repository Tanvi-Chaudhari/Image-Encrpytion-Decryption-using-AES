![Screenshot (717)](https://github.com/Tanvi-Chaudhari/Image-Encrpytion-Decryption-using-AES/assets/75910333/2116f34f-9e60-41ec-adb5-b6cb4cffd645)# Image Encryption and Decryption Program

## Program Overview

- Developed a robust program using Python for precise encryption and decryption of image files.
- Significantly enhances data security by preventing unauthorized access and data theft.
- Ensured the encrypted file remains highly secure, enabling worry-free transmission over networks.
- Recipient-side decryption allows seamless retrieval of the original image.

## Recommended Environment

- Advised using a Linux-based machine to minimize unexpected errors.
- **System:** Ubuntu 18.04.2 on Oracle VM VirtualBox.
- **Python Version:** 2.7.17.

## Key Libraries

- Utilized essential libraries to optimize functionality:
  - **numpy:** Version 1.13.3
  - **Pillow:** Version 9.0.0
  - **pycryptodome:** Version 3.12.0
  - **Tkinter:** Installed on Linux via `sudo apt-get install python-tk`.

# Process

## Executing the Program

- After writing the code in the `final.py` file, execute the program using the command `./final.py` in the Linux terminal.
- Ensure both `final.py` file and `Image2.jpeg` file are present on the desktop.

## Launching the Tkinter-based GUI

- Upon running the program, a Tkinter-based GUI window is opened, labeled "Image Encryption."
  ![Screenshot 2023-10-11 215918](https://github.com/Tanvi-Chaudhari/Image-Encrpytion-Decryption-using-AES/assets/75910333/c8f7980a-e316-4193-a611-85323a847018)


## Encryption Process

- To initiate encryption, follow these steps:
  1. Enter the encryption key into the provided input box.
  2. Click on the "Encrypt" button.
  3. This action triggers the opening of another window that allows the user to select the `Image2.jpeg` file.
  4. Upon selecting the image, the program encrypts it, generating encrypted files. The encrypted images are unrecognizable, ensuring data security.
  ![Screenshot (716)](https://github.com/Tanvi-Chaudhari/Image-Encrpytion-Decryption-using-AES/assets/75910333/782bd46a-4dc1-4170-a61b-7d716eddf5f5)


## Decryption Process

- To decrypt the images and obtain the original `Image2.jpeg` file:
  1. Input the same encryption key used for encryption into the provided input box.
  2. Click on the "Decrypt" button, it'll open up window to choose will one to decrypt, we'll choose Image2.jpeg.crypt.
  ![Screenshot (717)](https://github.com/Tanvi-Chaudhari/Image-Encrpytion-Decryption-using-AES/assets/75910333/5dc281a4-ba02-4a1a-b684-28376a774fec)
  3. The program then processes the decryption, providing the `visual_decrypt.jpeg` file, which is the decrypted version of the original `Image2.jpeg`.
  ![Screenshot (718)](https://github.com/Tanvi-Chaudhari/Image-Encrpytion-Decryption-using-AES/assets/75910333/e5e24a87-f6eb-41c0-b809-9f47ffafff8a)


## Handling Error Cases

- The program is designed to handle various error cases and provide appropriate alerts or warnings.
- For instance, attempting encryption or decryption without inputting the encryption key triggers alerts, prompting the user to enter the key.
- Warnings and alerts are strategically placed in the code to guide users and ensure proper usage of the program.

## Resources
- [Here](https://github.com/aditya-agrawal16/Image-Encryption-and-Decryption-using-AES-algorithm)
- [GeeksforGeeks](https://www.geeksforgeeks.org/advanced-encryption-standard-aes/)
