# LDPC Code Simulation for 5G NR

This project implements and analyzes Low-Density Parity-Check (LDPC) codes as specified in the 5G New Radio (NR) standard. It explores encoding, rate matching, modulation, and decoding over AWGN channels using simulation.

## Technologies Used
- MATLAB
- LDPC (Base Graph 1 and 2)
- BPSK Modulation
- AWGN Channel Modeling

## Features
- Implementation of LDPC encoding using structured base graphs and expansion techniques
- Rate matching using puncturing to achieve target code rates (⅓, ½, ⅗, ⅘)
- BPSK modulation and AWGN channel simulation
- Hard Decision, Min-Sum, and Sum-Product decoding algorithms
- BER performance evaluation under different SNR conditions

## Summary
LDPC codes were simulated under various code rates and decoding techniques. Sum-Product decoding showed near-optimal performance compared to Min-Sum and Hard Decision decoding. The study validates LDPC’s effectiveness for reliable communication in 5G NR systems.
