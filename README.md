This website provides the materials for the Tutorial [[T4] Computational Modeling of Musical Expression: Perspectives, Datasets, Analysis and Generation](https://ismir2019.ewi.tudelft.nl/?q=node/39) presented by Carlos Cancino-Chacón, Katerina Kosta and Maarten Grachten at the [20th International Society for Music Information Retrieval Conference (ISMIR 2019)](https://ismir2019.ewi.tudelft.nl).

The aim of this tutorial is to introduce the theory and practice of music performance research to a broad MIR audience. A music performance---an acoustic or audio-visual rendering of it---provides a much richer musical experience than the symbolic or notated representation of the performed music. This richness is arguably an important aspect of our engagement with music and is shaped by the musician's interpretation of the intentions of the music, as conveyed through their performance. The means of expressing these intentions vary from one instrument to another, and can include tempo, timing, dynamics, articulation, timbre, and intonation, among others.
In this tutorial we will give a brief overview of the music performance literature and highlight how expressive dimensions affect the perception and the creation of music. Furthermore we will showcase some state-of-the-art computational methods for both analysis and synthesis of expressive piano performances. 


## Materials for the Tutorial

### Slides

The slides of the presentation can be found [here](https://github.com/ofai/ismir2019_expressive_performance_tutorial/blob/master/ismir2019_T4_slides.pdf).

### Interactive Jupyter Notebooks

We include a hands-on part in which we share easily operated and adaptable code written in Python using Jupyter iPython notebook for demonstrating how to get started with computational analysis and synthesis of musical expression.

#### Hands-on Part I: Analysis of Performed Dynamics

The first hands-on part of this tutorial was presented by Katerina Kosta. 
It presents a case study to retrieve information from [MazurkaBL dataset](https://github.com/katkost/MazurkaBL) and provide tools to visualize it and imports models for dataset analysis.

[Interactive Jupyter Notebook](https://bit.ly/34s4LrU)

[Repository for the Notebook](https://github.com/katkost/MazurkaBL/blob/master/scripts/ismir_tutorial.ipynb)

Alternatively, setup locally using git:

1. Clone repository:
	
	```bash
	git clone https://github.com/katkost/MazurkaBL
	```
	
2. Install requirements:

	```bash
	cd MazurkaBL
	pip install -r requirements.txt
	```

3. Start Jupyter session:

   ```bash
   cd scripts
   jupyter notebook
   ```
   
4. In the browser window select file `ismir_tutorial.ipynb`.
	



#### Hands-on Part II: Generation of Expressive Performance

The second hands-on part of the tutorial was presented by Maarten Grachten and Carlos Cancino-Chacón. 
It provides an overview to the Basis Mixer, a machine learning system for generating expressive performances given a score.

[Interactive Jupyter Notebook](https://bit.ly/2WFL90A)

[Repository for the notebook](https://github.com/mgrachten/basismixer-notebooks)

Alternatively, setup locally using git:

1. Clone repository

	```bash
	clone https://github.com/mgrachten/basismixer-notebooks.git
	```
	
2. Install requirements

	```bash
	cd basismixer-notebooks
	conda env create -f environment.yml # or environment_macos.yml
	```
	
3. Start Jupyter session:
   
   ```bash
   jupyter notebook
   ```

## Presenters

[**Carlos Cancino-Chacón**](http://www.carloscancinochacon.com) is a postdoctoral researcher at the Austrian Research Institute for Artificial Intelligence (OFAI), Vienna, Austria. His research focuses on studying  expressive music performance, music cognition and music theory with machine learning methods. He pursued a doctoral degree on computational models of expressive performance at the Institute of Computational Perception of the Johannes Kepler University Linz, Austria. He received an M.Sc. degree in Electrical Engineering and Audio Engineering from the Graz University of Technology, a degree in Physics from the National Autonomous University of Mexico and a degree in Piano Performance from the National Conservatory of Music of Mexico.

[**Katerina Kosta**](https://www.katerinakosta.com) is a senior machine learning researcher at ByteDance AI lab. She pursued her Ph.D. from the Centre for Digital Music at the Computer Science and Electronic Engineering department of Queen Mary University of London, conducting research on computational modelling and quantitative analysis of expressive changes of dynamics in performed music. Research interests during her studies included time series analysis, custom data structures, pattern recognition, audio processing, and machine learning for music synthesis and analysis of perceived emotion in music audio. She received degrees from University of Athens (Mathematics) and Filippos Nakas Conservatory, Athens (Piano), and a Sound and Music Computing Masters from the Music Technology Group at Universitat Pompeu Fabra, Barcelona.

[**Maarten Grachten**](https://maarten.grachten.eu) is a senior researcher in machine learning for music and sound technology, currently active as an independent machine learning consultant. He holds an M.Sc. in Artificial Intelligence from University of Groningen (The Netherlands, 2001), and a Ph.D. in Computer Science and Digital Communication from Pompeu Fabra University (Spain, 2007). He has worked on computational modeling of musical expression in jazz and classical music since 2001. His work has been funded by European and national research grants at research institutions including the Austrian Research Institute for Artificial Intelligence (OFAI) and Johannes Kepler University (Austria), and has been published in international peer-reviewed conferences and journals.

## Acknowledgements
This work is partially supported by the European Research Council (ERC) under the European Union's Horizon 2020 Research and Innovation Programme under grant agreement No 670035 (project "Con Espressione").

<img src="http://erc.europa.eu/sites/default/files/LOGO_ERC-FLAG_EU_.jpg" width="350"/>

