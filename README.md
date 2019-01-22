# Tutorials
Repository with data and code samples for running object detection and classification jobs using Nanonets API.

## Object Detection
- data
  - Contains the data for building and training an Object Detection Model to identify the Millenium Falcon and TieFighters.
- notebooks
  - Contains the ipython notebook which can be used as a reference or launched using mybinder to try out the APIs yourself and build your own object detection model<sup>[1](#footnote_1)</sup>.
  
  
## Image Classification
- data
  - Contains the data for building and training a simple two class image classification model<sup>[2](#footnote_2)</sup> to differentiate between cats and dogs.
- notebooks
  - Contains the ipython notebook which can be used as a reference or launched using mybinder to try out the APIs yourself and build your own image classification model<sup>[1](#footnote_1)</sup>.

  
<a name="footnote_1">1</a>: You will need a valid authentication key from https://app.nanonets.com/#/keys to be able to create models.
  
<a name="footnote_2">2</a>: You can very trivially extend this example to a multi-class classification model by adding more categories and uploading data for the newly added categories.
