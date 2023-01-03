# deeplabcut_testing
 *** how to install deeplabcut on your system (windows) ***

Windows 10/11

Step 1. Download Anaconda ==> Download the appropriate Anaconda file using this link: https://www.anaconda.com/distribution/


Step 2. Navigate to http://www.mackenziemathislab.org/deeplabcut and scroll to the bottom of the page to locate the “DOWNLOAD CONDA FILE” button in purple. Download file. 


Step 3. Make “DeepLabCut” folder 

Step 4. Run Anaconda Navigator (Anaconda3)

Step 5. In Anaconda Navigator, launch “CMD.exe Prompt”. When you click on launch, you will see a command prompt window pop up.

Step 6. In this command window change the directory to where you saved your “DEEPLABCUT.yaml” file. 

For example, type: 
cd C:\Users\YourUserName\Documents\DeepLabCut


Step 7. Next download the necessary packages. You can do this by typing:
conda env create -f DEEPLABCUT.yaml
You will then see packages being downloaded and installed. This process will take a few minutes.

Step 8. You may be prompted to approve the installation of “python.exe”. If this happens, enter your administrator password. Further dependencies will be installed.


Step 9. When the installation is done, activate the environment by typing: 
conda activate DEEPLABCUT

Step 10. Close command prompt.

Step 11. In the Anaconda Navigator, select “DeepLabCut” under the “Applications on” dropbox.

Step 12. Look for “CMD.exe Prompt” and click on “Install”. Enter Administrator credentials when prompted.

Step 13. After installing CMD.exe, click on “Launch”.

Step 14. To launch a DeepLabCut session

step 15. on activatted session of DeepLabcut on anconda prompt(DeepLabcut) open jupyter by write the following
1- Jupyter Notebook. 

2- clicking on “New” and selecting your DeeplabCut environment (in Jupyter Notebooks)

--------------------## now you have successfully installed DeepLabCut in your system on deeplabcut conda environment ##----------------------------------

step 16. Create a DeepLabCut Project by the following commands

1- import deeplabcut
# Note: To get some feedback for the successful import, you can add the print function:
print(f'Successfully imported DeepLabCut version: {deeplabcut. __version__}')


2- use this link to complete your project ==> https://pigeonsupermodel.com/DLC_StudentGuide.html#installation

# deeplabcut_testing

Yours should be similar to mine. If you are struggling, watch this video first. Click Here
If you're still struggling, come get me or the TA.# deeplabcut_using
