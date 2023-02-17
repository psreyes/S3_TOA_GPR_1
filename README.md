# S3-TOA-GPR-1 vegetation products

Author: Pablo Reyes-Muñoz

Code: Pablo Reyes-Muñoz, Matías Salinero-Delgado

Workflow for mapping vegetation traits from the Sentinel3-OLCI collection in Google Earth Engine, from the paper "Quantifying fundamental vegetation traits over Europe using the Sentinel3 OLCI catalogue in Google Earth Engine".

This is a <b> guideline for mapping vegetation variables from TOA on Google Earth Engine (GEE) </b>, as proposed in Reyes-Muñoz et al., 2022.

<ol style='list-style-type:disc'> 
  <li> Please, click the link below to get access to the GEE repo (a GEE account is required): 
    https://code.earthengine.google.com/?accept_repo=users/pablosrmz/Github </li>
  
  </br>
    
  <li> Accept to add the repository in your GEE account and click the refresh button in the "Scripts" section. Then you should be able to see the code in the Reader section under the Scripts tab. </li>
  
  </br>
  
  <p style="text-align:center;"> <img src="https://user-images.githubusercontent.com/8297994/219678537-e97d40d3-8825-4534-8705-b2be0e4805bb.png" alt="Repo"> </p>

  
  <li> Access to the "settings" file and define the region of interest (ROI) and the time windows of the map (start_date and end_date). Draw your polygon of interest through the tools pannel at left in the map visualizer. Make sure that the variable ROI correspond to the name assigned to the new created polygon (var geometry). By default a composition map of 1 month will be produced between the start_date and the end_date in the demonstration.</li>
  
  </br>
  
  <li> Access to the "Plot" file (optionally) to apply further configurations for plotting (e.g. color palette, legend configuration) </li>
  
  </br>
  
  <li> Access to the "Main" file and click run in the upper buttons section </li>
  
  </br>
  
  <p style="text-align:center;"> <img src="https://user-images.githubusercontent.com/8297994/219683269-1ad8df5b-0f00-4a10-897d-7e1c6877e9b1.png"></p> 

  </br>
  
</ol>

For <b> training and exporting customized models from ARTMO to GEE </b>, please follow the guidelines in https://github.com/msalinero/ARTMOtoGEE.git

A workflow in Python to produce <b> time series mapping </b> over a region of interest can be found in <a href="https://colab.research.google.com/github/daviddkovacs/Global-EVT-maps/blob/main/Main%20Python%20script.ipynb"> this link</a>   
