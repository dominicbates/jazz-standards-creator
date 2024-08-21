# jazz-standards-creator

### Summary

Preliminary testing of training an LSTM to create jazz chord progressions. Code is not productionised or cleaned up, but repo is set to public in case of interest to anyone. 

Generated chord progressions are sensible and the model clearly understands jazz harmony, however it is not so great at structure over long timescales (and often doesn't return back to the original progression, e.g. produces AABCDE... rather than AABA). 

Repository structure:

    README.md
    data/

### Training data

- Data obtained from this paper:

https://archives.ismir.net/ismir2018/paper/000206.pdf

- URL of data:

https://www.musiccognition.osu.edu/resources/



