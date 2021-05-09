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
- [Technologies](#how-to-use)
- [Dataset](https://drive.google.com/drive/folders/131jT-0YeHtpkzYrO_JZviU78Wgj7onGV)
- [Research Paper](https://drive.google.com/file/d/1v1AZR_99Q4dxNaEl_fUNM-IAHo3wdsOR/view?usp=sharing)
- [Author Info](#author-info)

---

## Description

Evading automated detection exploits the fact that
text spotting in the wild is a challenging problem in
computer vision. To test our hypothesis, we compile a
novel dataset of text generated in popular video games
and analyze it using state-of-the-art text spotting tools.
Detection rates are negligible in most cases. Retraining these classifiers specifically for game environments
leads to dramatic improvements.

## Technologies
We used two open source state of the art algorithms for our analysis.
- [ABCNet](https://github.com/aim-uofa/AdelaiDet/blob/master/configs/BAText/README.md)
- [DeepTextSpotter](https://github.com/MichalBusta/DeepTextSpotter)


[Back To The Top](#read-me-template)

---

## How To Use

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
[Back To The Top](#read-me-template)

---

## References
[Back To The Top](#read-me-template)

---

## License

MIT License

Copyright (c) [2017] [James Q Quick]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#read-me-template)

---

## Author Info

- Twitter - [@jamesqquick](https://twitter.com/jamesqquick)
- Website - [James Q Quick](https://jamesqquick.com)

[Back To The Top](#read-me-template)
