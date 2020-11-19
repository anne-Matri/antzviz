## antzviz
This repository contains jupyter notebooks with the python code for visualization designs to be shown in OpenANTz software. 

OpenANTZ software can be found at this [**github repository**](https://github.com/openantz/antz).
Getting started is easy, see these [**User Commands**](https://github.com/openantz/antz/wiki/User-Commands) at the OpenANTz wiki.

In order to view data in OpenANTz, raw data is converted into attributes of 3D models, like color, shape, and scale, etc. The template format is a 94 column node csv file. Each column represents a different potential attribute, and each row is a different 3D node, or object. Parent-child relationships between nodes generate hyperglyphs.

The files in this repository will help users recreate the node csv files, along with labeling files like a tag csv file format.

### Directories
- **Covid Visualizations**: The designs show data from CMU's CovidCast API along with policy information gathered by Oxford's Blavatnik School of Government. 
  - Most visualizations in this repository are shown per month, with child nodes - a toroid and set of rods - that shows data per day. Those nodes change in size relative to changes in the underlying raw data.
  
- **Wearable Visualizations**: These designs show different trials with data from Oura rings, Apple Health Kit (watches), blood glucose monitor, and food tracking apps.
  - The underlying data is not shared for most of these designs, but users can easily read in their own data and use these files to make designs with their own data.
  - The exception to shared data is public, anonymized Oura ring data from the TempPredict Study.
   - A preprint of the research paper, along with the data, can be found [**here**](https://www.researchsquare.com/article/rs-43914/v1)


Additional information can be found at [**www.matridesign.com**](https://www.matridesign.com)

For questions, see contact information @anne-Matri's profile.
- Please note: I'm new to python, so if you've got suggestions for cleaning the code I'm happy to hear them.
