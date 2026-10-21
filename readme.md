# [Coding]SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme[with MATLAB+python codes]

Personal Blog: https://www.cnblogs.com/EWFrontier  
✿Breaking through the bottleneck of digital airborne computation! The SumComp coding scheme achieves efficient and low-complexity communication and computation integration ✿1. Article title: SumComp: A Digital Airborne Computation Coding Scheme Based on Integer Rings  
2. Abstract: Communication and computation are traditionally considered as independent entities, which can be optimized separately. However, many applications focus more on the functionality of local information rather than the information itself. For such scenarios, utilizing interference in multi-access channels for computation by leveraging digital airborne computation can significantly enhance computational efficiency—the ChannelComp method has proven this. However, the original coding scheme proposed by ChannelComp is generic and does not optimize for specific modulation categories, thus leading to high computational complexity. To address this, this study focuses on a specific digital modulation category (Quadrature Amplitude Modulation QAM and Pulse Amplitude Modulation PAM) for digital airborne computation, proposing a novel coding scheme called SumComp. Additionally, we derive the mean square error (MSE) analysis for the SumComp coding in the calculation of the arithmetic mean function, and establish an upper bound for the average absolute error (MAE) for a class of linear graph functions. Simulation results show that, in noisy multi-access channels, the performance of the SumComp coding outperforms both traditional analog airborne computation and the original coding scheme of ChannelComp in terms of MSE and MAE indicators. Specifically, under low noise conditions, the normalized MSE of the SumComp coding for calculating the arithmetic mean and geometric mean is at least 10 dB higher.  
3. Introduction: The evolution of wireless communications is crucial for achieving ubiquitous Internet of Things (IoT), shifting from human-centric to machine-type communication. The application of machine learning-based IoT in 6G and the continuous growth of IoT devices require handling massive amounts of data. To alleviate this heavy communication burden, airborne computing (AirComp) has emerged, leveraging the waveform superposition characteristic of multi-access channels (MAC) at the network edge to collect and compute data simultaneously.
AirComp is a non-orthogonal wireless communication method that, while optimizing communication rate and network coverage, ensures energy efficiency and data security. Notably, the throughput of AirComp linearly grows with the number of shared MAC devices, offering significant benefits for dense networks. Currently, AirComp is a research hotspot in the wireless field, with potential applications in distributed machine learning, intra-chip communication, and wireless control. However, AirComp is limited to amplitude modulation, hence we recently proposed a new communication computing method called ChannelComp, which allows arbitrary finite functions to be executed on the MAC and employs digital modulation. Its enhanced functionality extends its application beyond the summation operation supported by AirComp alone.
However, due to the generality of ChannelComp, its encoding scheme faces high computational complexity issues. Therefore, this paper significantly improves the encoding scheme of ChannelComp while preserving the inherent low latency and spectral efficiency advantages of both analog AirComp and ChannelComp. This enhancement overcomes the feasibility constraints of analog AirComp and the complexity issues of ChannelComp encoding, ensuring full integration with existing digital communication systems.
IV. Method Overview
1. Core Design Concept: The SumComp encoding scheme is based on integer ring design, aiming to avoid the optimization complexity of modulation design in the air for ChannelComp. This approach focuses on the computation of airborne summation functions, extending to a class of columnar graph functions via pre- and post-encoders. It leverages the integer ring representing a two-dimensional grid to perform summation operations on the MAC.
2. Encoding and Decoding Processes:
✧
Encoding process: First, the node input signal is mapped to quantized values through a preprocessing function, then it is mapped to Gaussian integers by an encoder, followed by mapping to a universal integer ring using an operator, and finally, a finite subset of the universal integer ring is selected as constellation points for transmission. Supports multiple digital modulations including QPSK, multi-level QAM (4/16/64 levels), hexagonal QAM, PAM, etc.
✧  
Decoding process: The receiving end first maps the noisy received signal back to an integer ring through a quantization operator, then converts it into Gaussian integers through an inverse mapping, and finally obtains the estimated target function values through the decoder and post-processing functions.
3. Key Features
Joint source-channel coding: The first time a one-dimensional input signal is mapped to two-dimensional (in-phase and quadrature components) constellation points for function computation.
✧  
Low complexity: No optimization problem needs to be solved, the encoding process provides closed-form solutions, and the complexity of encoders and decoders are approximately equal to (for node count, for modulation order).
✧  
Non-destructive superposition: The assignment of constellation points constitutes a group, avoiding the destructive superposition problem in traditional Gray code modulation.
V. Conclusions The study found that the integration of communication and computation can enhance the encoding process of ChannelComp, but its inherent complexity poses challenges for widespread optimization applications. To address these issues, we propose SumComp coding—an innovative and concise encoding scheme based on integer rings that enables digital modulation. SumComp coding exhibits good compatibility with various digital modulation techniques, such as QAM and PAM. Additionally, we analyzed the Mean Square Error (MSE) in the calculation of the Arithmetic Mean Function and established an upper bound for the Mean Absolute Error (MAE) for various columnar plot functions.
Empirical results confirm that SumComp coding outperforms the traditional AirComp method in the field of digital modulation and airborne computation, achieving significant advancements. Specifically, under low noise scenarios, the normalized MSE for computing the arithmetic mean and geometric mean with SumComp coding is improved by approximately 10 dB compared to the original ChannelComp coding scheme. The introduction of SumComp coding not only overcomes the computational complexity issues of the original ChannelComp coding scheme but also lays the foundation for further exploration in digital wireless computation.
Future research directions include: developing anti-noise SumComp channel coding; expanding the range of functions that can be computed in airborne computation using other ring algebra structures such as polynomial rings and division rings; extending single narrowband antenna systems to MIMO systems to achieve vector-based computation; applying SumComp coding to edge federated learning to enhance performance; and validating the feasibility of SumComp coding in actual wireless communication systems through practical experiments.

## Images

![(Coding)SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme [with MATLAB+Python codes]](01.jpg)
![(Coding)SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme [with MATLAB+Python codes]](02.jpg)
![(Coding)SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme [with MATLAB+Python codes]](03.jpg)
![(Coding)SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme [with MATLAB+Python codes]](04.jpg)
![(Coding)SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme [with MATLAB+Python codes]](05.jpg)
![(Coding)SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme [with MATLAB+Python codes]](06.jpg)
![(Coding)SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme [with MATLAB+Python codes]](07.jpg)
![(Coding)SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme [with MATLAB+Python codes]](08.jpg)
![(Coding)SumComp: Integer Ring-based Digital Aircraft Computation Coding Scheme [with MATLAB+Python codes]](09.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
