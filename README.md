# VideoOverLORA
This is my repository about a research area that I am very interested actually: How to transmit video over LoraWan. Is it achievable with an extreme narrow bandwidth technology? If it is, how? The video reception is, at least, aceptable?

**1. Definition of Research Questions**
A systematic review starts with well-defined research questions (RQs), not with database searches.

PICOC Framework
Population: IoT networks, WSN, LPWAN, LoRa/LoRaWAN
Intervention: Image or video transmission
Comparison: Classical compression vs. AI-based approaches
Outcome: Visual quality, QoS, energy efficiency
Context: Highly constrained, low-bitrate networks

Example Research Questions
RQ1: What techniques have been proposed for image or video transmission over LoRa/LoRaWAN networks?
RQ2: Which compression and reconstruction strategies are most effective in LPWAN environments?
RQ3: Which QoS and visual quality metrics are commonly used to evaluate these systems?
RQ4: To what extent are AI-based or generative models applied to visual data transmission in LPWAN?

**2. Review Protocol Definition**
The protocol ensures reproducibility and scientific rigor.

2.1 Digital Libraries
Recommended databases:
- IEEE Xplore
- Scopus
- Web of Science
- ACM Digital Library
- (Optional) SpringerLink, ScienceDirect

2.2 Search String Definition
General search string:
("LoRa" OR "LoRaWAN" OR "LPWAN") AND ("image transmission" OR "video transmission" OR "visual data") AND ("compression" OR "encoding" OR "reconstruction" OR "deep learning" OR "neural")

2.3 Inclusion Criteria
- Peer-reviewed journal or conference papers
- Published between 2015 and 2025
- Focus on LPWAN or LoRa-based networks
- Involve transmission of images, video, or visual data
- Present experimental evaluation or performance metrics

2.4 Exclusion Criteria
- Purely theoretical works without validation
- Studies unrelated to LPWAN
- Duplicate publications
- Papers without full-text availability

**3. Study Selection Process (PRISMA)**
- The study selection follows the PRISMA methodology:
- Identification – Database search and duplicate removal
- Screening – Title and abstract review
- Eligibility – Full-text assessment
- Inclusion – Final set of selected studies

All steps and article counts must be documented.

**4. Data Extraction**
A structured spreadsheet should be used to extract data from each study. Recommended Fields
- Authors / Year
- Network type (LoRa, LoRaWAN, NB-IoT, Sigfox)
- Visual data type (image, video, keyframe, event-driven)
- Compression technique
- Use of AI (yes/no)
- Evaluation metrics (PSNR, SSIM, latency, energy, PDR)
- Data rate
- Main contribution
- Limitations

**5. Data Analysis and Synthesis**
Instead of summarizing papers individually, the analysis should identify patterns and trends.
_Analysis Dimensions_
5.1 Transmission strategies:
- Periodic image transmission
- Event-driven visual sensing
- Keyframe-based approaches
5.2 Compression and reconstruction methods:
-JPEG / JPEG2000 at ultra-low bitrates
- Wavelet-based compression
- Autoencoders and deep models
- Generative reconstruction
5.3 Evaluation approaches:
- Network QoS metrics
- Objective visual quality metrics
- Perceptual metrics

**6. Identification of Research Gaps**
This step highlights opportunities for novel contributions. Typical gaps in the literature include:
- Limited use of perceptual quality metrics
- Scarce application of generative AI models
- Lack of source mobility or adaptive camera selection
- Absence of integrated routing, compression, and reconstruction frameworks
- Evaluations restricted to either simulation or hardware only
- These gaps directly motivate the VideoOverLoRa framework.

**7. Typical Structure of an SLR Paper**
1. Introduction
2. Research Methodology
2.1 Research Questions
2.2 Search Strategy
2.3 Inclusion and Exclusion Criteria
2.4 Study Selection Process
3. Results
4. Discussion
5. Research Gaps and Future Directions
6. Conclusion

**9. Linking the SLR to VideoOverLoRa**
The review should conclude by explicitly connecting identified gaps to the proposed framework:

"This systematic review shows that, while several studies address image transmission over LPWAN, few integrate adaptive routing, source mobility, and AI-based visual reconstruction. To bridge these gaps, the VideoOverLoRa framework is proposed."
