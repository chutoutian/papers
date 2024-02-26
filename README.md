Papers I have read and plan to read 

# Multimedia and Networking

## ABR
<details>
  <summary>BOLA: Near-optimal bitrate adaptation for online videos [INFOCOM16]
  </summary>
Modern video players employ complex algorithms to adapt the bitrate of the video that is shown to the user. Bitrate adaptation requires a tradeoff between reducing the probability that the video freezes and enhancing the quality of the video shown to the user. A bitrate that is too high leads to frequent video freezes (i.e., rebuffering), while a bitrate that is too low leads to poor video quality. Video providers segment the video into short chunks and encode each chunk at multiple bitrates. The video player adaptively chooses the bitrate of each chunk that is downloaded, possibly choosing different bitrates for successive chunks. While bitrate adaptation holds the key to a good quality of experience for the user, current video players use ad-hoc algorithms that are poorly understood. We formulate bitrate adaptation as a utility maximization problem and devise an online control algorithm called BOLA that uses Lyapunov optimization techniques to minimize rebuffering and maximize video quality. We prove that BOLA achieves a time-average utility that is within an additive term O(1/V) of the optimal value, for a control parameter V related to the video buffer size. Further, unlike prior work, our algorithm does not require any prediction of available network bandwidth. We empirically validate our algorithm in a simulated network environment using an extensive collection of network traces. We show that our algorithm achieves near-optimal utility and in many cases significantly higher utility than current state-of-the-art algorithms. Our work has immediate impact on real-world video players and BOLA is part of the reference player implementation for the evolving DASH standard for video transmission.
</details>

<details>
  <summary>A buffer-based approach to rate adaptation: evidence from a large video streaming service [SIGCOMM14]
  </summary>
</details>


<details>
  <summary>A control-theoretic approach for dynamic adaptive video streaming over HTTP [SIGCOMM15]
  </summary>
</details>

<details>
  <summary>Neural adaptive video streaming with pensieve [SIGCOMM17]
  </summary>
</details>

<details>
  <summary>Learning in situ: a randomized experiment in video streaming [NSDI20]
  </summary>
</details>

<details>
  <summary>Veritas: Answering causal queries from video streaming traces [SIGCOMM23]
  </summary>
</details>





## Live Streaming/Real-time Communication
<details>
  <summary>Salsify: Low-latency network video through tighter integration between a video codec and a transport protocol [NSDI18]
  </summary>
</details>

<details>
  <summary>Towards optimal low-latency live
video streaming [TON21]
  </summary>
</details>

<details>
  <summary>Converge: QoE-driven multipath video conferencing over WebRTC [SIGCOMM23]
  </summary>
</details>

<details>
  <summary>TwinStar: A practical multi-path transmission framework for
ultra-Low latency video delivery [ACMMM23]
  </summary>
</details>

<details>
  <summary>Achieving consistent low latency for wireless real-time communications with the shortest control loop [SIGCOMM22]
  </summary>
  Real-time communication (RTC) applications like video conferencing or cloud gaming require consistent low latency to provide a seamless interactive experience. However, wireless networks including WiFi and cellular, albeit providing a satisfactory median latency, drastically degrade at the tail due to frequent and substantial wireless bandwidth fluctuations. We observe that the control loop for the sending rate of RTC applications is inflated when congestion happens at the wireless access point (AP), resulting in untimely rate adaption to wireless dynamics. Existing solutions, however, suffer from the inflated control loop and fail to quickly adapt to bandwidth fluctuations. In this paper, we propose Zhuge, a pure wireless AP based solution that reduces the control loop of RTC applications by separating congestion feedback from congested queues. We design a Fortune Teller to precisely estimate per-packet wireless latency upon its arrival at the wireless AP. To make Zhuge deployable at scale, we also design a Feedback Updater that translates the estimated latency to comprehensible feedback messages for various protocols and immediately delivers them back to senders for rate adaption. Trace-driven and real-world evaluation shows that Zhuge reduces the ratio of large tail latency and RTC performance degradation by 17% to 95%.
</details>

## 3D Video
<details>
  <summary>Flare: practical viewport-adaptive 360-degree video
streaming for mobile devices [MOBICOM18]
  </summary>
</details>

<details>
  <summary>Pano: optimizing 360° video streaming with a better understanding of quality perception [SIGCOMM19]
  </summary>
</details>

<details>
  <summary>The prefetch aggressiveness tradeoff in 360° video streaming [MMSys18]
  </summary>
</details>

<details>
  <summary>Dragonfly: higher perceptual quality For continuous 360° video
playback[SIGCOMM23]
  </summary>
</details>

## CDN

<details>
  <summary>Darwin: Flexible learning-based CDN caching [SIGCOMM23]
  </summary>
</details>




# Wireless System and Networking

<details>
  <summary>Networking across boundaries: enabling wireless communication through the water-air interface [SIGCOMM18]
  </summary>
</details>

<details>
  <summary>Underwater backscatter networking [SIGCOMM19]
  </summary>
</details>

<details>
  <summary>Battery-free wireless imaging of underwater
environments [NC21]
  </summary>
</details>

<details>
  <summary>Underwater messaging using mobile devices [SIGCOMM22]
  </summary>
</details>

# Machine Learning and Systems

# Misc

<details>
  <summary>Visage: enabling timely analytics for drone imagery [MOBICOM21]
  </summary>
</details>

<details>
  <summary>Dashlet: taming swipe uncertainty for robust short video streaming [NSDI23]
  </summary>
</details>