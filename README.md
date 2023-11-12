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
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_1.png?raw=true" />
    </a>
</p>
          II.  Drag and drop the IMV tab to the desired side of the canvas after the view has been selected (Desktop or mobile view). It will display the default asset (the box asset) to show that the function is operational.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_2.png?raw=true" />
    </a>
</p>
          III. On the right, click on the “PROPERTIES” tab. Then under the "Indexing Settings", we see the "Model Swap Parameter" and "Add Entry" button will be visible.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_3.png?raw=true"  />
    </a>
</p>
          IV.  The Model Swap Parameter is an editable class index that will house the names of all models within a particular indexable model operation. The default “swf” can be edited by the user if they wish.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_4.png?raw=true" />
    </a>
</p>
          V.  Click the Add Index Model to add desired indexable model(s). Here, the Index ID is spotted and is also editable by the user. In this tutorial, the Model Swap Parameter is replaced with the “user” while the Index ID stays “1”. Since we intend to publish three models, we add two more Index models to make three and we don't need to replace their Index IDs since it numerically increases by 1 each time a new index model is added (but you are free to customize it as you wish). Img (a) and (b) shows the consecutive steps just explained
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_5.png?raw=true" />
    </a>
</p>
<p align="center">
   (a)
    </p>
<p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_6.png?raw=true" />
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
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/assets/78617644/4f94e097-c855-4ea9-b518-5479bc9c36c2" />
    </a>
</p>
          VII.  The models get imported into the canvas. Then it can be published.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_8.png?raw=true" />
    </a>
</p>
          VIII.  Once the link is successfully deployed, you can specifically call each Indexed Model by adding “ ‘/’ + ‘?’ + ${Model Swap Parameter} + ‘=’ + ${Index ID}” then press enter.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_9.png?raw=true" />
    </a>
</p>
          So this makes our link becomes "https://bead-christmas.swiftxr.app/?user=1". To check other models, just replace the ${Index ID} (which is the number “1” in our case) with “2” or ”3” to individually view other indexed models.
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_10.png?raw=true" />
    </a>
</p>
          IX.  Now, in the case of website integration that the developer needs the iframe embedded code, it can be accessed by clicking the "copy embed" button on top of the web address modal (which appears after you have published your project).
          <br />
          &nbsp;
            <p align="center">
    <a href="">
      <img align="center" alt="GIF" src="https://github.com/swiftXR/indexable-viewer/blob/main/SwiftXR/new_swf_11.png?raw=true" />
    </a>
</p>
      


