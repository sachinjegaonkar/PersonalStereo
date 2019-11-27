[![Android Developer Challenge](https://github.com/sachinjegaonkar/PersonalStereo/blob/master/Android%20Developer%20Challenge.jpeg)](https://github.com/sachinjegaonkar/PersonalStereo)


# Personal Stereo - #AndroidDevChallenge

Digital music become widely available from different media sources like internet radio, digital storage devices, internet music, DLNA sources etc. With vast amount of digital music accessible to the end users, there is a need of developing tools to effectively and efficiently retrieve and manage the music of interest to them. Audio Processing with Machine Learning models is an interesting topic with many potential applications that we can offer to the end users. With that opportunity, we can provide plenty of information alongside to the end user while playing the right music for every moment.

This personal intelligent music information retrieval system provides below features:
* Automatic Audio Classification/Tagging
    1. It pre-processes and extracts the features from the music samples and creates a metadata for the audio(for latter purpose) and then apply the classification algorithm (Machine/Deep Learning) on it to get the result e.g. genre classification, instrument recognition, artist identification, emotion detection, etc.
* Audio Fingerprinting
    1. Determines the digital summary of the audio e.g. tonal analysis (e.g. melody and harmony) and rhythm or tempo analysis (e.g. beat tracking).
* Audio Recommendations
    1. Automatically recommends similar search for audio files to listeners.
    2. The music recommendation engine acts on the user’s past listening history to build customized recommendation lists.
    3. It predicts the listening preferences by using the deep learning models.
* Audio Transcription
    1. Speech Recognition
    2. Lyrics Identification.
* The Other Features
    1. DLNA Playback – Implements the UPnP protocol to allow the device to act as DMC, DMR, DMS, DMP, etc.
    2. Internet Radio Playback – Allows browsing and playback of internet radio stations. Radio stations are categorized based on their Genre, Languages, Countries, etc. 
    3. Additional Music – Allows playback from USB connection and devices like smartphones, computer, etc.
    4. Favorites – List of tracks that user thumbs-up for.
    5. Play Timer – User sets-up the play timer that is triggered with automatic playback of pre-configured tracks initially. Further, it intelligently decides what to play next based on the recommendations.
    6. Content Indexing – Allows users to browse the music content based on their classification - Artists, Albums, Genres, Tracks, Languages, Countries, etc.
    7. Play Queues – Current and Previous Play Queues.


# General Steps to build the Machine Learning models:
  1. Load audio files - Background task
  2. Extract features from audio - Background task
  3. Convert the data to pass it in our deep learning model - Background task
  4. Run a deep learning model and get results - Background task
  5. Use the extracted information to display the content description - Front End task.
