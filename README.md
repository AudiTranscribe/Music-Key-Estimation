# Music-Key-Estimation (ARCHIVED)
Notebooks that help estimate the music key of an audio file.

Models taken from the [KeyCNN Repository](https://github.com/hendriks73/key-cnn).
```
@inproceedings{SchreiberM19_CNNKeyTempo_SMC,
   Title = {Musical Tempo and Key Estimation using Convolutional Neural Networks with Directional Filters},
   Author = {Hendrik Schreiber and Meinard M{\"u}ller},
   Booktitle = {Proceedings of the Sound and Music Computing Conference ({SMC})},
   Pages = {47--54},
   Year = {2019},
   Address = {M{\'a}laga, Spain}
}
```

Slight adaptations to the model processing were made.

### Important Note
This repository does **not** contain the actual music key estimation code for the AudiTranscribe project. This was a pet
project using machine learning to examine possible approaches to music key estimation.

Also, we have archived this repository as it does not help with the main functionality of AudiTranscribe. We have used
the [Krumhansl-Schmuckler Key-Finding Algorithm](http://davidtemperley.com/wp-content/uploads/2015/11/temperley-mp99.pdf)
in favour of this machine-learning based algorithm in the actual application.
