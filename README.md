# CARLA-Object-Detection-and-Point-Cloud-Visualization
The implementation of YOLOv3-based object detection and point cloud visualization in CARLA simulator. In this repository, we demonstrate a demo for simulated autonomous driving in CARLA, equipped with object detection and point cloud visualization as following:

![image](https://github.com/KevinChen-MMT-QA/CARLA-Object-Detection-and-Point-Cloud-Visualization/blob/main/demo/fig1.jpg)

## CARLA Simulator
The version of CARLA simulator is 0.9.13. You can find the official documents [here](https://carla.org/2021/11/16/release-0.9.13/), and start your work via [quick start package installation](https://carla.readthedocs.io/en/latest/start_quickstart/).

## Major Functions
CARLA is a simulated autonomous driving software, and has many Python API functions implemented in `CARLA_0.9.13\PythonAPI\examples`. 

`automatic_control.py` is a basic API which controls an agent to drive in the city. You can also use `dynamic_weather.py` and `generate_traffic.py` to produce a more complex traffics.
