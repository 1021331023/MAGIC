# Map-Guided Few-Shot Audio-Visual Acoustics Modeling

## The failure case

We visualize the failure results of eval as follows.

### The given observations and query location
We provide a house tour gif to help understand the 3D scene and a top-down map indicate the locations of given few-shot observations and the query.

<p align="center">
  <img src="images/failure.gif">
</p>

<p align="center">
  <img src="images/failure.png">
</p>


Blue pinpoints indicate the provided viewpoints. The blue arrow represents the direction of the provided viewpoints. The green pinpoint indicates the speaker that emits the audio in the query and the pink pinpoint indicates the listener that receives the audio. 

### The grouth truth audio
<p align="center">
  <img src="images/failure-gt.png">
</p>

### Few-ShotRIR predicted audio
<p align="center">
  <img src="images/failure-baseline.png">
</p>

### ours predicted audio
<p align="center">
  <img src="images/failure-ours.png">
</p>

## The failure case 2

We visualize the failure results of eval as follows.

### The given observations and query location
We provide a top-down map indicate the locations of given few-shot observations and the query.

<p align="center">
  <img src="images/failure-2.png">
</p>


Blue pinpoints indicate the provided viewpoints. The blue arrow represents the direction of the provided viewpoints. The green pinpoint indicates the speaker that emits the audio in the query and the pink pinpoint indicates the listener that receives the audio. 

### The grouth truth audio
<p align="center">
  <img src="images/failure-gt-2.png">
</p>

### Few-ShotRIR predicted audio
<p align="center">
  <img src="images/failure-baseline-2.png">
</p>

### ours predicted audio
<p align="center">
  <img src="images/failure-ours-2.png">
</p>