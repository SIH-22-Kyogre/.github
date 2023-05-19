# Team Kyogre at Smart India Hackathon '22

## Project 1 - SatVision: AI-Driven Detection of Non-Residential Built-Up Clusters from Satellite Images

[**Link to Prototype Demo Video**](https://drive.google.com/file/d/1iFQUJNGRD8HNew-qzn8W0ULaZY_QRtxx/view).    
   
[**Link to Project Documentation and Related Resources**](https://drive.google.com/drive/folders/1pxgf16lKAE3KhUQMAe3u23BQO_tnjmZz?usp=share_link).

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

### Repositories

- [Landcover Visualization Frontend](https://github.com/SIH-22-Kyogre/satvision-mapviewer-frontend).
- [Landcover Visualization Backend](https://github.com/SIH-22-Kyogre/SatVision_MapViewer-Backend).
- [Real-time Satellite Image Acquisition](https://github.com/SIH-22-Kyogre/SatVision_Satellite-Image-Acquisition).
- [Machine Learning Experiments for Landcover Type Detection](https://github.com/SIH-22-Kyogre/SatVision_LandCoverDetection).
- [Application Pipelineing Utilities](https://github.com/SIH-22-Kyogre/SatVision_Pipelining-Utils).


## Project 2 - EyeSea: Real-Time Automatic Marine Species Threat Alerting at Shoreline via Underwater Surveillance

[**Link to Project Presentation Video**](https://www.youtube.com/watch?v=Xd86llXbR9c).    
   
[**Link to Project Documentation and Related Resources**](https://drive.google.com/drive/folders/1HKZbwZYPwmzcRHn4PJ2jxeqz1iDUWfdx?usp=share_link).

- High-definition underwater cameras are deployed using buoys, moored in the sea at an optimal distance from the coast. 
- To detect, localize, and identify lethal marine species, a pattern recognition algorithm analyzes real-time optical image feed from high-definition underwater cameras.
- On detecting a potentially lethal threat approaching the coast, the system sounds a public alarm as well as a personalized alert on swimmers' wearable devices to warn them of a possible threat.

<img alt="conceptual-setup" src="https://github.com/SIH-22-Kyogre/.github/assets/56585697/ebeadb96-ab7f-4c54-84ae-69612320515f" width="900" />

### Repositories
