# Audio-Modulation-and-Demodulation
This proyect consists in using two NI ELVIS III, each with their own Emona Communications Board for NI ELVIS III, which are comunicating by TCP/IP.
The whole system can be controlled through a NI SystemLink Cloud Dashboard.

The first ELVIS III is uploaded with different songs which can be selected from NI SystemLink Cloud Dashboard. The song will be outputed as a signal 
through the Emona Communications Board. The signal will be modulated using the board's modules, it can be either amplitud modulated or frecuency modulated.
After being modulated the signal would return to the NI ELVIS III and then sends by TCP/IP to the other NI ELVIS III. This second device outputs the
recieved signal to its Emona Communications Board, which will demodulate the signal with its integrated modules, depending on how it was modulated in the 
first place. The demodulated signal will be returned to the NI ELVIS III and could be heard by connecting a speaker to the Communications Board.
