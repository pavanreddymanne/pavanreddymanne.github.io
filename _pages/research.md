---
permalink: /research/
title: "Research"
author_profile: true
---
## Structural MIMO for 6G

<p style="text-align: center;">
  <img src="/files/smimo.jpg" width="600" height="250" alt="Rank Hardware">
</p>

Current 5G MU-MIMO deployments, typically use 64 antenna ports and the base station can serve up to 16 layers, in a paired MU-MIMO group. Although a theoretical 16-fold increase in network capacity can be expected compared to a single-antenna system, practical limitations such as limited antenna directivity per port, interference from other sectors, and power division among scheduled layers restrict the number of users that can be paired and the achievable network capacity. To overcome these limitations, we propose Structural MIMO (S-MIMO), which eliminates the constraints of conventional 5G MIMO systems by implementing the following methods:  
* Highly directional beams associated with each antenna port/panel maximizes the coverage per port/panel.
* Structural arrangements of multiple antenna panels using a three-dimensional structure, enabling full coverage in azimuth and elevation. 
* Joint baseband processing of signals associated with multiple antenna panels, incorporating TDD reciprocity calibration, MU-MIMO precoding/beamforming in the DL, and joint processing of UL signals from multiple antenna panels.   

<u>Acknowledgements</u>: *I was mentoring Spandan Bisoyi, who is pursuing this work as part of his Ph.D. thesis. For more details on our work, please refer to this white paper:*  <a href="https://bharat6galliance.com/bharat6G/public/assets/report/document_28222201.pdf" target="_blank">S-MIMO</a>  
*This work was submitted as a potential technology for IMT-2030 or 6G:* <a href="https://www.itu.int/md/R19-WP5D.AR-C-1265/en" target="_blank">Link</a>


## Enhanced Rank Adaptation for MIMO Systems
<p style="text-align: center;">
  <img src="/files/rank_hw.jpg" width="750" height="250" alt="Rank Hardware">
</p>

<div style="display: flex; align-items: center; justify-content: center; gap: 20px;">

  <!-- Left: Image -->
  <div style="flex: 1; text-align: center;">
    <img src="/files/rank.jpg" width="500" height="225" alt="Rank Simulation" style="border-radius: 8px;">
  </div>

  <!-- Right: Text -->
  <div style="flex: 1; text-align: justify; font-size: 16px;">
    Multiple-input-multiple-output systems enhance the available degrees of freedom, enable spatial multiplexing, and improve network capacity. 
    However, higher-rank transmission becomes advantageous only if it compensates for inter-layer interference, necessitating rank adaptation. 
    Typically, rank adaptation relies on full or partial channel state information or outer loop rank adaptation (OLRA), with the former incurring 
    additional resource overhead, while the existing works on latter often yield sub-optimal performance. Addressing this issue, we have designed 
    an enhanced OLRA (eOLRA) that achieves optimal performance. We have performed extensive system-level simulations and experimental evaluations 
    on a real-time 5G base station to quantify the achievable gains. We demonstrate significant gains in cell-edge throughput and link stability. <i>More details on this work are available at this link:</i> <a href="/files/olra.pdf" target="_blank">OLRA</a>
  </div>

</div>

## Graph Neural Networks-based User Pairing in Wireless Communication Systems
<div style="text-align: center;">
  <img src="/files/gnn2.jpg" width="350" height="250" alt="GNN Graph">
  <img src="/files/gnn.jpg" width="350" height="250" alt="GNN Model">
</div>

Recently, deep neural networks have emerged as a solution to solve NP-hard wireless resource allocation problems in real-time. However, multi-layer perceptron (MLP) and convolutional neural network (CNN) structures, which are inherited from image processing tasks, are not optimized for wireless network problems. As network size increases, these methods get harder to train and generalize. User pairing is one such essential NP-hard optimization problem in wireless communication systems that entails selecting users to be scheduled together while minimizing interference and maximizing throughput. In this paper, we propose an unsupervised graph neural network (GNN) approach to efficiently solve the user pairing problem. Our proposed method utilizes the Erdos goes neural pipeline to significantly outperform other scheduling methods such as k-means and semi-orthogonal user scheduling (SUS). At 20 dB SNR, our proposed approach achieves a 49% better sum rate than k-means and a staggering 95% better sum rate than SUS while consuming minimal time and resources. The scalability of the proposed method is also explored as our model can handle dynamic changes in network size without experiencing a substantial decrease in performance. Moreover, our model can accomplish this without being explicitly trained for larger or smaller networks facilitating a dynamic functionality that cannot be achieved using CNNs or MLPs

## Building Bharat RAN 5G

<p style="text-align: center;">
  <img src="/files/bran.jpg" width="600" height="250" alt="Bharat RAN solution wisig">
</p>

  At WiSig Networks, we developed a trusted, secure, dis-aggregated and standard compliant 5G Bharat RAN solution for Indian market that inter-operates with 5G Core and third-party low-power and high-power radio units. This solution can be adapted for global markets including macro as well as private 5G deployments. Some of the key research and development activities of my team includes following: design, implementation, and on-field evaluation of scheduling algorithms, link and rank adaptation, power control, and multi-user MIMO.


## System-Level Simulator

<div style="display: flex; align-items: center; justify-content: center; gap: 20px;">

  <!-- Left: Image -->
  <div style="flex: 1; text-align: center;">
    <img src="/files/sls.jpg" width="500" height="225" alt="SLS" style="border-radius: 8px;">
  </div>                                                                                                                                                                                                                  <!-- Right: Text -->                                                                                        <div style="flex: 1; text-align: justify; font-size: 16px;"> 


In wireless systems, any new algorithmic enhancements and design proposals have to be evaluated exhaustively before a real-life deployment. This evaluation requires analyzing multiple communication links between a mobile station and devices for varying propagation scenarios. The computational complexity of an individual communication link itself is significantly high. Hence, a comprehensive evaluation at a system-level will have a significant increase in the complexity with an increase in the number of mobile stations and devices. Typically, to address this issue, system-level simulators are used where all the link-features are abstracted. These system-level simulator tools are vital in evaluating network performance and are expected to persist as essential tools with the next-generation cellular systems. <b>Motivated by this and the significant impact of the simulation tools in the standardization process and developing new technologies, we have developed standard-compliant uplink and downlink system-level simulators.</b>  
  
<br>

<u>Key Features</u>: 3-D channel modelling (UMa/UMi/RMa), 3GPP Phase-I and Phase-II calibration, massive MIMO: antenna modelling and scheduler designs, traffic modelling, link & rank adaptation, power control, and all 3GPP mandate features for evaluation, support for reconfigurable intelligent surfaces and non-orthogonal multiple access.  
 <br> 
<u>Acknowledgements</u>: <i>This work includes signficant contributions from Prof. Kiran Kuchi, Dr. SaiDhiraj Amuru, and Harish Kumar D. For more details on our work, please refer to this latest publication </i> <a href="https://ieeexplore.ieee.org/document/10303281" target="_blank">(Link)</a> <i>and my Ph.D. thesis </i> <a href="/files/thesis.pdf" target="_blank">(Link)</a>.

</div>
</div>

## 5G feature using 4G

<div style="display: flex; align-items: center; justify-content: center; gap: 20px;">

<div style="flex: 1; text-align: justify; font-size: 16px;">
  
Beamforming of physical downlink control channel (PDCCH) is introduced in 4G LTE-Advanced and 5G-NR specifications. However, the legacy 4G LTE systems (typically Release-8 systems) which account for most of the existing 4G deployments still cannot perform beamforming on PDCCH. Note that the capacity of the control channel in downlink dictates the number of users that can be scheduled at any time instant, and thus it limits the cell-capacity.  With minimal software changes to the scheduling algorithm,  we have designed a beamforming algorithm that significantly enhances the network capacity. In the proposed design, we use sounding reference signals received in uplink to determine the best beam for a user, and then ingeniously beamform the PDCCH in downlink. Numerical evaluations show that our proposed design significantly outperforms the state-of-the-art algorithms.

<br>
Please refer to our work here:  <a href="https://ieeexplore.ieee.org/document/9027449" target="_blank">(Link)</a>.
<br>


<span style="background-color: #f6ede4; color: #b30000; padding: 3px 6px; border-radius: 5px;">
This work was awarded with <i>Best Paper Honorable Mention</i> at COMSNETS 2020 Conference.
</span>



</div>

<!-- Left: Image -->
  <div style="flex: 1; text-align: center;">
    <img src="/files/bfpdcch.jpg" width="500" height="225" alt="Beamformed PDCCH" style="border-radius: 8px;">
  </div>              

                                                                                                                                                                                                    
</div>





## Reconfigurable Intelligent Surfaces                                                                                                                                                                                        
<p style="text-align: center;">
  <img src="/files/ris.jpg" width="500" height="250" alt="RIS">                                                                                                                           </p> 

Reconfigurable intelligent surface (RIS) is considered a promising technology for the next generation cellular communications to improve the achievable network capacity and cellular coverage. RIS consists of a large number of passive antenna elements (or meta-surfaces) which can reflect the incident ray toward the desired direction. By controlling the impedance of the meta-surfaces through a passive electronic circuit, an additional phase shift is introduced into the reflected signal, and thus, the signal is steered in the desired direction. This way, RIS helps in achieving improved signal reception for the users and also providing coverage to the users who are affected by the signal blockages. We have designed and patented various algorithms for RIS-assisted wireless systems that include selection of users for pairing, power control, optimizing the RIS location in cellular networks, etc.<br>
<i>
Please refer to our key publications on RIS here: Optimizing the RIS location </i> <a href="https://ieeexplore.ieee.org/document/10303281" target="_blank">(Link)</a> <i>and  User pairing in the presence of RIS</i> <a href="https://ieeexplore.ieee.org/document/9881592" target="_blank">(Link)</a>.



## Non-Orthogonal Multiple Access                                                                                                                                                                          
<p style="text-align: center;">
  <img src="/files/noma.jpg" width="400" height="250" alt="NOMA">                                                                                                                           </p>

Non-orthogonal multiple access (NOMA) is considered as a key radio access technique for beyond 5G networks. In NOMA, the users are allocated the same time and frequency resources but are multiplexed across the power domain to achieve multi-fold improvement in the network capacity. At the receiver side of NOMA systems, the successive interference cancellation is employed to decode the transmitted data. However, there are various challenges like user pairing, power allocation, imperfections in SIC, etc. which limit the achievable gains in practice. To address these challenges, we have designed various algorithms such as hybrid NOMA-OMA pairing, joint power allocation and beamforming, etc.
<br>

Please refer to our key publications in this topic here: <a href="https://ieeexplore.ieee.org/document/9881592" target="_blank">IEEE WCL</a>, <a href="https://ieeexplore.ieee.org/document/9861026" target="_blank">IEEE VTC</a>, <a href="https://arxiv.org/abs/2203.15828" target="_blank">(COMSNETS)</a>. 
<br>

<u>Acknowledgements</u>: <i>Some of these publications include the thesis works of M.Tech. students under my supervision.
</i>
