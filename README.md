# Urban_Noise_Detection

YAMNet is a pre-trained deep neural network that can predict audio events from 521 classes, such as laughter, barking, or a siren.
YAMNet is a pre-trained neural network that employs the MobileNetV1 depthwise-separable convolution architecture. It can use an audio waveform as input and make independent predictions for each of the 521 audio events from the AudioSet corpus.
Internally, the model extracts "frames" from the audio signal and processes batches of these frames. This version of the model uses frames that are 0.96 second long and extracts one frame every 0.48 seconds .

Dataset:

The ESC-50 dataset (Piczak, 2015) is a labeled collection of 2,000 five-second long environmental audio recordings. The dataset consists of 50 classes, with 40 examples per class.
