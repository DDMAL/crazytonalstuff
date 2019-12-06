# November 29, 2019

Attendees: Finn, Sylvain, Suzuka, Sam, Jacob, Nestor, Yaolong, Tim

> Notes taken by Nestor Napoles Lopez

## Discussion of the chord labeling algorithm on Op.44 No.1 - II.

- Sylvain: The output of the `DH(ML)` seems to be the best
- Yaolong: The ensemble method consists of three algorithms: The NCT + CL(ML) [Non-chord-tones + Chord labeling using machine learning], the DH(ML) [Direct Harmonic Analysis], and the NCT + CL(RB) [Non-chord-tone + Chord labeling using a rule-based system].
- (The discussion on the ouput of the algorithm for the first 13 measures continues)
- Yaolong: Forcing people to write labels for every *salami slice* is probably not a good idea, and very demanding for the annotator, we can, for example, omit slices where the chords are incomplete (2 pitch classes)
- Nestor: What about cases where those 2 pitch classes are in a place where they are *felt* like the chord you are expecting, it would be necessary to have those ones annotated
- Sam: That is given by the syntax, the machine learning model is not quite there yet
- Yaolong: All of the feedback regarding the ouput of the algorithm is great, however, we should also discuss how can we use the output of the model to facilitate our annotations of the Mendelssohn dataset, my hope is that it will save us time compared to starting annotating from scratch
- (Long discussion over whether an `F` chord, as annotated by the ensemble method, is really a double suspension, a dominant ninth, or something else)
- Everybody: For the annotation process, we can put a double exclamation mark to outputs in which the predictions of the ensemble method agree but the root of the chord label is not in the music
- Finn: How about we hear the piece in one ear and sonorize the chord labels of the algorithm in the other ear, then we should be able to spot places where the harmonies don't make any sense
- Everybody: That's a great idea, let's do that!