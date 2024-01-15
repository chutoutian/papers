# papers
papers I have read and plan to read
## ABR
<details open>
  <summary>BOLA: Near-optimal bitrate adaptation for online videos [INFOCOM16]
  </summary>
  Modern video players employ complex algorithms to adapt the bitrate of the video that is shown to the user. Bitrate adaptation requires a tradeoff between reducing the probability that the video freezes and enhancing the quality of the video shown to the user. A bitrate that is too high leads to frequent video freezes (i.e., rebuffering), while a bitrate that is too low leads to poor video quality. Video providers segment the video into short chunks and encode each chunk at multiple bitrates. The video player adaptively chooses the bitrate of each chunk that is downloaded, possibly choosing different bitrates for successive chunks. While bitrate adaptation holds the key to a good quality of experience for the user, current video players use ad-hoc algorithms that are poorly understood. We formulate bitrate adaptation as a utility maximization problem and devise an online control algorithm called BOLA that uses Lyapunov optimization techniques to minimize rebuffering and maximize video quality. We prove that BOLA achieves a time-average utility that is within an additive term O(1/V) of the optimal value, for a control parameter V related to the video buffer size. Further, unlike prior work, our algorithm does not require any prediction of available network bandwidth. We empirically validate our algorithm in a simulated network environment using an extensive collection of network traces. We show that our algorithm achieves near-optimal utility and in many cases significantly higher utility than current state-of-the-art algorithms. Our work has immediate impact on real-world video players and BOLA is part of the reference player implementation for the evolving DASH standard for video transmission.
  
</details>


## 3D video