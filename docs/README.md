<p align="center">
<img src="assets/embryophenomicslogo.png" width="600"/>
<h1 align="center">A window on the dynamic period of embryonic development!</h1>
<h3 align="center">Hardware and software for visualising, quantifying and studying developing embryos</h3>
</p>

## Welcome
Welcome to the EmbryoPhenomics repository. EmbryoPhenomics is a platform for studying embryonic development. It was developed by a team of scientists to visualise developmental processes happening over the course of weeks, days, hours and seconds in hundreds of developing embryos. The project began with the development of [OpenVIM](http://www.openvim.org) some custom high-throughput bioimaging hardware. OpenVIM allows embryonic development to be recorded and visualised at different temporal resolutions in large numbers of embryos, while closely controlling the embryonic environment. Most recently, the team have developed [EmbryoCV](http://www.embryocv.org), a Python software that automatically measures biological responses of developing embryos including growth, movement and heart rate.

<h3 align="center">EmbryoPhenomics = OpenVIM + EmbryoCV</h3>

## What is EmbryoPhenomics?
EmbryoPhenomics is a technological platform for studying the phenome of aquatic embryos. Embryonic development is the most dynamic period of an organisms' life - temporally, functionally and spatially. EmbryoPhenomics consists of two pieces of high-throughput technology - bioimaging hardware [OpenVIM](http://www.openvim.org) and analytical software [EmbryoCV](http://www.embryocv.org). These technologies are synergistic and enable the visualisation and quantification of the dynamic process of whole-organism development with high temporal accuracy, in large numbers of embryos all while finely controlling the embryonic environment. The EmbryoPhenomics platform is automated and so can run over prolonged periods without any need for manual interaction and is therefore ideal for capturing the process of embryonic development which, while dynamic, also occurs over the course of hours and days.

### What can EmbryoPhenomics do?
Both the OpenVIM hardware and EmbryoCV software are freely available for others to use and adapt to their own needs. Both of these technologies have been developed to be modular and highly versatile. 

OpenVIM has been used with a range of organisms from single celled Protozoa, various molluscan and amphipod embryos, through to early life stage planktonic jellyfish. See the OpenVIM site for a more thorough list and the [Embryonic Development Vimeo Channel](http://www.vimeo.com/channels/embryonicdevelopment) for example video. The components of OpenVIM are modular meaning that lenses ranging from 20 X - 5000 X digital magnification have all been used succesfully. Experiments ranging from just a few hours through to many months have been performed and the number of embryos within experiments have ranged from just a single embryo through to 384 per OpenVIM system. Furthermore OpenVIM uses the open-source MicroManager software and therefore any components supported by MicroManager can be used with OpenVIM.

EmbryoCV is a software written in Python, a popular programming language among biologists. Furthermore, the majority of the image processing done in EmbryoCV uses the OpenCV computer vision library and its underlying code is written in C and therefore fast. Most of the processes in EmbryoCV are applicable to different species and it has been tested with both a freshwater gastropod and a marine amphipod - two species that possess very different forms of development and challenges in terms of their development of form and function. Nonetheless EmbryoCV was effective with both and can quantify growth, movement, physiological rates (cardiac rates), but also 'proxy traits' without any direct manual equivalent, but which are highly effective in their discriminatory power.

### The future of EmbryoPhenomics
The aim for EmbryoPhenomics is to enable the visualisation and quantification of dynamic processes within developing organisms with the goal of advancing our understanding of these critical life stages. Such technologies should be available to a wide range of scientists, working on different species, questions, life stages and with different budgets and the hope is that EmbryoPhenomics will provide a platform to facilitate this. If you are interested in this technology and would like to discuss how to implement or access it please use the [Embryo-phenomics user group](https://groups.google.com/forum/#!forum/embryo-phenomics).
