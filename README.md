Humanoid Robot Experiment 01

What is it?
​
The Humanoid AI Engine is an advanced software control system designed to keep a 12-DOF (Degree of Freedom) bipedal humanoid robot balanced, aware, and operational in real-time.

​What does it do?

​It manages the robot's movement, balance, and hardware communication using four key features:

° Uses an asynchronous publisher/subscriber pipeline to pass perception and control data across nodes smoothly without system freezes.

° Predicts ground reaction forces and computes exact joint torques to help the robot recover balance if pushed.

° Processes simulated 3D depth maps to detect obstacles and adapt walking speeds automatically.

° Randomizes floor friction, adds signal delays (jitter), and injects torque noise so the software works on physical hardware.

