topics learnt:

1) processes' bash commands, unix philosophy, differences between piping and redirection, checking, running, and killing silently or forcefully different processes, finding port numbers of ssh processes, analyzing simple log processes, synchronous and asynchronous processes

2) Deployment tool Docker,cpu virtualization(the illusion of private resources, provided by software),SandBox,Registary of Docker images(Docker Hub),Docker Build commands, Denial of Service Attack, usage of ubuntu,alpine dokcker images,Docker processes,images, and logs,Docker I/O and terminal flags,Dockerfile scripting for automating docker images' creation

use existing Docker images to launch containers

define new Docker images using Dockerfiles

troubleshoot common issues with running Docker containers

Contexts this semester
• Virtual Machines (hardware)
• Virtual Machines (languages)
• Virtual Operating System (container)--Docker makes creation easy . The "physical" OS is shared, which is very efficient. Programs in different containers can uses different flavors of Linux
• Virtual Memory (covered later lecture...)

Containers and Virtual Machines are "Sandboxes"

Resources of the "cluster"(group of containers inside a single VM) are limited to those of a single VM

