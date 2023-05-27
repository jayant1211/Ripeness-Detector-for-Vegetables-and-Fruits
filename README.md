# Ripeness Detector for Vegetables and Fruits
[Dec 2021 - Jan 2022] 

To access a comprehensive and detailed methodology, please refer to the our publication in IEEE CONIT 2022<br>
IEEE Explore: https://ieeexplore.ieee.org/document/9847917

The ripening and color transition of fruit and vegetables are closely related to each other. Changes in Chlorophyll, Carotenoids, flavonoids and other important pigments decide the color of fruit and vegetables. As fruit/vegetables ripe, over time, the number of these particular pigments changes, changing the color of the fruit or vegetables. Using this relationship based on color, and by using appropriate technology one can determine the ripeness of the fruit and vice versa for a particular fruit or vegetable. It has been shown that different color spaces produce different results with spectral analysis.

<img src="https://github.com/jayant1211/Ripeness-Detector-for-Vegetables-and-Fruits/blob/main/rsc/img.jpg" width="75%" height="75%">

The aim of this project is to detect Fruits/Vegetables Ripeness by Analysing their Spectral Composition. Based on Values of Red, Green, and Blue intensities, we aim to classify fruits/vegetables into 4 classes as Early Ripe, Partially Ripe, Ripe, and Decay using the proposed system.

<img src="https://github.com/jayant1211/Ripeness-Detector-for-Vegetables-and-Fruits/blob/main/rsc/Screenshot%202023-04-26%20194012.png" width="50%" height="50%">

### Steps:
A. Read and note the Colour intensity of Fruit or vegetable using TCS34725 in terms of RGB Values. (Can refer .csv file for this)

B. Map the readings to 8-bit value (0-255).

C. Train ANN Model with the mapped values.

D. Assemble the circuit setup comprising 4 LEDs(Red, White, Green, Yellow) and an Arduino board.

Schematics:<br>
<br>
<img src="https://github.com/jayant1211/Ripeness-Detector-for-Vegetables-and-Fruits/blob/main/rsc/Screenshot%202023-04-26%20194651.png" width="50%" height="50%">

D. Using Python code to interface with an Arduino board, the program outputs one of four classifications - Early Ripe(0), Partially Ripe(1), Ripe(2), or Decay(3) - based on the status of the connected device. (refer main.ipynb)

E. Each unique output lits up a unique LED.

## Cite
If you use our study in your research, please consider citing us, Thanks:

<h3>BibTeX Citation</h3>

  <pre><code>
@INPROCEEDINGS{9847917,
  author={Pawar, Shital and Meshram, Jayant and Mondhe, Ajinkya and Nachan, Akash and Nilangekar, Tejas and Patil, Aditya},
  booktitle={2022 2nd International Conference on Intelligent Technologies (CONIT)},
  title={Ripeness Detector for Vegetables and Fruits},
  year={2022},
  volume={},
  number={},
  pages={1-5},
  doi={10.1109/CONIT55038.2022.9847917}
}
  </code></pre>
  
 


