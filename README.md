# KIFT

## About

Voice control system in C using Carnegie Mellon University Sphinx (CMUSphinx). PocketSphinx/Sphinx use three models - an acoustic model, a language model and a phonetic dictionary. As I understand them, the acoustic model converts audio samples into phonemes(?), the language model contains probabilities of sequences of words, and the phonetic dictionary is a mapping of words to phonemes.

In the

## Required Modules

- `brew install sox`
- `brew reinstall swig`

## Dependencies

- [node-record-lpcm16](https://github.com/gillesdemey/node-record-lpcm16)
- [Electron](https://github.com/electron/electron)
- [CMake-js](https://github.com/cmake-js/cmake-js)

## Tools

* [PocketSphinx API Documentation](https://cmusphinx.github.io/doc/pocketsphinx/index.html#intro_sec)
* [Sphinx Knowledge Base Tool](http://www.speech.cs.cmu.edu/tools/lmtool-new.html)
* [English (United States) model](https://sourceforge.net/projects/cmusphinx/files/Acoustic%20and%20Language%20Models/)

## Authors

- [Adam Syed](https://github.com/suedadam)
- [Bassirou Rabo Hima](https://github.com/brabo-hi)
- [Phillipe Assef](https://github.com/philasf)
- [Zeid Tisnes](https://github.com/zedin27)

## Resources
* [Understanding phonetic symbols](http://www.ling.upenn.edu/courses/Fall_2014/ling115/phonetics.html)
* [modeldir stuff](https://cmusphinx.github.io/wiki/tutorialpocketsphinx/)
* [train acoustic model](https://cmusphinx.github.io/wiki/tutorialam/)


## License
