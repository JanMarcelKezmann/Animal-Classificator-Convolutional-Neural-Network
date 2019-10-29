# Convolutional Neural Network Animal Classificator

<p>The goal of this kernel was to build a clean image classificator that includes Data Augmentation as well as Model Evaluating and Fine-Tuning. I tried to create a general approach of solving this kind of problems for image classifications which can be reused for different kind of image data.</p>

## The Dataset
<p>The Dataset can be found and downloaded here on <a href="https://www.kaggle.com/alessiocorrado99/animals10">Kaggle.</a></p>

## Local Installation

### Clone the repo (or simply download it)
```shell
git clone https://github.com/JanMarcelKezmann/Animal-Classificator-Convolutional-Neural-Network.git
```

### Install requirements
##### (go into the new folder)

```shell
pip install -r requirements.txt
```

### Run with JupyterNotebook or JupyterLab
<p>Just open the .ipynb code in a Notebook of your choice and run it.</p>

## Run the Code via the Google Colab
<p>Because the code was written in the colaboratory of Google you can simply open it in there and run it after uploading the data to the drive.</p>

## Results
<p>Evaluated were two different convolutional neural networks: The Inception V3 and the Inception ResNet V2.</p>
<p>The best result was achieved even before trying to fine-tune the models.</p>

<table style="text-align:center">
  <tr>
    <th>Model</th>
    <th>Inception V3</th>
    <th>Inception ResNet V2</th>
  </tr>
  <tr>
    <td><strong>Loss:</strong></td>
    <td>0.9624</td>
    <td>0.8385</td>
  </tr>
  <trr">
    <td><strong>Accuracy:</strong></td>
    <td>85.29 %</td>
    <td>89.33 %</td>
  </tr>
</table>

### Problems with the Accuracy
<Checking out a couple of images I found out that some pictures were put into the wrong folder in the original dataset. This means that for example a dog picture is put into the horse folder.</p>
<p>This could potentially result in a worse accuracy for about 1 % which is not huge but still relevant.</p>

## References

[1] https://www.kaggle.com/alessiocorrado99/animals10
