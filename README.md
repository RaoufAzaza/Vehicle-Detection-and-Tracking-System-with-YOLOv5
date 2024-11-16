Overview:

This project implements a real-time vehicle detection and tracking system using YOLOv5, designed for tracking vehicles such as cars, trucks, and other road users in video feeds. The system employs YOLOv5's tracking functionality to detect and monitor multiple vehicle classes, with real-time updates and dynamic reporting.

Features:

Vehicle Detection: Detects multiple vehicle types (cars, trucks, etc.) in video frames.
Real-Time Tracking: Tracks vehicles across frames, assigning unique IDs to prevent double-counting.
Cross-Line Detection: Tracks and counts vehicles crossing a designated red line in the video stream.
Dynamic Reporting: Outputs real-time counts of vehicles crossing the line, categorized by vehicle class.
Progress Bar: Displays a progress bar (using tqdm) to track frame processing status.
Video Output: Generates an annotated video with vehicle IDs, bounding boxes, and counts per class.

Contributing:

Feel free to fork the repository, open issues, or submit pull requests. Contributions are welcome!
