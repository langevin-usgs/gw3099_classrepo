Instructions to use Sagehen example problem notebook

 (1) Install Jupyter notebooks into Arcpy folder: 
					In Windows explorer navigate to C:\Python27\ArcGIS10.5\Scripts  (paths may vary)
               --type “cmd” in the folder address line
               --Type “pip install jupyter”
               
               
 (2)  Install pyprms into Arcpy folder
							--Copy pyprms folder from C:\Users\rniswon\Documents\Data\Git\gw3099_classrepo\exercises\GSFLOW\prmspy
							--Paste pyprms folder into C:\Python27\ArcGIS10.5\Lib\site-packages.

 (3)  Change file extension for gsflow
              --Change “gsflow.txt” to “gsflow.exe” in gw3099_classrepo\exercises\GSFLOW\examples\sagehen\model\bin
              
              
 (4)  Change paths in configuration file. 
             --Navigate to: .\gw3099_classrepo\exercises\GSFLOW\examples\sagehen.
             --Open “sagehen_parameters.ini” in text editor.
             --Replace first part of paths by globally replacing “C:\Users\rniswon\Documents\Data\Git\“ using the correct path for your computer.
             
 (5)  Navigate to .\ gw3099_classrepo\exercises\GSFLOW\notebook
             --Right click on “jupyter.bat” file and open in text editor.
             --In jupyter.bat change path “C:\Python27\ArcGIS10.5\Scripts\jupyter-notebook.exe” to be correct for your computer; save and close the file.
             --Double click jupyter.bat and the notebook should open.



