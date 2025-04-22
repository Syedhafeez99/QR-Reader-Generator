Features
QR Code Generation

Create custom QR codes from any text or URL input
Specify custom filenames for saved QR codes
Preview generated QR codes directly in the application
Save QR codes as PNG image files
Reset functionality for creating multiple QR codes

QR Code Reading/Detection

Open and scan existing QR code images
File browser to easily locate QR code files
Display the detected QR code image in the application
Extract and show the encoded data from QR codes
Support for standard QR code formats

Technical Implementation
The application leverages several key technologies:

Tkinter: For the graphical user interface with tabbed navigation
qrcode: Python library for generating QR codes
OpenCV (cv2): For detecting and decoding QR codes from images
Error handling: Comprehensive validation and error messages for user inputs

User Interface
The interface is organized into two tabs:

QR Code Generator: Input data, specify a filename, and generate QR codes
QR Code Detector: Browse for existing QR code images and extract their encoded data

This tool provides a complete solution for working with QR codes, enabling users to both create and read QR codes in a single application with minimal technical knowledge required.
