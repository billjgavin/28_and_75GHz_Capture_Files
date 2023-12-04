Zip file samples_17_03 contains RF Samples recorded on 17/03/2022, Samples include 75GHz captures of BSPK, QPSK, 8PSK and 16QAM modulated data. 3 Samples a,b,c are included for each recorded waveform scenario. Samples of background noise from the lab (All RF sources turned off) in which these signals were recorded are included for SNR calculations. 

Similarly, Zip file IQ_28_Ghz contains RF  samples recorded on 10/02/2022, Samples include 28GHz captures of BSPK, QPSK, 8PSK and 16QAM modulated data. Only one example of each SNR is included. Samples of background noise from the lab (All RF sources turned off) in which these signals were recorded are included for SNR calculations. 

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

IQ Files are captured as follows for 16QAM/8PSK/QPSK/BPSK/CW

Sig gen TX set to PRBS15 with 50Msymbols/s data rate

RX signal sampled by spectrum analyser at 200Msamp/s, 160MHz IF BW, 100us capture frame duration. All data is conducted (not radiated).

-10dBm at sig gen corresponds to -17dBm at spectrum analyser, However CW files are for carrier with no modulation applied - can be used to easily check RX power for each range

Please use N9030B_IQ_file_processor_0_1.m to extract data from each file. 




