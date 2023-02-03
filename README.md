# SALT
Speech as lookup table - Using an updatable list of pre-recorded audio clips to provide speech access to static and semi-static menu systems.

## Types of automated speech
Automated speech can be placed in three categories

### Static speech
Static speech would apply to things like microwave or washine machine controls. From the moment you build the device you know all the phrases it could ever need to say and this can be easily accomodated by a set of pre-recorded audio.

### Semi-static speech
Semi-static speech would apply to devices such as DAB radios. Many of the menu options won't change and the station names will remain fairly stable for a while. As station names change (and move around the spectrum) any static speech system will need updating or it will go out of date. A semi-static system allows for an update mechanism.

### Dynamic speech
A dynamic speech system (screenreaders, voice assistants etc) could need to say anything at any time. This will require a speech synthesiser. 

## Features of SALT
- audio clips are referenced by the text they read out, an audio clip saying 'radio' will be referenced by the string "radio"
- there will be a full set of alphabet audio clips from "a" to "z" so if a clip is missing for a word then the word can be spelled out this may also trigger a 'request' message
- a 'request' mechanism and 'update' mechanism will exist so missing clips can be requested and new audio clips can be downloaded
