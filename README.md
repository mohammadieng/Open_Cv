# Open_Cv
What I Learned from OpenCV

Simple_Satellite_Image_Ehance.ipynb:

How it works:
+ Converts frames to grayscale for intensity-focused optimization.
+ Applies CLAHE to improve local contrast while mitigating noise amplification.
+ Blends the result with a Gaussian blur via weighted addition (addWeighted) to extract and emphasize high-frequency edge details.
+ Processes video streams in real-time with a side-by-side preview of original vs. enhanced output.
