# Segmentation4FTBatch
This macro allows a semi-automated segmentation and creation of ROI sets for fibrilToolBatch.
It can use as input 2D images created with SurfCut (https://github.com/sverger/SurfCut).
As output, it creates an input for FibrilTool_Batch.ijm (https://github.com/sverger/FibrilTool_Batch).

For more details on how to use the macro, see https://github.com/sverger/SurfCut/blob/master/SurfCut_UserGuide.pdf pages 15-18.

## Prerequisites:
- Fiji (https://fiji.sc).
- The ImageJ “MorphoLibJ” library. See installation procedure at https://imagej.net/MorphoLibJ.
- The "Segmentation4FTBatch.ijm" macro file.
- Data: 2D cell contour images in .tif. An example file is available in the /Test_file folder.

## Install/run:
1) Download the "Segmentation4FTBatch.ijm" macro file somewhere on your computer (You can put it in the Fiji "macros" folder for example)
2) Start Fiji.
3) In Fiji, run the macro: Plugins>Macros>Run…, and then select the “Segmentation4FTBatch.ijm” file. Or drag and drop the macro on Fiji
4) Then follow the instructions step by step. You can also follow the step by step user guide https://github.com/sverger/SurfCut/blob/master/SurfCut_UserGuide.pdf from page 15 to 18

## Output:
The macro outputs an ROIset file in .zip for each image analyzed
