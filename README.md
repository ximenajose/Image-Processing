# Image-Processing
Image Processing Python Scripts for Practice

A set of python scripts, generated on both CLI and Jupyter Notebooks, are shared in this repository.

Basic Workflow:

1. Import Input_Image into Image_Processing and apply changes, run.
      >Image_Processing generates Output_Image.
2. Import Input_Image into Decompose_Image, run.
      >Decompose_Image outputs Input_Image.csv file.
3. Import Output_Image into Decompose_Image, run.
      >Decompose_Image outputs Output_Image.csv file.
4. Import Input_Image.csv and Output_Image.csv into Compare_CSVs
      >Compare_CSVs generates a delta report and a delta image showing differences.

Limitations:
1. System currently compares two identically pre-registered images.
2. System currently lacks registration features, which are being explored for implementation via OpenCV and/or sckikit-image.
3. System assumes 8-bit throughout, though it can be modified to accommodate 10, 12 or 16 bit as needed.
4. System assumes sRGB/Rec.709 luminance weights, though it can be modified to accommodate other standards.
5. System currently requires toggling back and forth between scripts and could benefit from integration, though not recommended at this time to prevent scope creep.
