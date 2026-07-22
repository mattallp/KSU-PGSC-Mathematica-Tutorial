# KSU-PGSC-Mathematica-Tutorial
Author: Matthew Allphin (mattallp@ksu.edu), PGSC Academic Chair 2026-2027

## Description
This is a crash course in the Mathematica programming language designed to help physics students at Kansas State University. The goal is to help students learn the basics of Mathematica essential for the physics graduate program at Kansas State University. This guide is a work in progress.


# Introduction
Welcome to Kansas State! This guide is originally intended to help new physics graduate students become familiar with Mathematica. Mathematica is a powerful educational tool that some professors may require you to use for classes. In addition, you may find Mathematica useful for research purposes such as creating plots, performing heavy computations, conducting data analysis, and many more tasks you might encounter in your academic career. 

This guide is by no means extensive; it will mostly cover the basics of syntax and provide some useful tips and examples. An accompanying PDF (WIP) will include formatting and style sheets. Note that this guide was written using Wolfram 15.0 on Windows and Linux, so some things may have changed depending on the version you are using. To get started, you will need to install Mathematica (see the section below on [Installing Mathematica](#InstallInstructions)). After you have successfully installed and activated Mathematica, you will want to download the Mathematica notebook included in this repo: [PGSC Wildcat Guide to Mathematica](PGSC-Wildcat-Guide-to-Mathematica.nb). You should then be able to open the notebook in Mathematica and begin working through the tutorial. 



The rest of this README will include instructions on how to install and activate a Wolfram Mathematica license as a student at KSU, an outline of how the GitHub repository is organized, and a Table of Contents/Topics list of the main Mathematica notebook file. If you have any questions, suggestions, or concerns, you can reach me at mattallp@ksu.edu or over Discord. 


<a name = InstallInstructions></a>
# Installing and Activating Mathematica 
As a student at KSU, you have access to a Mathematica License for the purpose of helping with your academic activities. K-State has its own set of instructions on how to activate a Mathematica license, found here: [KSU Mathematica Licenses](https://www.k-state.edu/it/resources/access-software/applications/mathematica/)

The basic process, however, is as follows:

1. Go to [http://users.wolfram.com](http://user.wolfram.com/)
2. Click on Single Sign-On (SSO)
3. Enter your K-State email (@ksu.edu)
4. You will be redirected to sign in through KSU
5. You will then need to fill out the [Wolfram Activation Key Request Form](https://user.wolfram.com/portal/requestAK/a5db253ebf5428b621947c33fb2200be20558931) to request an Activation Key. You should be promptly provided with an Activation Key ([SEE NOTE BELOW](#NOTE1))
7. You will then need to download and install Mathematica; there are several ways to do this. If you are logged in to Wolfram, you can go to the My Products Page and click on Wolfram Mathematica and download the installer specific to your operating system; there are instructions on how to install depending on your operating system as well.
   - You will also have the option to download the documentation locally on your computer. If you have the documentation locally, you don't need internet to access the documentation, and there are a lot of interactive documentation files that you can open directly in a Mathematica notebook. 
9. When you launch Mathematica, it will prompt you to enter your Activation Key, which you got earlier ([SEE NOTE BELOW](#NOTE1)). After using the Activation Key, Mathematica should be ready for use.
 
 <a name = "NOTE1"></a>
> [!NOTE]
> As of July 2026, I believe you don't actually need an Activation Key code to activate Mathematica. You may just need to create an account using your KSU credentials. After installing Mathematica, you will simply be prompted to log in to your Wolfram account, and after using Single Sign-On, your Mathematica should be activated and ready for use. 

You also have access to Wolfram Mathematica Online; however, this guide is intended for locally installed versions of Mathematica. 

# Repository Organization

This GitHub repository currently consists of three main files:
- README.md
- TASKLIST.md
     - This is an organized task list to help monitor progress on the project. This is mostly for my own bookkeeping, though any contributors may want to look at this. 
- PGSC-Wildcat-Guide-to-Mathematica.nb
     - This is the main Mathematica notebook tutorial file. This is the file you want to work through the tutorials.
# Current list of Topics/Table of Contents for PGSC-Wildcat-Guide-to-Mathematica.nb
   0. Introduction
   1. Basics: How to write and evaluate code, how to declare variables, and how to call functions.
      - Input and Output
        - Clearing and Suppressing Output
        - Documentation
        - Errors
        - Troubleshooting
        - Comments in code
      - Variables and Basic Functions
        - Exercise with Solution
      - Lists, Vectors, and Matrices
        - Exercise with Solution
   2. Functions and Numerics: How to define and evaluate functions in Mathematica, some nuances of the numerical calculations and units in Mathematica.
      - Function Definition
        - Exercise with Solution
      - Replace
      - Prefix and Postfix
        - Exercise with Solution
      - Numerics
      - Units in Mathematica
        - Wolfram|Alpha Shortcuts
        - Exercise with Solution
   3. Plotting and Graphics: Basic graphical features in Mathematica, including plots, graphics objects, and animations.
      - 1D Plots and Plot Options
        - Plot Options for Formatting
        - Nuances of Plot Commands
      - Plots in Higher Dimensions
      	- Plot3D
      	- Contour Plots
      	- Vector Fields
      	- Parametric Plots
      	- Complex Functions
