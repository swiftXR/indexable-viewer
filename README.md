
[//]: # "indexable-viewer"

[//]: # "A sample website using SwiftXR Indexable viewer" 

# What's new?

[//]: # "## SwiftXR Overview"

[//]: # "<p> SwiftXR is a fast no-code, cross-platform development solution for building lightweight interactive 3D, AR, and VR experiences. </p>"

## New features/Updates.

<p> These are technical updates and existing upgrades that will improve usability and user experience . They include; <p/>

###  1. Indexable Model Viewer.
   <p> This is an Individual product publishing identification feature that enables each asset to be called uniquely to an assigned space when the project is published. To give a clearer explanation, we will be taking an e-commerce website as a case study. For every product that is on sale, the 3D models will be imported to the SwiftXR canvas, each model will have a model ID with a collective Model Swap Parameter. This means that at the start of the project, SwiftXR will automatically assign a value for the  Model Swap Parameter (this value can be changed by the user). This value assigned will serve as a housing for all the model IDs. Below is a detailed tutorial on how to publish projects of this nature ; </p>
          I.  To start with, the “indexable model viewer” tab can be located in the Design Components > 3D Viewer Components > Indexable Model viewer (IMV).
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR7.png?raw=true" width="947" height="286" />
    </a>
</p>
          II.  Drag and drop the IMV tab to the desired side of the canvas after the view has been selected (Desktop or mobile view). It will display the default asset (the box asset) to show that the function is operational.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR1.png?raw=true" width="1917" height="550" />
    </a>
</p>
          III. On the right, click on the “configurator tab”. Here, the Model Swap Parameter and Add Index Model button will be visible.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR2.png?raw=true" width="382" height="547" />
    </a>
</p>
          IV.  The Model Swap Parameter is an editable class index that will house the names of all models within a particular indexable model operation. The default “swf” can be edited by the user if they wish.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR8.png?raw=true" width="382" height="535" />
    </a>
</p>
          V.  Click the Add Index Model to add desired indexable model(s). Here, the Index ID is spotted and is also editable by the user. In this tutorial, the Model Swap Parameter is replaced with the “user” while the Index ID is replaced with “a”. Since we intend to publish three models, we add two more Index models to make three and we replace their Index IDs with “b” and ”c” respectively. Img (a) and (b) shows the consecutive steps just explained
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR3.png?raw=true" width="350" height="532" />
    </a>
</p>
<p align="center">
   (a)
    </p>
<p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR9.png?raw=true" width="350" height="532" />
    </a>
</p>
<p align="center">
   (b)
    </p>
          VI.  Then the models should be dragged and dropped in the box that says “Paste link or drag glb…”.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR4.png?raw=true" width="377" height="532" />
    </a>
</p>
          VII.  The models get imported into the canvas. Then it can be published.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR5.png?raw=true" width="1917" height="350" />
    </a>
</p>
          VIII.  Once the link is successfully deployed, you can specifically call each Indexed Model by adding “ ‘/’ + ‘?’ + ${Model Swap Parameter} + ‘=’ + ${Index ID}” then press enter.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR10.png?raw=true" width="407" height="30" />
    </a>
</p>
          So this makes our link become “https://new-swiftxr-project-3001.netlify.app/?user=a”. To check other models, just replace the ${Index ID} (which is the letter “a” in our case) with “b” or ”c” to individually view other indexed models.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR6.png?raw=true"  width="800" height="350"/>
    </a>
</p>
          IX.  Now, in the case of website integration that the developer needs the iframe embedded code, it can be accessed by clicking the Embed project as HTML button close to the Publish button.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/SwiftXR13.png?raw=true" width="557" height="66" />
    </a>
</p>
      


