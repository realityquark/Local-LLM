

## **Welcome to my two-part series on setting up your computer to run Large Language Models (LLMs) locally!**

## NVIDIA_DRIVERS.md
I've decided to split this guide into two parts because. Let's face it, the NVIDIA drivers can be tricky to setup. In Part 1, we'll focus specifically on getting those drivers working correctly with Windows and Linux. Windows is a straight foward process, but Linux is where you can run into some touble. We will also go ahead and setup Cuda toolkit and Nvidia's Container Toolkit in Linux. This will be focusing on bare metal Linux, if you are wanting to utilize WSL2, check out part 2 where we get into specific on how to set that up.

## Leveraging_Install.md
In Part 2, we'll go over some situation awareness and then install two popular AI frameworks: Ollama, and Open WebUI. These frameworks are great examples of the diversity in AI tooling, and each has its own unique installation process. Ollama by itself can be ran from windows terminal, but Open WebUI will give you a GUI to interact with. You can even utilize more than one model at a time so you can compare your outputs from multiple modles while only asking your question once.  In addition to installing these frameworks, we'll also cover the roles that Docker, Cuda, and container toolkits play in helping you bring your AI projects to life. I've had a blast setting up my lab with these tools, and I hope this guide will help you get started on your AI journey too!






 _   _       _     _ _         ____       _                                       _    ___ 
| \ | |_   _(_) __| (_) __ _  |  _ \ _ __(_)_   _____ _ __ ___        _          / \  |_ _|
|  \| \ \ / / |/ _` | |/ _` | | | | | '__| \ \ / / _ \ '__/ __|     _| |_       / _ \  | | 
| |\  |\ V /| | (_| | | (_| | | |_| | |  | |\ V /  __/ |  \__ \    |_   _|     / ___ \ | | 
|_| \_| \_/ |_|\__,_|_|\__,_| |____/|_|  |_| \_/ \___|_|  |___/      |_|      /_/   \_\___|


                         
                                                     

