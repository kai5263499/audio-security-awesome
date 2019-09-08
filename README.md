audio-security-awesome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)[![Travis](https://api.travis-ci.org/kai5263499/audio-security-awesome.svg?branch=master)](https://travis-ci.org/kai5263499/audio-security-awesome)

------------------------------------------------------------------------------------------

A collection of audio security related resources

* Voice Cloning
  * [**Blog Posts**](#voice-cloning-blog-posts)
  * [**Voice Cloning Papers**](#voice-cloning-papers)
  * [**Voice Cloning Implementations**](#voice-cloning-implementations)

* [Datasets](#datasets)

* [Speech To Text](#speech-to-text)

* [Text To Speech](#text-to-speech)

* [Commercial Services](#commercial-services)

------------------------------------------------------------------------------------------

# Voice Cloning Blog Posts
------------------------------------------------------------------------------------------
### [Audio texture synthesis and style transfer](https://dmitryulyanov.github.io/audio-texture-synthesis-and-style-transfer/)

### [CycleGAN VC](http://www.kecl.ntt.co.jp/people/kaneko.takuhiro/projects/cyclegan-vc/)
* Parallel-Data-Free Voice Conversion Using Cycle-Consistent Adversarial Networks

# Voice Cloning Papers
------------------------------------------------------------------------------------------
### [VoCo: Text-based Insertion and Replacement in Audio Narration](http://gfx.cs.princeton.edu/pubs/Jin_2017_VTI/Jin2017-VoCo-paper.pdf)

### [Great Reddit thread](https://www.reddit.com/r/MachineLearning/comments/8o7mkt/d_is_there_an_implementation_of_neural_voice/)

# Voice Cloning Implementations
------------------------------------------------------------------------------------------
### [Real Time Voice Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning)
* GUI Python toolbox that boasts the ability to clone a voice with 5 seconds of sample data
* Uses PyTorch and requires a GPU
* [Video presentation of toolbox features](https://youtu.be/-O_hYhToKoA)

### [Audio Style Transfer](https://github.com/vadim-v-lebedev/audio_style_tranfer)
* Python, Theano

### [GAN SASS TF](https://github.com/khaotik/GAN_SASS_TF)
* Python, Tensorflow

### [SpecGAN](https://github.com/naotokui/SpecGAN)
* Python

### [Neural Style Audio TF](https://github.com/DmitryUlyanov/neural-style-audio-tf)
* Python, Tensorflow, librosa

### [WaveGAN](https://github.com/chrisdonahue/wavegan)
* Python

# Datasets
------------------------------------------------------------------------------------------

Here are a collection of audio datasets for training new models

### [Google Audio Set](https://research.google.com/audioset/index.html)

### [Urban Sound Dataset](https://serv.cusp.nyu.edu/projects/urbansounddataset/)
* Contains urban sound tags like birds, car horns, etc

### [RAVDESS](https://smartlaboratory.org/ravdess)
* The Ryerson Audio-Visual Database of Emotional Speech and Song
* Contains emotion tags

### [LJ Speech](https://keithito.com/LJ-Speech-Dataset/)
* 13,100 short audio clips of a single speaker reading passages from 7 non-fiction books
* Sourced from the LibriVox project

### [Blizzard Challenge 2017](https://synsig.org/index.php/Blizzard_Challenge_2017)
* Data comes from professional audiobooks produced by Usborne Publishing

### [CSTR VCTK Corpus](http://homepages.inf.ed.ac.uk/jyamagis/page3/page58/page58.html)
* This CSTR VCTK Corpus includes speech data uttered by 109 native speakers of English with various accents. Each speaker reads out about 400 sentences, most of which were selected from a newspaper plus the Rainbow Passage and an elicitation paragraph intended to identify the speaker's accent.
* All speech data was recorded using an identical recording setup: an omni-directional head-mounted microphone (DPA 4035), 96kHz sampling frequency at 24 bits and in a hemi-anechoic chamber of the University of Edinburgh.

# Speech To Text
------------------------------------------------------------------------------------------

### [Mozilla Deep Speech](https://github.com/mozilla/DeepSpeech)
* A TensorFlow implementation of Baidu's DeepSpeech architecture

### [CMUSphinx](https://cmusphinx.github.io/)
* Research project from the Carnegie Mellon University
* [Golang library](https://github.com/xlab/pocketsphinx-go)
* [Python library](https://github.com/cmusphinx/pocketsphinx-python)

# Text to Speech
------------------------------------------------------------------------------------------

### [Tacotron](https://github.com/keithito/tacotron)
* Based on a Google published paper published in April 2017, [Tacotron: Towards End-to-End Speech Synthesis](https://arxiv.org/pdf/1703.10135.pdf), where they present a neural text-to-speech model that learns to synthesize speech directly from (text, audio) pairs.
* An implementation of Tacotron speech synthesis in TensorFlow

### [Wavenet](https://en.wikipedia.org/wiki/WaveNet)
* WaveNet is a deep neural network for generating raw audio. It was created by researchers at London-based artificial intelligence firm DeepMind. The technique, outlined in a paper in September 2016,[1] is able to generate more realistic-sounding human-like voices by sampling real human speech and directly modelling waveforms.
* [Keras implementation of Wavenet](https://github.com/basveeling/wavenet)
* [Tensorflow implementation of WaveNet](https://github.com/ibab/tensorflow-wavenet)

# Commercial Services
------------------------------------------------------------------------------------------

Sometimes open source projects either aren't up to par or a service with greater compute resources behind it makes more sense for a project.

### [Lyrebird](https://lyrebird.ai/)
* Free voice cloning service

### [Snowboy Kitt AI](https://snowboy.kitt.ai/)
* [Snowboy Go Wrapper](https://github.com/brentnd/go-snowboy)

### [IBM Watson Speech to Text](https://www.ibm.com/cloud/watson-speech-to-text)
* Free usage tier
* Otherwise $.0125/min
* Requires text to be chunked so you'll need to split it along pauses

### [Amazon Polly](https://aws.amazon.com/polly/)
* Free usage tier
* Something like $0.10/min - Not cheap

### [Youtube](https://www.youtube.com/upload)
* Automatically transcribes speech to text for free!

### [Copsonic](https://www.copsonic.com/)
* Various audio security services. Use with caution.