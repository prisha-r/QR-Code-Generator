Python QR Code Generator

This is my first professional Python project which generates QR codes from the user provided link. 
The generated QR code is saved as an image file and can also be displayed immediately using the Pillow library.

Features:
- Generate QR codes from any link provided.
- Save QR codes in PNG format with custom filenames.
- Displays the QR code after creation.

Technologies & Libraries:
- Python – Programming language used.
- qrcode– Library for generating QR codes.
- Pillow (PIL) – Library for handling images and displaying them.

How to Use
1. Clone or download this repository.
2. Make sure Python is installed on your system.
3. Install required libraries:
   ```bash
   python -m pip install qrcode pillow

Run the script:
bash
Copy code
python qr_code_generator.py
Enter the URL when prompted.
Enter the desired file name for the QR code.
The QR code image will be saved and displayed automatically.

Example
After running the script and entering https://www.youtube.com as the URL, a file named youtube_qr.png will be created and opened automatically.

Author
Prisha
