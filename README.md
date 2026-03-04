# roadmap for automobile ai 
<br>
Phase 1: The Foundations (Math, Physics, and Core Code)
Math & Physics Focus:
Kinematics (velocity, acceleration, mass), linear algebra (matrix multiplication), and foundational calculus (derivatives for optimization).

Programming Focus: 
Python, NumPy for array manipulation, and traditional machine learning algorithms like Linear and Logistic Regression.

Free Resources:
The Machine Learning Specialization by Andrew Ng (to solidify AI fundamentals) and Khan Academy (to review specific linear algebra or calculus concepts as needed).

Phase 2: Perception (Teaching the Car to See)
This is where you move from basic data arrays to processing live video feeds, allowing the vehicle to detect lanes, pedestrians, and traffic lights.

Concept Focus:
Image processing, color space conversion, Convolutional Neural Networks (CNNs), and object detection.

Tool Focus:
OpenCV and PyTorch or TensorFlow.

Free Resources:
The "Python Plays GTA V" series by Sentdex on YouTube. This is an incredible, highly engaging project to train a neural network to identify objects and drive inside a virtual game world.

Phase 3: Sensor Fusion and Localization (Understanding the World)
Cameras alone are not reliable enough. You must merge 2D camera data with 3D LiDAR and Radar, while calculating exactly where the car is located down to the centimeter.

Concept Focus:
The Kalman Filter (using probability to calculate the true location from noisy sensor data) and 3D point cloud processing.

Tool Focus:
Advanced Python and NumPy for heavy mathematical state estimation.

Free Resources:
The "State Estimation and Localization for Self-Driving Cars" course on Coursera (Course 2 of the University of Toronto Specialization). Remember to click the "Audit" link to access the materials for free.

Phase 4: Planning and Control (Making Decisions and Moving)
The AI must plot a safe trajectory through traffic and mathematically control the steering wheel, throttle, and brakes.

Concept Focus: 
Pathfinding algorithms (like A*), vehicle dynamic modeling, and PID Controllers.

Tool Focus:
Translating physical kinetic equations into Python control loops.

Free Resources:
Courses 3 and 4 of the Toronto Coursera Specialization ("Visual Perception" and "Motion Planning and Control").

Phase 5:
The Professional Level (Simulation and Production Code)
To bridge the gap from a learning environment to professional engineering, you must transition to industry-standard middleware and simulation environments.

Concept Focus:
Real-time data streams, system architecture, and eventually translating critical Python prototypes into C++ for maximum execution speed.

Tool Focus:
ROS (Robot Operating System) and the CARLA Simulator.

Free Resources:
The official CARLA documentation and tutorials. Additionally, reading the open-source codebase for Openpilot (Comma.ai) on GitHub is the absolute best way to see how real engineers structure autonomous vehicle code.
