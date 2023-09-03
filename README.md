# FRC1884 2023

### Description
Code from [FIRST Robotics Competition](https://www.firstinspires.org/robotics/frc) team 1884 during the 2023 season.

The robot code is all contained in [src/main/java/frc/robot](https://github.com/UnknownPaws/FRC1884-2023/tree/master/src/main/java/frc/robot) and contains for for autonomous and driver controlled movement of the swerve drive, elevator, intake claw, and pivoting arm –all of which are subsystems of the robot. To make our robot as competitive as possible we utilised the April Tags for precise odometry and alignment as well as motion profiled movement of the motors on the elevator, arm, and drivebase which consisted of using PID loops to avoid over/undershooting a motor goal, and velocity-time profiles to ensure smooth and safe movement of mechanisms.
