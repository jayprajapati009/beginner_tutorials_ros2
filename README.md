# ROS2 CPP Publisher and Subscriber Tutorial

## Overview

The primary functionality of this package is to publish custom string messages.

## Dependencies

Before running this package on a third-party system, make sure that the following prerequisites are met:

- Ubuntu 22.04
- ROS 2 Humble
- Your ROS 2 workspace is set up correctly

## Build and Run Instructions

1. **Clone Package**

   You can obtain the package by either cloning the repository or copying it to your ROS 2 workspace. Make sure to place it in the `src` directory of your workspace.

   ```sh
   git clone https://github.com/your_username/ros2_custom_string_publisher.git
   ```

2. **Build the Package**

    Navigate to your ROS 2 workspace and build the package using colcon.

    ```sh
    cd cpp_pubsub
    colcon build --packages-select cpp_pubsub
    ```

3. **Source the Workspace**
    Source the ROS 2 workspace to set the environment for the package.

    ```sh
    source install/setup.bash
    ```

4. **Run the Publisher Node**
    You can now run the custom string publisher node.

    ```sh
    ros2 run cpp_pubsub publisher_member_function.cpp
    ```

5. **Run the Subscriber Node**
    Open a new terminal and run the subscriber node.

    ```sh
    source install/setup.bash
    ros2 run cpp_pubsub subscriber_member_function.cpp
    ```

## References

[1] <https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Cpp-Publisher-And-Subscriber.html>
