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

Both the OpenVIM hardware and EmbryoCV software are open-source and freely available for others to use and adapt to their own needs. The OpenVIM and EmbryoCV technologies are intentionally broad in their scope, modular and versatile. Via their respective Github repositories we provide information on getting started and a [Google Group forum](https://groups.google.com/forum/#!forum/embryo-phenomics) can be used to ask questions and share experiences and advice.

## What can EmbryoPhenomics do?
[OpenVIM](http://www.openvim.org) has been used with a range of organisms from single celled Protozoa, various molluscan and amphipod embryos, through to early life stage planktonic jellyfish. See the OpenVIM repository for a more thorough list and the [Embryonic Development Vimeo Channel](http://www.vimeo.com/channels/embryonicdevelopment) for example video. The components of OpenVIM are modular meaning that lenses ranging from 20 X - 5000 X digital magnification have all been used succesfully. Experiments ranging from just a few hours through to many months have been performed and the number of embryos within experiments have ranged from just a single embryo through to 384 per OpenVIM system. Experimental designs and associated acquisition parameters can be Furthermore OpenVIM uses the open-source [MicroManager](https://micro-manager.org) software and therefore components supported by MicroManager can be used withthin an OpenVIM system. 

While OpenVIM can be used with a broad range of experimental designs and associated image acquisition parameters, EmbryoCV is really tailored towards experiments in which 'real-time' image sequences are acquired of each embryo over successive time points. This approach allows visualising, and thereby quantifying, both long term developmental responses, but also responses only evident in real-time, such as heart rate, movements. See below for a sample of how this works and allows both a 'time-lapse', but also at any time point also a 'real-time' view of developing embryos.

<p align="center">
<img src="assets/radixDevelopment.gif" width="400"/>


[EmbryoCV](http://www.embryocv.org) is a Python software for automated high-throughput analysis of the video datasets produced by the OpenVIM platform.  In testing EmbryoCV has been applied to the automated quantification of embryos in > 30M images and includes measures of size, shape, movement and physiological parameters including heart rate and intrinsic embryo movements, which have proven a reliable measure of embryo health and lethal end points. The raw data from EmbryoCV include both obviously relevant biological data (growth rates, heart rates, movements, lethal end points), but also data that can be further interrogated to identify new or as yet unknown end points. A central ethos in the design of EmbryoCV was to maximise the extraction of data that could be biologically relevant i.e. rather than simply producing a classification of alive or dead (although this can also be done using the output data), also produce data that are relevant and valuable to understanding the complex biological responses of developing organisms.

Data are output in a format that can be interrogated dynamically on disk.Furthermore, the majority of the image processing done in EmbryoCV uses the OpenCV computer vision library and its underlying code is written in C and therefore fast. Most of the processes in EmbryoCV are applicable to different species and it has been tested with both a freshwater gastropod and a marine amphipod - two species that possess very different forms of development and challenges in terms of their development of form and function. Nonetheless, EmbryoCV was effective with both and can quantify growth, movement, physiological rates (cardiac rates), but also 'proxy traits' without any direct manual equivalent, but which are highly effective in their discriminatory power. EmbryoCV has been designed to make future development to work with different species, or to incorporate different types of computer vision functionality possible.

## The future of EmbryoPhenomics
The aim for EmbryoPhenomics is to enable the visualisation and quantification of dynamic processes within developing organisms with the goal of advancing our understanding of these critical life stages. Such technologies should be available to a wide range of scientists, working on different species, questions, life stages and with different budgets and the hope is that EmbryoPhenomics will provide a platform to facilitate this. If you are interested in this technology and would like to discuss how to implement or access it please use the [Embryo-phenomics user group](https://groups.google.com/forum/#!forum/embryo-phenomics).
