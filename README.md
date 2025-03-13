# Car-Speed-and-Counting

🚗Vehicle Speed Tracking & Counting Using YOLOv8 and AI

Have you ever wondered how AI can measure vehicle speed and count cars automatically? Today, I’m sharing an advanced project that uses YOLOv8 to detect, track, and measure vehicle speeds in pixels per second, while also checking for speed violations

Technologies Used: ✅ YOLOv8 for vehicle detection (Cars 🚗, Buses 🚌, Trucks 🚛)
✅ OpenCV for video processing and object tracking
✅ Python for speed calculation and data analysis

How It Works: 🔹 Vehicle Detection & Tracking: The model processes a real-world traffic video, detects vehicles, and tracks their movements.
🔹 Speed Calculation: 📌 When a vehicle crosses Line 1, the entry time is recorded.
📌 When it crosses Line 2 , speed is calculated using:
Speed = Distance / Time (in pixels per second).
🔹 Speed Violation Detection: If a vehicle exceeds 60 px/s, it gets labeled as OVERSPEED in red 🚨.
🔹 Vehicle Counting: The program keeps track of the total number of vehicles that passed both lines.

Real-Time Display Features: While running, the system shows:
✅ Unique ID for each vehicle
✅ Real-time speed tracking ✅ Speed violations highlighted in red 🚨
✅ Total vehicle count on-screen

This project is a great step in AI-powered Computer Vision If you find it interesting, share it with AI enthusiasts
