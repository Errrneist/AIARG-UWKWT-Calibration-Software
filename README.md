<img align="right" src="https://github.com/Errrneist/AIARG-UWKWT-Calibration-Driver/blob/master/IMG/UW-Icon.jpg" alt="University of Washington" width="100">

# AIARG-UWKWT-Calibration Software
**[University of Washington](http://www.washington.edu/) [Kirsten Wind Tunnel](https://www.aa.washington.edu/AERL/KWT)-[Aircraft Icing and Aerodynamics Research Group](https://www.aa.washington.edu/research/AIARG)**

*[William E. Boeing Department of Aeronautics & Astronautics](https://www.aa.washington.edu/), [Boeing](http://www.boeing.com/), [NASA](https://www.nasa.gov/), [FAA](https://www.faa.gov).*
* A software for the University of Washington Kirsten Wind Tunnel to perform [Custom Calibration Tasks](https://github.com/Errrneist/AIARG-UWKWT-Calibration-Driver/blob/master/Documents/KWT_Sidewall_Software_Diagram.pdf). 
* Based on Labview and [ULx](https://www.mccdaq.com/daq-software/universal-library-extensions-lv.aspx) Package for Labview.
* The software reads and samples signals from six channels and processes the sampled data.
* It is capable to sample, record, plot, fit, analyze, and write Post-Processed matrix to a file.


<img align="right" src="https://github.com/Errrneist/AIARG-UWKWT-Calibration-Driver/blob/master/IMG/UW-AA.jpg" alt="University of Washington" width="350">

## Contributor

**Principal Investigator**

* *[Dr. Michael B. Bragg](https://www.aa.washington.edu/people/faculty/bragg)*

**Research Professor**

* *[Dr. Christopher Lum](https://www.aa.washington.edu/people/faculty/lum)*

* *[Dr. Mohamad Reza Soltani](http://ae.sharif.edu/~web/homepage.php?username=msoltani)*

**Software Developer**

* *[Hongjun Wu](https://github.com/Errrneist/AIARG-UWKWT-Calibration-Driver/blob/master/Documents/Resume-Github.pdf)*

**Lab Manager**

* *Kevin Ho*

**Kirsten Wind Tunnel Support**

* *Hannah Stevens*

**Staff**

* *Rami Slim*

## Sources
* [1] [ULX for NI Labview Documentation](https://www.mccdaq.com/PDFs/manuals/QS%20ULx%20for%20NI%20LabVIEW.pdf)
* [2] [InstaCal](https://www.mccdaq.com/daq-software/instacal.aspx)

## License
* [Apache License 2.0](https://github.com/Errrneist/AIARG-UWKWT-Calibration-Driver/blob/master/LICENSE.txt)

## Program Log
#### Stage I: Drafting and Function Testing
* Update 20171207: Project started after discussion.
* Update 20171209: Finished theory building and created a flow chart.
* Update 20171210: Downloaded ULx library and documents.
* Update 20171217: Completed first test program.
* Update 20180106: Completed project structure.
* Update 20180117: Received sample .EU file generated by the wind tunnel.
* Update 20180128: Uploaded code from Perforce to Github for developing convience.
* Update 20180220: Completed the main panel. Able to switch panels in between different VIs.
* Update 20180226: There is a Functions VI being created to demonstrate the features in the program.
#### Stage II: Framework Development
* Update 20180305: There is a "BIG BUG" issue that sample button doesn't latch when pressed once.
* Update 20180312: There is a ES file "Normal Beam.vi" File that demonstrates basic functions of the program.
* Update 20180313: Fixed a bug of connecting the axis of the plot to opposite side, and restructured the code.
* Update 20180314: Fixed a small issue that the sample button does not latch.
* Update 20180315: Project continueing permitted by Boeing. Determined future features to add.
#### Stage III: Engineering Sample MK-I (Theory Testing)
* Update 20180316: Might need to rewrite the main framework to optimize performance.
* Update 20180317: After discussion, decided to rewrite the main framework. GUI design planned.
* Update 20180325: Main framework rewrote completed and old prototypes are moved to the prototypes folder.
* Update 20180326: Engineering Sample MK-I released.
#### Stage IV: Engineering Sample MK-II (Data Collection and Channel Module)
* Update 20180329: Based on discussion, rewriting framework and GUI redesign started. 
* Update 20180401: Found a way to work around the "BIG BUG" issue.
* Update 20180402: The "BIG BUG" issue is solved after complete rewrite of main framework.
* Update 20180403: Wired up all 6 channels.
* Update 20180404: Added new feature: Main channel selection and its indicator.
* Update 20180405: Main Channel Selection (Universal Module) completed.
* Update 20180406: Added new feature: Waveform Graph.
* Update 20180407: Engineering Samle MK-II released.
#### Stage V: Engineering Sample MK-III (File Management and Output)
* Update 20180405: Added the "Final Matrix" onto the front panel.
* Update 20180408: Build main matrix with given data.
* Update 20180409: Attempt to write the matrix to a file. (DataFile.txt)
* Update 20180410: Add a header to the output text file.
* Update 20180411: Add "Main Channel" and "Time" to the header.
* Update 20180412: Optimize the format of the txt file.
* Update 20180413: Engineering Sample MK-III Released. 
#### Stage VI: Engineering Sample MK-IV (1st Stage Statistical Features)
* Update 20180414: Changed plot XY matrix to XY graph.
* Update 20180415: Plotted graphs to XY graph.
* Update 20180416: Changed color and plot line style to white.
* Update 20180417: Optimized GUI.
* Update 20180418: Organized file structure and optimized performance.
* Update 20180419: Add calculation of slope, SD, and r^2 to each graph.
* Update 20180420: Add a module to find best fit for the data.
* Update 20180421: Engineering Sample MK-IV released.
#### Stage VII: Beta Sample I (2nd Stage Statistical Features)
* Update 20180423: Decided to add a automated fit feature to the program. 
* Update 20180425: Decided to use tabular structure than automated fit.
* Update 20180430: Decided to fit three degree of polynomial fit in tabular window.
* Update 20180502: Finished first order linear fit graphs.
* Update 20180504: Finished second order polynomial fit graphs.
* Update 20180505: Fixed some minor bugs and optimized UI elements.
* Update 20180509: Experienced some hardship while programming the fit for third order polynomial.
* Update 20180512: Finished all polynomial fits wiring and optimized UI.
* Update 20180513: Beta Sample I released.
#### Stage VIII: Beta Sample II (Optimization)
* Update 20180514: Determined several features and UI optimizations to do. Preparing to present to Boeing.
#### Stage VX: Golden Master Edition (Review)
#### Stage X: Final


