# Detecting-Private-Communication-in-Video-Games

I co-authored an amazing research publication "A First Look at Private Communications in Video Games using Visual Features" in [PETS 2021](https://petsymposium.org/2021/paperlist.php)
> In this paper, we investigate the feasibility
of using video games and virtual environments to evade
automated detection, namely by manipulating elements
in the game environment to compose and share text
with other users.

---

### Table of Contents
You're sections headers will be used to reference location of destination.

- [Description](#description)
- [Dataset](#Dataset)
- [Technologies](#Technologies)
- [Research Paper](https://drive.google.com/file/d/1v1AZR_99Q4dxNaEl_fUNM-IAHo3wdsOR/view?usp=sharing)

---

## Description

Evading automated detection exploits the fact that
text spotting in the wild is a challenging problem in
computer vision. To test our hypothesis, we compile a
novel dataset of text generated in popular video games
and analyze it using state-of-the-art text spotting tools.
Detection rates are negligible in most cases. Retraining these classifiers specifically for game environments
leads to dramatic improvements.


## Dataset 

Click [Drive](https://drive.google.com/drive/folders/131jT-0YeHtpkzYrO_JZviU78Wgj7onGV) to access the dataset.

Below is the dataset structure.

```html
dataset
  |
  |----COD/               
  |----GTA/               
  |----Minecraft/               
  |------|
  |------|----Train/            
  |------|----Test/            
  |------|------|
  |------|------|----Images/
  |------|------|----Xmls/
```
---


## Technologies
We used two open source state of the art algorithms for our analysis.
- [ABCNet](https://github.com/aim-uofa/AdelaiDet/blob/master/configs/BAText/README.md)
- [DeepTextSpotter](https://github.com/MichalBusta/DeepTextSpotter)

[Back To The Top](#Detecting-Private-Communication-in-Video-Games)
