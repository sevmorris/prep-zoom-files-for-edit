**STEPS FOR PREPPING FILES FOR EDIT**

***Prep Zoom files for Logic***

- Create a working dir for the project with a title in the standard format
- Copy the raw audio files from the Zoom dir(s) to the working dir
- Open Zoom files in iZotope RX9
  - Resample @ 44.1kHz
  - Save as 24bit wav


***Prep wavs for Descript***
- Create a Logic project with the same title as working dir
- Import the wavs into the project
    - Files from more than one source will need to be synced manually in Logic
- Create a subdir in working dir named "exports"
- Export files with _ss appended to file name to "exports" dir


***Process files in Descript***

- Create a new project with the same name as working dir
- Drag the files from "exports" into the Descript "Project Files" folder
- Apply Studio Sound to each file
- Create a composition from each file _after Studio Sound process completes_
- Select the composition, then select Share and export as a wav file


***Replace Logic files with new versions***

- Open the Logic project and delete the existing files
- Drag the new processed files exported from Descript into the Logic project
- Make any prep edits if needed
- Create a subdir in working dir named "prepped"
- Export all files to "prepped" dir


***Final checks and upload***

- Open files in iZotope and adjust level if necessary
- Upload for editor
