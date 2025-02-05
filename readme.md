Lunar Imaging System

Overview
The Lunar Imaging System is a cutting-edge project designed to enhance low-light images from the Polar Scientific Regions (PSR) of the lunar surface. It focuses on improving Signal-to-Noise Ratio (SNR) for better visibility, crucial for landing site selection and geomorphological analysis. By utilizing advanced image enhancement techniques, this system provides clearer and more detailed observations of the Moon’s polar regions.

Features
Image Enhancement: Utilizes Non-Local Means (NLM), Contrast Limited Adaptive Histogram Equalization (CLAHE), and Optimized High-Resolution Contrast (OHRC) algorithms.
•	Batch Processing: Efficiently processes large sets of lunar images using OpenCV.
•	Image Stacking: Combines multiple images to enhance clarity and reduce noise.
•	Database Management: Stores and retrieves processed images efficiently using PostgreSQL.
•	API Integration: Connects with external data sources and processing tools using Flask.
•	Cloud Storage: Enables scalable data handling and accessibility for high-computation image processing.


Technology Stack

![Screenshot 2025-01-30 145423](https://github.com/user-attachments/assets/42e18c89-2c78-43ff-be94-9af37aa97ac7)

•	Frontend: HTML, CSS, JavaScript, React.js
•	Backend: Flask (Python)
•	Database: SQL
•	Algorithms: NLM, CLAHE, OHRC, Image Stacking
•	Libraries: OpenCV, NumPy, Pandas

How It Works:

 ![Screenshot 2024-12-20 174657](https://github.com/user-attachments/assets/fdfcab4d-7bf9-4a8b-b8f2-26a501b13af5)

•	Image Acquisition: Collects raw low-light images from lunar datasets.
•	Preprocessing: Applies denoising techniques and enhances contrast.
•	Processing & Enhancement: Implements NLM, CLAHE, and OHRC to improve image quality.
•	Stacking & Analysis: Merges multiple images for better resolution and detail extraction.
•	Storage & Retrieval: Saves processed images in PostgreSQL and enables API-based retrieval.

Use Cases
•	Lunar Landing Site Selection: Helps identify safer landing zones for future missions.
•	Scientific Research: Assists in studying lunar surface morphology and geological formations.
•	Space Exploration: Supports better visualization for rover navigation and exploration planning.


Improved image quality by 20.05% by implementing advanced image processing algorithms, including Non-Local Means (NLM) denoising to reduce noise and CLAHE to enhance contrast, making lunar features more visible.

![Screenshot 2025-01-30 145122](https://github.com/user-attachments/assets/f6049051-9582-467f-9d83-9a08aeaab06f)

Future Enhancements
•	Implement AI-based Image Classification for automatic crater and terrain detection.
•	Optimize real-time image processing for faster results.
•	Expand cloud integration for scalable and distributed computing.
 

Contributors
1.	Harsh Vasu Paroch - Developer
2.	Shubham Sharma - Developer
3.	Piyush Bhat - Developer
4.	Saif Ullah - Developer
