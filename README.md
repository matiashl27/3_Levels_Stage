# Strobe-enhanced microscopy stage for microfluidic droplet generation

The strobe-enhanced microscopy stage is a free and open-source workstation for imaging fast processes, particularly developed for microfluidic droplet generation. It uses the lens from the Raspberry Pi Camera to produce a microscope with a field of view of almost 1mm and a strobe illumination based on a high-power LED for imaging fast-moving objects. Custom electronics allow the synchronization between the LED and the camera to capture sharp images of fast-moving droplets and other objects.

This design is inspired by open-source hardware such as the [OpenFlexure flat-top microscope](https://rwb27.gitlab.io/openflexure-flat-top-microscope/).

Find about more about this platform and other open-source hardware for bioimaging on the [LIBRE hub website](https://librehub.github.io/).

> **Note:** This site has some sections that were adapted from [OpenFlexure Microscope](https://build.openflexure.org/openflexure-microscope/v7.0.0-beta1/low_cost_microscope) and [OpenFlexure Flat-top Microscope](https://rwb27.gitlab.io/openflexure-flat-top-microscope/1_preparing_laser_cut_parts) documentation to facilitate the assembly. 

## Table of Contents

### Instructions

* [Assembly instructions](https://librehub.github.io/3_Levels_Stage/3-level-station.html)
    * [Parts list](https://librehub.github.io/3_Levels_Stage/3-level-station_BOM.html)
    * [Software installation](https://librehub.github.io/3_Levels_Stage/software-installation.html)
* Usage instructions
	* [Software usage](https://librehub.github.io/3_Levels_Stage/usage.html)

### Design files and source code

* Hardware designs
    * [Microscope hardware and assembly instructions (source)](https://github.com/LIBREhub/3_Levels_Stage)
    * [Pi Hat](https://github.com/wenzel-lab/open-microfluidics-workstation/tree/master/module-pi/pi_pcb)
    * [Strobe module](https://github.com/wenzel-lab/open-microfluidics-workstation/tree/master/module-fast-imaging)
* Software source code
    * [Microscope server](https://github.com/wenzel-lab/open-microfluidics-workstation/blob/master/module-pi/webapp.zip) (This code runs on the built-in Raspberry Pi and includes the web application for the user interface.)
    * Microscope operating system (This collates all software and builds a pre-written SD card image for the Raspberry Pi.) - Coming soon

## This project is documented with GitBuilding

### What is GitBuilding

GitBuilding is an OpenSource project for documenting hardware projects with minimal
effort, so you can stop writing and GitBuilding. GitBuilding is a python program that
works on Windows, Linux, and MacOS. More information on the GitBuilding project, or how
to install GitBuilding please see the [GitBuilding website](http://gitbuilding.io)

### How do I edit the documentation?

To edit the documentation you do not need to install anything, but you will need to
install something to build the final version of the documentation (such as a website).
The documentation files can be opened in a plain text editor such as Windows Notepad,
Notepad++, gedit, VS Code, etc. GitBuilding also comes with a browser-based editor that
displays has a live display of the final HTML documentation.

If you have ever used [markdown](https://www.markdownguide.org/basic-syntax/) you will
notice that the files you are editing are markdown files. GitBuilding uses an extended
markdown syntax (that we call BuildUp). This allows you to keep track of parts in the
documentation. More detail on the documentation is available on the
[GitBuilding website](https://gitbuilding.io/syntax/). There is also additional
[syntax for configuration](https://gitbuilding.io/syntax/buildconfsyntax), and for
[part libraries](https://gitbuilding.io/syntax/builduplibrary/).

## License and Collaboration

This project is open-source and is released under the CERN open hardware license. All the design files are generally for free, but we would like to hear from you how is it going.

You're free to fork the project and enhance it. If you have any suggestions to improve it or add any additional functions make a pull-request or file an issue.

All files have been designed using [Onshape](https://www.onshape.com/en/) (EDUCATION)
