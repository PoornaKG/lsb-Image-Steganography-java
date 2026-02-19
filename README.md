# lsb-Image-Steganography-java
This project implements Image Steganography in Java using the Least Significant Bit (LSB) algorithm. It securely embeds a secret image inside a cover image by modifying the least significant bits of pixel values, ensuring minimal visual distortion. The system also supports extraction of the hidden image from the encoded output image.
📌 Project Overview

Steganography is the process of hiding sensitive information within another medium so that the presence of hidden data is not easily noticeable.
In this project, a secret image is embedded inside a cover image by modifying only the least significant bits of pixel values, ensuring minimal visual distortion.

⚙️ Technologies Used

Java
BufferedImage
ImageIO
Bitwise Operations (LSB Manipulation)

🚀 Features

✅ Hide a secret image inside a cover image
✅ Extract the hidden image from the combined image
✅ Uses pixel-level bit manipulation
✅ Maintains visual similarity with original cover image

🧠 Working Principle
🔹 Hiding Process

Read both cover and secret images.

For each pixel:

Clear the least significant bit (LSB) of the cover image.

Insert the LSB of the secret image into the cover image.

Generate a new combined image containing hidden data.

🔹 Extraction Process

Read the combined image.

Extract the least significant bit from each pixel.

Reconstruct the secret image from extracted bits.

📂 Output Files

combined.jpg → Image containing hidden data

extracted.jpg → Reconstructed secret image

💡 Applications

Secure communication

Digital watermarking

Data protection

Cybersecurity research

🎯 Learning Outcomes

Understanding of image processing in Java

Practical implementation of bitwise operators

Knowledge of basic steganography techniques

File handling and pixel manipulation
