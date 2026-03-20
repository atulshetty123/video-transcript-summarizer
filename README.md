# video-transcript-summarizer
This is a project that automates summary of the content in a YouTube video by analyzing the transcript of the video's audio using OpenCV (Python), where I have successfully provided a summarized transcript for this yt video using LexRank algorithm.

[PROJECT LINK] -->[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fxX_3ut4h3ykbcNtgcXX1RvdXHSg4dsz)

In the Video Summarizer (previously mentioned under Educational Qualifications section), I successfully decoupled the core processing logic from the source input (YouTube API, local MP4, or cloud buckets) by implementing a standardized Data Ingestion Interface.So, I will leverage this similar architectural approach by building a provider-independent layer for the FHIR Viewer using fsspec. By treating Google Cloud Storage, AWS S3, and local directories as a unified file-system object, I ensure that the FHIR Parser remains entirely agnostic to the physical location of the data. 

<img width="993" height="994" alt="mermaid-diagram-2026-03-20-155316" src="https://github.com/user-attachments/assets/dbb50800-b7f8-4b30-be7a-7288f4c88071" />
