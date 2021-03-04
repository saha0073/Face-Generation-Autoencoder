# Face Generation with Autoencoder

Variational Autoencoder for actors face image generation using PyTorch.

## Dataset
The actors face were from Google Image using Selenium. Faces from the images were extracted using dlib.


## Results

### Training
<div>
<img src='https://github.com/saha0073/Face-Generation-Autoencoder/blob/main/images/loss.png', width="40%">
</div>

### Samples

Generated images are far from ideal, mainly because input data was quite dirty.



**Training images** (original vs. reconstruction)
<div>
	<img src='https://github.com/saha0073/Face-Generation-Autoencoder/blob/main/images/valid_orig.png', width="48%">
  <img src='https://github.com/saha0073/Face-Generation-Autoencoder/blob/main/images/valid_rec.png', width="48%">
</div>

**Testing images** (original vs. reconstruction)
<div>
	<img src='https://github.com/saha0073/Face-Generation-Autoencoder/blob/main/images/sample_input_1.png', width="48%">
  <img src='https://github.com/saha0073/Face-Generation-Autoencoder/blob/main/images/sample_output_1.png', width="48%">
</div>

<div>
<img src='https://github.com/saha0073/Face-Generation-Autoencoder/blob/main/images/sample_input_2.png', width="48%">
  <img src='https://github.com/saha0073/Face-Generation-Autoencoder/blob/main/images/sample_output_2.png', width="48%">
</div>

<br>
<br>

**New Samples**
<div>
	<img src='https://github.com/saha0073/Face-Generation-Autoencoder/blob/main/images/gen.png', width="60%">
</div>

Inspired by [milsun](https://github.com/milsun)