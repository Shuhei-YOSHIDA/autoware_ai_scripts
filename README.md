autoware_ai_scripts
====

## docker
* Prepare docker image for Autoware AI; [link](https://github.com/autowarefoundation/autoware_ai_docker)
* Commit your progress, for example GPG key fix, to your image (After `apt clean && rm -rf /var/lib/apt/lists/*`)(Type `docker commit <Container> <Repository>`)
* Run the image by `./run_local_image <ImageName>`
* If you need to set a name to a container, `./run_local_image <ImageName> <ContainerName>`

### reference
Fix GPG error of AutowareAI docker image
1. [ROS](https://discourse.ros.org/t/ros-gpg-key/20671)
1. [nvidia](https://developer.nvidia.com/blog/updating-the-cuda-linux-gpg-repository-key/)
