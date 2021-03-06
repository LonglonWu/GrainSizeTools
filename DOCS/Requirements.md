*last update 2020/03/18*

Requirements & Development
-------------

### Requirements

GrainSizeTools script requires [Python][1] 3.5+ or higher and the Python scientific libraries [*Numpy*][2], [*Scipy*][3], [*Pandas*][9] and [*Matplotlib*][4].

- Python (>= 3.6)
- Numpy (>=1.11)
- Scipy (>=0.13)
- Pandas (>=0.16)
- Matplotlib (>= 2.0.2)

We recommend installing the [Anaconda][5] distribution, as it includes all the required the scientific packages plus an scientific-oriented integrated development system (requires > 5 GB disk space). In case you have a limited space in your hard disk, there is a distribution named [miniconda][7] that only installs the packages you actually need.

GrainSizeTools script was designed to analyse and visualize grain size populations and estimate stresses via paleopiezometers. **It is therefore necessary to measure the diameters, the sectional areas or the volumes of the grains in advance and store them in a txt/csv/xlsx file**. For this task, we highly encourage you to use the [*ImageJ*](http://rsbweb.nih.gov/ij/) application or one of their different flavours (see [here](http://fiji.sc/ImageJ)). ImageJ-type applications are public-domain image processing programs widely used for scientific research that runs on Windows, macOS, and Linux platforms. The documentation contains a quick tutorial on how to measure the areas of the grain profiles with ImageJ, see *Table of Contents*. The combined use of **ImageJ** and **GrainSizeTools script** is intended to ensure that all data processing steps are done through free and open-source programs/scripts that run under any operating system.

If you are dealing with EBSD data instead, we encourage you to use the [MTEX toolbox](https://mtex-toolbox.github.io/) for grain reconstruction and the [export2file script](https://github.com/marcoalopez/export2file) for exporting the data (a tutorial on this will be available soon).



### For developers

There are two options here:

- Cloning the repository by clicking **Clone or download** under the repository name https://github.com/marcoalopez/GrainSizeTools or pasting the following URL using git:

```html
git clone https://github.com/marcoalopez/GrainSizeTools.git
```
- Forking the repository by clicking **Fork** in the repository name.

To see the differences between cloning and forking see https://github.community/t5/Support-Protips/The-difference-between-forking-and-cloning-a-repository/ba-p/1372

At the moment there is no automatic test to check the functionality of the script (it is a pending task!). In the meantime, you can check the functionality manually by performing the tests proposed in the following section: [running test](https://github.com/marcoalopez/GrainSizeTools/blob/master/DOCS/running_tests.md)



[next section](https://github.com/marcoalopez/GrainSizeTools/blob/master/DOCS/Scope.md)  
[table of contents](https://github.com/marcoalopez/GrainSizeTools/blob/master/DOCS/tableOfContents.md)



[1]: https://www.python.org/

[2]: http://www.numpy.org/

[3]: http://www.scipy.org/

[4]: http://matplotlib.org/

[5]: https://www.anaconda.com/distribution/

[6]: https://www.enthought.com/products/canopy/

[7]: http://conda.pydata.org/miniconda.html

[8]: http://rsbweb.nih.gov/ij/

[9]: http://pandas.pydata.org
