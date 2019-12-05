# SimBA

Several excellent computational frameworks exist that enable high-throughput, consistent, and unbiased scoring of freely moving animals. We attempt to distribute a plug-and play pipeline and system that enabled users in preclinical social neuroscience to feed in images of variables qualities to automatically segment and analyse behavior. The system does not require computer science and programing experience, and SimBa is optimized for any video recording quality. We may be able to provide support and advice for specific use instances, especially if it benefits multiple users and advances the scope of SimBa. An post issues here and we'll work on solving bugs as they appear!

- The simBA pipeline requires no programing knowledge 
- Specialized commercial or custom-made equipment is not required
- Extensive annotations are not required
- The pipeline is flexible and can be used to create and validate classifiers for different behaviors and environment 

SimBa currently does not support analysis of video recordings of multiple similarly coat-colored animals, and is vslided using videos filmed from above at 90 degree angle. However we and others are working hard on getting multi-animal tracking of similarly coat colored animals and multiple recording angles supported! :muscle:


![](https://github.com/sgoldenlab/tkinter_test/blob/master/images/4videos.gif)

## Pipeline

<img src="/images/overallflow.PNG" width="989" height="169" />

[Pre-process videos](docs/tutorial_process_videos.md) --> [Create tracking model](docs/Tutorial_DLC.md) --> [Building classfier(s)](docs/tutorial.md) --> [Analysis/Visualization]()

## [Installation](docs/Installation.md) 

How to [install SimBA](docs/installation.md)

## Tutorial

- [Process Video using tools](docs/Tutorial_tools.md)
- [Batch process video](docs/tutorial_process_videos.md)
- [DeepLabCut in the GUI](docs/Tutorial_DLC.md)
- [SimBA](docs/tutorial.md)
- [Label Behavior](docs/labelling_aggression_tutorial.md)

## License
This project is licensed under the GNU Lesser General Public License v3.0. Note that the software is provided "as is", without warranty of any kind, express or implied. If you use the code or data, please cite us :)

## References


