# Beaded_Streams
Code to detect beaded stream locations throughout the Arctic using decision tree classification and YOLO object detection from high-resolution Planet imagery. 

In the src/ folder there are five different R Markdown scripts:

- 1_merge_catchments merges MERITHydro catchments with previously detected beaded streams and circumpolar land cover and permafrost data from the National Snow and Ice Data Center

- 2_CART_analysis classifies catchments as potentially beaded or non-beaded based on training from a random sample of manually identified catchments, as well as previous studies

- 3_download_Planet includes python code to search and download Planet imagery

- 4_YOLO_analysis describes some of the code used to run the You-Only-Look-Once version 5 object detection algorithm

- 5_Figures gives a brief description of figure creation, and code to reproduce some of the figures in the corresponding manuscript 'Mapping and characterizing Arctic beaded streams through high resolution satellite imagery' submitted to Remote Sensing of the Environment

