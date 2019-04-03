# Resource

 - [***Tacotron***](https://google.github.io/tacotron/)
 - [***Wavenet***](https://deepmind.com/blog/wavenet-generative-model-raw-audio/)
 - [***tacotron code***](https://github.com/keithito/tacotron)
 - [***tacotron-2 code***](https://github.com/Rayhane-mamah/Tacotron-2)
 - [***wavenet code***](https://github.com/ibab/tensorflow-wavenet)
 

----------
# TACOTRON: TOWARDS END-TO-END SPEECH SYNTHESIS

> ***A text-to-speech synthesis system typically consists of multiple stages, such as a text analysis frontend, an acoustic model and an audio synthesis module. Building these components often requires extensive domain expertise and may contain brittle design choices. In this paper, we present Tacotron, an end-to-end generative text-to-speech model that synthesizes speech directly from characters. Given <text, audio> pairs, the model can be trained completely from scratch with random initialization. We present several key techniques to make the sequence-to-sequence framework perform well for this challenging task. Tacotron achieves a 3.82 subjective 5-scale mean opinion score on US English, outperforming a production parametric system in terms of naturalness. In addition, since Tacotron generates speech at the frame level, it’s substantially faster than sample-level autoregressive methods.***

![1](https://leanote.com/api/file/getImage?fileId=5ca4d026ab644169fd0039ee)

![2](https://leanote.com/api/file/getImage?fileId=5ca4d059ab64416bfb003823)

----------
# NATURAL TTS SYNTHESIS BY CONDITIONING WAVENET ON MEL SPECTROGRAM PREDICTIONS

> ***This paper describes Tacotron 2, a neural network architecture for speech synthesis directly from text. The system is composed of a recurrent sequence-to-sequence feature prediction network that maps character embeddings to mel-scale spectrograms, followed by a modified WaveNet model acting as a vocoder to synthesize time-domain waveforms from those spectrograms. Our model achieves a mean opinion score (MOS) of 4.53 comparable to a MOS of 4.58 for professionally recorded speech. To validate our design choices, we present ablation studies of key components of our system and evaluate the impact of using mel spectrograms as the conditioning input to WaveNet instead of linguistic, duration, and F0 features. We further show that using this compact acoustic intermediate representation allows for a significant reduction in the size of the WaveNet architecture.***

![3](https://leanote.com/api/file/getImage?fileId=5ca4d392ab64416bfb0038c4)

----------
# WaveNet: A Generative Model for Raw Audio

> ***This paper introduces WaveNet, a deep neural network for generating raw audio waveforms. The model is fully probabilistic and autoregressive, with the predictive distribution for each audio sample conditioned on all previous ones; nonetheless we show that it can be efficiently trained on data with tens of thousands of samples per second of audio. When applied to text-to-speech, it yields state-of-the-art performance, with human listeners rating it as significantly more natural sounding than the best parametric and concatenative systems for both English and Mandarin. A single WaveNet can capture the characteristics of many different speakers with equal fidelity, and can switch between them by conditioning on the speaker identity. When trained to model music, we find that it generates novel and often highly realistic musical fragments. We also show that it can be employed as a discriminative model, returning promising results for phoneme recognition.***

![4](https://leanote.com/api/file/getImage?fileId=5ca4d7a6ab64416bfb003982)
![5](https://leanote.com/api/file/getImage?fileId=5ca4d7e0ab64416bfb00398f)

----------
# Reference

> [***1. Expressive Speech Synthesis with Tacotron --- Google AI Blog***](https://ai.googleblog.com/2018/03/expressive-speech-synthesis-with.html)
[***2. WaveNet: A Generative Model for Raw Audio --- DeepMind Blog***](https://deepmind.com/blog/wavenet-generative-model-raw-audio/)

