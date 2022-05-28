## Prepping Zoom Audio Files For Podcast Editors

---
These are _my_ specific step using _my_ specific software to process Zoom files for _my_ editors.

<details>
  <summary>Prep Zoom files for Logic</summary>
  <br>
  • Create a folder for the project with a title in the standard format<br>
  • Copy (do not move) original Zoom files to the working folder<br>
  • Open files in iZotope RX9:<br>
      • Resample @ 44.1kHz<br>
      • Save as 24bit wav<br>

</details>

<details>
  <summary>Pre-process wav files in Logic</summary>
    <br>
  • Create a Logic project with the same title as project folder<br>
  • Import wavs into Logic<br>
    (Files from more than one source will need to be synced manually in Logic)<br>
  • Create a subdir in project folder named "exports"<br>
  • Export files from Logic to "exports" folder<br>

</details>

<details>
  <summary>Process files in Descript</summary>
    <br>
  • Create a new Descript project with the same name as project folder<br>
  • Drag the files from "exports" into the Descript "Project Files" folder<br>
  • Apply Studio Sound to each file<br>
  • _After Studio Sound process completes_ create a composition from each file<br>
  • Append _ss to the end of composition titles<br>
  • Select each composition, then select Share and export as a wav file<br>

</details>

<details>
  <summary>Process final files in Logic</summary>
    <br>
  • Open the Logic project and delete existing audio<br>
  • Drag the new files exported from Descript into the Logic project<br>
  • Make cuts if needed<br>
  • Create a new subdir in project folder named "prepped"<br>
  • Export all files from Logic to "prepped" folder<br>

</details>

<details>
  <summary>Final checks and upload</summary>
    <br>
  • Open "prepped" files in iZotope and adjust level if necessary<br>
  • Upload for editor<br>

</details>
