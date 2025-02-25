# -Frequency-Dependent-Crosstalk-Cancellation-XTC-

This study was completed as part of the final project for the 3D Audio course at NYU Steinhardt. 

The study explores the implementation of Frequency Dependent Crosstalk Cancellation (XTC) for spatial audio
using the Matrix Inversion method in Python. A simple non-frequency dependent system is 
implemented. This system is then improved by using frequency dependent regularization both with and 
without branch based regularization. It is observed that the branch based regularization approach 
outperforms both the former approaches by resulting in a more balanced frequency response with 
better attenuation levels. 

Please read the PDF for more details on the methodology and results.

It is difficult to observe the effects of the frequency dependent cross-talk cancellation by listening to the resulting audio (especially when listening on headphones/without stereo loudspeakers). However, it is evident from the frequency response graphs that the branch-based frequency dependent XTC system  shows significantly higher balance in attenuation
across the frequency spectrum as compared to the non-frequency dependent system, and has significantly lower attenuation 
levels (10 to  50 db) as compared to the frequency dependent system without branch-based regularization, outperforming both of them.

The original binaural file that was used to test each XTC system was recorded at Bobst library, NYU,  using the Neumann KU-100 Head. The original binaural audio file as well as the processed audio files after applying each XTC system can be found in this repository. 
