# Notes from Hunter Massey

# Final Summary
### 1. Untitled #1
*	This is an original piece that uses the SineEnv voice.
*	Link to repo: https://github.com/allolib-s23/demo1-huntermassey33
*	To play, run ./run.sh tutorials/synthesis/hm_demo1.cpp and press ‘A’
*	This was the first musical piece I’ve ever written! I chose an arbitrary key, F, and came up with a background chord melody using 5 play_Chord functions. These play 6 notes each because I was using guitar barre chords to write the song. I then created a second melody that plays over the chords using single notes. This was mostly the result of me trying to figure out Allolib and experiment with songwriting for the first time.
### 2. 1979 v1
*	This is a partial transcription of 1979 by The Smashing Pumpkins.
*	Link to repo: https://github.com/allolib-s23/demo1-huntermassey33
*	To play, run ./run.sh tutorials/synthesis/1979.cpp and press ‘A’
*	I wanted start experimenting with the Karplus-Strong plucked string sound to achieve a sort of clean toned rock guitar sound. Thus, the intro to 1979 was the first thing to pop into my head. The start of this song also has a drum loop, so I added one here as well. I also made a new playChord function that takes in a vector of notes instead of creating a new function for each chord.
### 3. Untitled #2
*	This is an original piece that uses multiple instruments.
*	Link to repo: https://github.com/allolib-s23/demo1-huntermassey33
*	To play, run ./run.sh tutorials/synthesis/hm_demo2.cpp and press ‘A’
*	The goal of this piece was to take elements of my previous original and the feedback from my 1979 transcription and use that to create a pop/rock song with drums, bass, and a guitar that uses a chorus effect. I achieved the bass sound using Adam Schmieder's calm chords 1 preset for FM synthesis and changing the parameters to allow for different frequencies. To achieve chorus, I created a function that plays a note and simultaneously plays notes that are slightly out of tune, some above the frequency of the original note and some below. This function takes in a new argument, layers, which changes the intensity of the chorus by increasing the amount of out of tune notes.
### 4. Tremolo Siren
*	This is an original piece that uses multiple instruments.
*	Link to repo: https://github.com/allolib-s23/demo1-huntermassey33
*	To play, run ./run.sh tutorials/synthesis/tremPick_demo.cpp and press ‘A’
*	I originally wanted to be able to simulate a guitar bend/sliding effect, but the plucked string sound doesn’t allow for pitch changes in the middle of a note that was just plucked (maybe this would work better with a saw wave or FM preset). The closest thing I achieved was tremolo picking that could slide between frequencies. This piece is centered around this tremolo function, plus added drums. The function takes in two notes as frequencies as well as the duration of each note. It also takes in a transition duration that determines the speed of the slide.
### 5. 1979 v2
*	This is a more complete transcription of 1979 by The Smashing Pumpkins.
*	Link to repo: https://github.com/allolib-s23/demo1-huntermassey33
*	To play, run ./run.sh tutorials/synthesis/1979_v2.cpp and press ‘A’
*	To improve my previous rendition, I added the second part of the verse with bass, the chorus, and the bridge. In addition, I changed some of the guitar parts to use the chorus effect, and updated other parts to have a slightly improved clean guitar sound. I also played around with the dynamics of the song by experimenting with changing amplitudes. This is also the first time I added visuals for the non-string instruments, which are very simple but weren’t the main focus.		
