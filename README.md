# Semantic Reliability Decoding for Short Block Codes Transmission

📋 Overview
This repository contains the implementation of a novel semantic-enhanced receiver framework for transmitting natural language sentences over noisy wireless channels using multiple short block codes. Our approach leverages large language models (BART) to perform semantic error correction, achieving significant performance gains over conventional channel coding schemes.
Key Features

Semantic Error Correction (SEC): Reconstructs corrupted segments using language model context
Semantic List Decoding (SLD): Generates multiple candidate reconstructions and selects the best one via weighted Hamming distance
Semantic Confidence-guided HARQ (SHARQ): Eliminates CRC overhead using confidence-based error detection

Main Results

~0.5 dB BLER gain with SEC over PPV-approaching short codes
~1 dB BLER gain with SLD over baseline
Up to 90% latency reduction compared to long LDPC codes while maintaining comparable BLER
Near-perfect semantic fidelity (BLEU > 93, ROUGE-L > 97)
