Deployed version : https://metacell.github.io/sds-viewer/
- [User Manual - Loading Datasets](https://github.com/MetaCell/sds-viewer/tree/development#sds-viewer-user-manual)
- [User Manual - Navigating the Components](https://github.com/MetaCell/sds-viewer/tree/development#navigating-the-sds-viewer)
- [Running Application Locally](https://github.com/MetaCell/sds-viewer/tree/development#sds-viewer-running-instructions)

## SDS Viewer User Manual 

The SPARC SDS Viewer is compatible with SPARC Portal (https://sparc.science) datasets and models. New functionality allows you to launch the SDS viewer with a SPARC dataset or model preloaded using the SDS Viewer button on the dataset or model landing page.

In addition, users can load datasets from the SPARC portal in two other ways:

1) Loading a SPARC Dataset from list:
   - Click on 'SPARC Datasets' button, it's located on the lower left corner.
   - On the window that opens up, select the dataset you want to load. 
   ![image](https://user-images.githubusercontent.com/4562825/166984322-83b4a8c2-aa29-4e6d-96e9-bcf4d125a3a9.png)
   - After selection, click 'Done'
   - Dataset will be loaded.
   - Datasets list comes from https://cassava.ucsd.edu/sparc/datasets/

2) Loading a dataset specifying DOI as parameter
   - Users can specify the DOI of a SPARC Portal dataset as a parameter on the URL and load it this way.
   - For example, if user wants to load Dataset with DOI 10.26275/qskp-awpu, we can add the id as parameter : 
     https://metacell.github.io/sds-viewer/?doi=10.26275/qskp-awpu
     This will open up the SDS Viewer with the dataset already loaded.
     
![loadwithid](https://github.com/MetaCell/sds-viewer/assets/99416933/2daf28db-c604-4d2d-9a3f-c9de494d5d6f)

     
### Navigating the SDS Viewer
   - Users can search for subjects, folders and files on the sidebar. Selecting an item on the sidebar will display the Metadata for it and zoom the Graph to its corresponding node. 

![clickonitem](https://github.com/MetaCell/sds-viewer/assets/99416933/824f8c44-d8fd-473b-a9bd-ce2ebed701ad)

   - Selecting an item on the Graph will display its Metadata. 

![image](https://user-images.githubusercontent.com/4562825/186723085-c6573146-82dc-4fb7-ae95-588f7b1e4842.png)

   - Navigating the Graph Viewer can be done with the mouse. There's also controlers on the bottom right that allows the user to change the Layout view, zoom in/out, reset the view to its original state and expand all data in the viewer.

![controllers](https://github.com/MetaCell/sds-viewer/assets/99416933/30aa8bb3-ec61-46d8-9f83-55ade15b95c0)

   - Multiple Datasets can be loaded at the same time, which will open a new Graph Viewer Component for each dataset.

![multiple](https://github.com/MetaCell/sds-viewer/assets/99416933/a74fa033-ccd4-4609-b50f-852ce44d347a)


### Datasets Used
The SPARC SDS Viewer is compatible with SPARC Portal (https://sparc.science) datasets and models. 

### Error Handling
- In the case of encountering an error, take a screenshot and report it with us please by opening an [issue](https://github.com/MetaCell/sds-viewer/issues/new). If you do not have a GitHub account you can still submit your feedback at [SPARC Contact Us](https://sparc.science/contact-us?source_url=%2Fdata%3Ftype%3Ddataset%26search%3D). 
- To go back , click on the 'x' to go back to the previous screen.
