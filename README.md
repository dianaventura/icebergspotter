# Detecting Antarctic Icebergs with K-Means
This is my mini exploration into the world of satellite imagery, and polar science.

## What I Did

- **Loaded a real satellite image** of the Antarctic region to see icebergs and sea ice from above.
- **Used K-Means clustering** (an unsupervised machine learning algorithm) to automatically segment the image into different regions based on brightness.
- **Assume the brightest areas are icebergs** (ice reflects more radar energy in SAR images).
- **Applied morphological filtering** to clean up the detection, removing noise and highlighting actual iceberg shapes.
- **Visualized the results** by overlaying the detected icebergs in red on the original image.

## Why I Did It

I wanted to see if I could use simple, accessible tools to mimic the kind of iceberg detection that real polar scientists do.  
This project let me explore:
- How unsupervised learning can find patterns in real-world data
- Why SAR images are so powerful for polar research
- The challenges of distinguishing icebergs from sea ice and ocean

## What I Learned

- **K-Means clustering** is a surprisingly effective way to segment satellite images, even with minimal data.
- **Image preprocessing** (like resizing and grayscale conversion) is crucial for efficient analysis.
- **Post-processing** helps turn raw machine learning output into meaningful scientific results.
- There’s a lot more to learn, but even a small project can open the door to big questions about our planet!

---

## References

- [Scalable automated detection and tracking of icebergs in the Southern Ocean – British Antarctic Survey](https://www.bas.ac.uk/project/scalable-automated-detection-and-tracking-of-icebergs-in-the-southern-ocean/)[1]
- [Using AI to track icebergs – British Antarctic Survey News](https://www.bas.ac.uk/media-post/using-ai-to-track-icebergs/)[2]
