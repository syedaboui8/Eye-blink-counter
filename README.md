This projects presents an innovative approach to implementing a live eye blink counter utilizing a Face Mesh Detector. The system operates by continuously 
capturing video feed from a camera source and processing it using computer vision algorithms. Specifically, the Face Mesh Detector, powered by libraries 
like OpenCV and MediaPipe, is employed to detect and track facial landmarks, including those corresponding to the eyes. By analyzing the spatial arrangement 
of these landmarks, the system calculates the height to width ratio of the eyes, a crucial metric for identifying blinking patterns. Moreover, the eye blink 
counter is activated when the computed height to width ratio falls below a predefined threshold. This activation serves as an indicator of eye closure, signifying 
a blink event. Such functionality can be invaluable in various applications, ranging from driver fatigue detection systems to human-computer interaction interfaces.
Through the integration of real-time facial landmark detection and intelligent threshold-based analysis, this eye blink counter offers a versatile and efficient solution 
for monitoring eye movements. The subsequent sections will delve into the technical implementation of the system, highlighting key components and algorithms employed to 
achieve accurate and reliable blink detection in diverse scenarios. Additionally, practical considerations, challenges, and potential applications of the proposed system 
will be discussed to provide comprehensive insights into its functionality and significance in contemporary computer vision research and applications.
