Image2SoundVocoder (Personal Project)
==================

Max MSP 6 with CNMAT Externals 

Turns images into music.

Takes an image, extracts pixel RGB data into a matrix. Iterate through the values in a column and scale the data into midi frequencies. Synthesizer built with a recorded audio file, pitch frequency manipulated by external MIDI controller. Options for major, minor, and harmonic minor scales. Utilizes Fast Fourier Transform for the voice decoder. 

Counter object to initiate a custom-made chord progression using saw synth tones. Chords set by manually by type and pitch. Arpeggiator to create an underlying bassline as well as prerecording drum loop to create a one man band type recording. Manipulate the voice recording using the midi Synthesizer controller to play over the backing track, or set the image to play over the backing track

Plan to write more features with the Java max libraries
