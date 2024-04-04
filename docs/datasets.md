# Datasets

- [IEMOCAP](http://sail.usc.edu/iemocap/)
- [CMU-MOSI](http://multicomp.cs.cmu.edu/resources/cmu-mosi-dataset/)
- [Dravidian MultiModality](https://zenodo.org/records/5045061)

### IEMOCAP
The Interactive Emotional Dyadic Motion Capture (IEMOCAP) database is an acted, multimodal and multispeaker database, recently collected at SAIL lab at USC. It contains approximately 12 hours of audiovisual data, including video, speech, motion capture of face, text transcriptions. It consists of dyadic sessions where actors perform improvisations or scripted scenarios, specifically selected to elicit emotional expressions. IEMOCAP database is annotated by multiple annotators into categorical labels, such as anger, happiness, sadness, neutrality, as well as dimensional labels such as valence, activation and dominance. The detailed motion capture information, the interactive setting to elicit authentic emotions, and the size of the database make this corpus a valuable addition to the existing databases in the community for the study and modeling of multimodal and expressive human communication.

The IEMOCAP dataset can be obtained after submitting a formal request [here](https://sail.usc.edu/iemocap/iemocap_release.htm).

### CMU-MOSI
The Multimodal Corpus of Sentiment Intensity (CMU-MOSI) dataset is a collection of 2199 opinion video clips. Each opinion video is annotated with sentiment in the range [-3,3]. The dataset is rigorously annotated with labels for subjectivity, sentiment intensity, per-frame and per-opinion annotated visual features, and per-milliseconds annotated audio features.

The CMU-MOSI dataset is available for download [here](https://drive.google.com/drive/folders/1uEK737LXB9jAlf9kyqRs6B9N6cDncodq).
To get an idea on how to make use of this dataset, you can refer to this link [here](../src/dataset/mosi_explore.ipynb).

More References
- [CMU-MOSI Explore](https://www.kaggle.com/code/neelaryan/cmu-mosi-explore)


### Dravidian MultiModality
It consists of Malayalam and Tamil Videos by popular Youtube movie critics. The dataset is annotated with sentiment in the range [-2,2]. It consists of 70 Audio, Video and Transcript files for Malayalam and 64 for Tamil. 

The Dravidian MultiModality dataset is available for download [here](https://zenodo.org/records/5045061).

Preprocessing steps for this dataset is given below<br> 
- [for audios](../src/dataset/dravidian_audio_mal.ipynb)
- [for transcripts](../src/dataset/dravidian_transcripts_mal.ipynb)
- [for videos](../src/dataset/dravidian_video_mal.ipynb)
