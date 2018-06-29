# Name Generation using GRU network
Indian name generation using Gated Recurrent units. It uses a character level language model for this task.

## Test Results
<p align="center">
  <img src="media/1.JPG" >
 </p>
As you can see the model generates some names which doesn't sound quite indian, but with more data and training that problem can be solved.

## Training Plot
<p align="center">
  Training loss<br>
  <img src="media/loss.png" >
</p>

<p align="center">
  Training Accuracy<br>
  <img src="media/acc.png" >
</p>

## Model Architecture
It uses a unidirectional GRU network. 
<p align="center">
  <img src="media/model_plot.png" width="500" height="500">
</p>

