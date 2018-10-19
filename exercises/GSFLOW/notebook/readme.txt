Instructions to use Sagehen example problem notebook

 (1) Install Jupyter notebooks into Arcpy folder: 
				--In Windows explorer navigate to C:\Python27\ArcGIS10.5\Scripts  (#s in yellow vary)
        --type 'cmd' in the folder address line
        --Type 'pip install jupyter''
        
        * The following is incase the 1st version of python in each person's path is not python27 32-bit *
        --or: add the following to pip.ini in C:\Users\USERNAME\pip
        			[global]
							trusted-host = pypi.python.org
                             pypi.org
                             files.pythonhosted.org
              --then be in C:\Python27\ArcGIS10.5 and run following cmd: C:\Python27\ArcGIS10.5\Scripts\pip install jupyter
        --or: be in C:\Python27\ArcGIS10.5 and run following cmd:
         C:\Python27\ArcGIS10.5\Scripts\pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org --trusted-host pypi.python.org jupyter

 (2)  Need to change paths in configuration file. 
        --Navigate to: .\gw3099_classrepo\exercises\GSFLOW\examples\sagehen
        --Open 'sagehen_parameters.ini' in text editor.
        --Replace first part of paths by globally replacing 'C:\Users\rniswon\Documents\Data\Git\' using the correct path for your computer.

 (3)  Navigate to .\ gw3099_classrepo\exercises\GSFLOW\notebook
        --Right click on 'jupyter.bat' file and open in text editor.
        --In jupyter.bat change path 'C:\Python27\ArcGIS10.5\Scripts\jupyter-notebook.exe' to be correct for your computer; save and close the file.
        --Double click jupyter.bat and the notebook should open.
