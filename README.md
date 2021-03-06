### CS419_Ins_cla
 CS419 group project Lyric Khare		(20D170022) Pranav Limaye		(20D170028) Shivam Ambokar	(200100145) Sneha Kulkarni		(200100090)
#### Abstract
Music recordings often require remixing to change the dynamics and balance between the different instruments used in them. While listening to a musical piece, we might want to change the loudness of certain instruments, suppress the sound of unwanted notes, alter the mixer settings used for the audio, etc. Such tasks can be achieved by obtaining different sound tracks for every individual instrument  and notes used in the audio. In this project, we will be building and training a neural network model to recognise the different musical instruments being played in an input audio sample. The model will further differentiate the notes played by the instrument and eventually form separate samples for each of the instruments. The applications of this include making customised karaoke tracks, remixing audio files, equaliser presets (based on genre of instruments), etc.
The training set will consist of audio samples of two instruments simultaneously. The input will also consist of annotated pitch and timing of the notes and the instruments in the audio. The datasets to be used are MusicNet (The labels are verified by trained musicians; a labelling error rate of 4% has been estimated) and Google NSynth. Magenta on Tensorflow will be used for training the neural network and for extracting features
#### Files
<sandbox.ipynb> => for reading .wav files, calculating MFCCs, and generating the dataset used in <cs419_code.ipynb>
<cs419_code.ipynb> => various ML and DL algorithms implemented on Google NSynth dataset to train a model to predict the type of instrument played in the new file
<cs419_ppt.pdf> => The presentation containing all the comparative study of all methods in a less technical and understandable way
<cs419_report.pdf> => This pdf contains the comparative study of all methods with full description of mathematics involved
<overlay_sound_code> => Folder has code for generating multi-instrument overlaid sound files and code to detect the instrument being played in them.
