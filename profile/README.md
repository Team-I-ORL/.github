# MRSD 25 - TEAM I - ORB Robotics
We’re ORB Robotics, a team of engineers aiming to ease the days of frontline health workers. We believe we can do this with an onsite robotic solution that inspects hospital inventory, retrieves surgical kit items, and restocks supply rooms.

## Code Structure
Our organization's codebase is structured into several specialized repositories, each focusing on a specific aspect of our robotics project. This modular approach allows for better organization, easier maintenance, and improved collaboration.

### Navigation
- **Description**: Contains all navigation-related modules and packages
- **Purpose**: Autonomous Navigation in a pre-mapped environment.
  
### Manipulation
- **Description**: Houses all modules and packages related to robotic manipulation
- **Purpose**: Motion planning and related code for fetch's manipulator

### Interfaces
- **Description**: Stores all interfaces, including APIs and UIs
- **Purpose**: Ensures consistency across various interaction points

### ros1_bridge
- **Description**: A fork of the ros2/ros1_bridge repository
- **Purpose**: Provides bidirectional communication between ROS 1 and ROS 2

### Perception
- **Description**: Dedicated to all perception-related code and modules
- **Purpose**: All perception modules from object detection, segmentation and head servoing

## Repository Structure

Each repository has its own README file, which provides detailed information on:

1. Setup instructions
2. Usage guidelines
3. Specific dependencies

To get started with a particular aspect of our project, navigate to the relevant repository and consult its README for comprehensive information on setup and usage. This structure allows team members and contributors to quickly find the information they need and start working on specific components of our robotics project.

## System Architecture
