This repository provides the supporting tools for the paper "Enabling Effective Requirements Compositional Verification for Complex Embedded Systems," where the methodological framework presented in the paper is implemented through algorithms, offering a complete process.

The tool adopts a front-end and back-end separation project development framework, with the front-end being the Vue framework and the back-end being the Springboot framework. The packaged front-end and back-end files are located in the CVCES folder, which contains:
-- CVCES-frontend, the packaged front-end files
-- CVCES-backend-1.0-SNAPSHOT.jar, the packaged back-end jar file

To deploy this tool, simply place the folders "nginx-1.22.1" and "CVCES" in the local computer's path "C:".

The process to start the tool is as follows:

Open the "nginx-1.22.1" folder and double-click on "nginx.exe" to start;
Open the "CVCES" folder and double-click on "startBackend.bat" to start.
This will launch the tool.

The CVCES-data folder provides five running cases from the paper, which can be executed using the tool.
The "CVCES Tool Demo Video.mp4" video file demonstrates the operation of the tool using the running case LCS.
