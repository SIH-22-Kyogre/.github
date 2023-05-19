## Team Kyogre at Smart India Hackathon '22

### Project 1: SatVision: AI-Driven Detection of Non-Residential Built-Up Clusters from Satellite Images

[Link to Project Documentation and Related Resources](https://drive.google.com/drive/folders/1pxgf16lKAE3KhUQMAe3u23BQO_tnjmZz?usp=share_link).

The identification of non-residential built-up areas and detecting clusters of such regions can greatly aid strategic industrial
expansions, developmental planning, and understanding the earth’s topography in general.

The proposed solution aims to achieve detection of non-residential built-up areas clusters through **AI-driven analysis of Medium Resolution Satellite Imagery**. 
In a systematic approach, the solution aims to,
- Prepare annotated datasets for using standard satellite imagery collected by NASA, ESA and ISRO.
- Utilize existing annotated datasets to support model building.
- Deep CNNs to detect, segment and identify clusters of non-residential built-up regions.
- Evaluate its performance on highly-populated regions like Mumbai, Kolkata, Bangalore, and Delhi that pose a complex topography to detect patterns from. 
- Leverage geographic metadata and topological constraints to refine the solution formulation at multiple steps, including annotated dataset preparation and post-processing the Deep CNN results.
- As a user endpoint, we build a GUI tool that visualizes landcover segmentation overlays on geographic maps generated through a novel `patchify-process-reconstruct` pipeline.

#### Repositories

- [Landcover Visualization Frontend](https://github.com/SIH-22-Kyogre/satvision-mapviewer-frontend).
- [Landcover Visualization Backend](https://github.com/SIH-22-Kyogre/SatVision_MapViewer-Backend).
- [Real-time Satellite Image Acquisition](https://github.com/SIH-22-Kyogre/SatVision_Satellite-Image-Acquisition).
- [Machine Learning Experiments for Landcover Type Detection](https://github.com/SIH-22-Kyogre/SatVision_LandCoverDetection).
- [Application Pipelineing Utilities](https://github.com/SIH-22-Kyogre/SatVision_Pipelining-Utils).
