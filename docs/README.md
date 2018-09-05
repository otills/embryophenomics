<p align="center">
<img src="assets/embryophenomicslogo.png" width="600"/>
<h1 align="center">A window on the dynamic period of embryonic development!</h1>
<h3 align="center">Hardware and software for visualising, quantifying and studying developing embryos</h3>
</p>

## Welcome
Welcome to the EmbryoPhenomics repository! EmbryoPhenomics is a platform for studying embryonic development. It was developed by a team of scientists to visualise developmental processes happening at the whole-organism level over the course of weeks, days, hours and seconds in hundreds of developing embryos. 

## What is EmbryoPhenomics?
EmbryoPhenomics began with the development of [OpenVIM](http://www.openvim.org) some custom high-throughput bioimaging hardware. OpenVIM allows embryonic development to be recorded and visualised at different temporal resolutions in large numbers of embryos, while closely controlling the embryonic environment. Most recently, the team have developed [EmbryoCV](http://www.embryocv.org), a Python software that automatically measures biological responses of developing embryos including growth, movement and heart rate.

<img src="assets/EmbryoPhenomicsLogic.png" width="800"/>

Both the OpenVIM hardware and EmbryoCV software are open-source and freely available for others to use and adapt to their own needs. The OpenVIM and EmbryoCV technologies are intentionally broad in their scope, modular and versatile. Via their respective Github pages we provide information on getting started and a Google Group forum can be used to ask questions and share experiences.

### What can EmbryoPhenomics do?
[OpenVIM](http://www.openvim.org) has been used with a range of organisms from single celled Protozoa, various molluscan and amphipod embryos, through to early life stage planktonic jellyfish. See the OpenVIM repository for a more thorough list and the [Embryonic Development Vimeo Channel](http://www.vimeo.com/channels/embryonicdevelopment) for example video. The components of OpenVIM are modular meaning that lenses ranging from 20 X - 5000 X digital magnification have all been used succesfully. Experiments ranging from just a few hours through to many months have been performed and the number of embryos within experiments have ranged from just a single embryo through to 384 per OpenVIM system. Furthermore OpenVIM uses the open-source [MicroManager](https://micro-manager.org) software and therefore components supported by MicroManager can be used with OpenVIM.

[EmbryoCV](http://www.embryocv.org) is a software written in Python, a popular programming language among biologists. Furthermore, the majority of the image processing done in EmbryoCV uses the OpenCV computer vision library and its underlying code is written in C and therefore fast. Most of the processes in EmbryoCV are applicable to different species and it has been tested with both a freshwater gastropod and a marine amphipod - two species that possess very different forms of development and challenges in terms of their development of form and function. Nonetheless, EmbryoCV was effective with both and can quantify growth, movement, physiological rates (cardiac rates), but also 'proxy traits' without any direct manual equivalent, but which are highly effective in their discriminatory power. EmbryoCV has been designed to make future development to work with different species, or to incorporate different types of computer vision functionality possible.

### The future of EmbryoPhenomics
The aim for EmbryoPhenomics is to enable the visualisation and quantification of dynamic processes within developing organisms with the goal of advancing our understanding of these critical life stages. Such technologies should be available to a wide range of scientists, working on different species, questions, life stages and with different budgets and the hope is that EmbryoPhenomics will provide a platform to facilitate this. If you are interested in this technology and would like to discuss how to implement or access it please use the [Embryo-phenomics user group](https://groups.google.com/forum/#!forum/embryo-phenomics).
