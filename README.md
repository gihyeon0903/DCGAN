# DCGAN
<br/>

### Datasets
-------------------
<a href='https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html'>CelebA</a> : 약 20k개의 연예인 얼굴 datasets

<p align="center">
  <img src="./result/celeba.jfif" width="300" height="200"/>
</p>

### Model
-------------------
DCGAN

<a href='https://drive.google.com/drive/folders/1LtAKipP0b6bzJz09njBBAYZRVnkU211y?usp=drive_link'>Weights</a>
<p align="center">
  <img src="./result/model.png" width="700" height="150"/>
</p>


### Train
-------------------
epochs : 10, learning rate : 0.0005, optimizer : Adam(Beta1, 2 = 0.5), Loss : MiniMax Loss <br>
1. Smile Man
2. Neutral Man
3. Neutral Woman

<br/>

### Result
-------------------
#### 1. D, G Loss
<p align="center">
  <img src="./result/SmileMan.png" width="440" height="320"/>
</p>

#### 2. Inference(Epoch = 1, 5, 10)
1. Smile Man
<p align="center">
  <img src="./result/smile_man_epoch.gif" width="350" height="260"/>
</p>

2. Neutral Man
<p align="center">
  <img src="./result/neutral_man_epoch.gif" width="350" height="260"/>
</p>

3. Neutral Woman
<p align="center">
  <img src="./result/neutral_woman_epoch.gif" width="350" height="260"/>
</p>

#### 3. Vector Arithmetic
* Smile Man - Neutral Man + Neutral Woman = Smile Woman
<p align="center">
  <img src="./result/vector arithmetic.gif" width="350" height="260"/>
</p>

#### 4. Walking in the latent Space
* Image A <-> Image B (interpolation)
<p align="center">
  <img src="./result/Walking in the latent Space 2.png" width="900" height="90"/>
</p>
