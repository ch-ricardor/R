# R example

 
 Program: Example_codebook.R  
 Author: Ricardo Rodriguez 2014/11
   Script to create the basic information for the CodeBook.md

 =================================================================================
 Setting up the working environment:
 =================================================================================

  Directory structure:
      The directory structure for this application is controlled by some predefined variables, and it is
      represented by this structure:

      dWorkingDir
      dWorkingDir/I_Data
      dWorkingDir/I_export_Data
      dWorkingDir/I_programs | Any other valid path set in the I_programs variable.

      These variables should be modified to setup your personal working environment preferences, and allow you
      to decide where do you want to store the application and its results.
  VARIABLES:

      dWorkingDir - First part of the root directory path where the application is installed
                  NOTE: This directory path MUST exist.
      
  I_<varaibles>

      I_Data - Is the working directory path where the program will download, expand and store the working files files.
              NOTE: if the directory path doesn't exist, it will be created by the script.
      I_temp - Is the temporary directory path.
              NOTE: if the directory path doesn't exist, it will be created by the script.
      I_export_Data - Is the directory path where the program will create the new files to be reviewed.
              NOTE: if the directory path doesn't exist, it will be created by the script.
      I_Programs - Is the directory path where the auxiliary programs and scripts are stored.


 Modify this line to use your own directory path 
  NOTE: (dWorkingDir) 
     In blank would be the actual working directory
