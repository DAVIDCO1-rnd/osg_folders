Important environment variables: 
===============================
OSGCOMPUTE_FILE_PATH / OSG_FILE_PATH
--------------------
If the examples are built please ensure that the data will be available.
Set the environment variable OSGCOMPUTE_FILE_PATH to the folder which contains the
osgCompute data (e.g. C:\SVT\osgCompute-Data).

You have to setup the OSG_FILE_PATH environment variable accordingly in order to find these files. 
Please add OSGCOMPUTE_FILE_PATH to OSG_FILE_PATH. This ensures that OSG is able to load the
necessary data successfully.

On Windows adapt the environment variable in the system properties and add to the OSG_FILE_PATH variable
   C:\SDK\OpenSceneGraph-Data;C:\SDK\OpenSceneGraph-Data\Images;%OSGCOMPUTE_FILE_PATH%
On Unix systems do the following:
  export OSG_FILE_PATH=$OSG_FILE_PATH:$OSGCOMPUTE_FILE_PATH