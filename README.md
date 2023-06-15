# WELCOME

# music-generation

## DESCRIPTION

This research paper explores the use of deep learning techniques, specifically the WaveNet architecture, for automatic music generation. The objective is to create enjoyable music without the constraint of adhering to traditional musical theory rules. The learning process focuses on modeling audio waveforms directly, utilizing Long ShortTerm Memory (LSTM) networks in conjunction with WaveNet. The WaveNet architecture, built upon Causal Dilated 1D Convolution layers, allows for capturing long-range dependencies and producing high quality music outputs. The research utilizes a dataset of classical music MIDI files, and the training phase involves predicting subsequent amplitude values given a sequence of input values. The generative phase involves iteratively selecting the most probable values from the model's learned patterns to construct a new musical composition. Overall, this research contributes to the advancement of deep learning in the field of automatic music generation.

All code retrieved from: [https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/](https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/)

**For more detailed see paper: [Music Generation Paper PDF](music_generation_abd_al_muttalib.pdf)**

## Run:

### Setup env:

```
python -m venv env
.\env\Scripts\activate
```

### Install requirements:

```
pip install -r .\requirements.txt
```

### To Run, and Enjoy :)

```
python app.py
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Authors

* **Abd Al-Muttalib Ibreighith**

**Contact me on Gmail:** officialabdib@gmail.com

# THANKS
