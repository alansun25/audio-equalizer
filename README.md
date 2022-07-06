# Audio EQ and Spectrum Analyzer

*insert screenshot here*

# Features
tbd

# Challenges/Bugs Along the Way
- When initially adding parameters to the processor, ran into a failed assertion related to building the Audio Unit (AU) version of the plugin. Found that the issue was related to [version hints](https://docs.juce.com/master/classAudioProcessorParameter.html#a843462756ec916e5ba137677f30010e5). **Solution:** Added explicit version hints to parameter IDs.

# Acknowledgements
[MatKat Music](https://www.youtube.com/matkatmusic)
