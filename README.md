# video-transcript-summarizer
This is a project that automates summary of the content in a YouTube video by analyzing the transcript of the video's
audio using OpenCV (Python), where I have successfully provided a summarized transcript for the yt video by handling the Token Limit of the LLM by recursively breaking down a 2-hour transcript into semantic chunks.

[PROJECT LINK] -->[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fxX_3ut4h3ykbcNtgcXX1RvdXHSg4dsz)

In the Video Summarizer (previously mentioned under Educational Qualifications section), I successfully decoupled the core processing logic from the source input (YouTube API, local MP4, or cloud buckets) by implementing a standardized Data Ingestion Interface.So, I will leverage this similar architectural approach by building a provider-independent layer for the FHIR Viewer using fsspec. By treating Google Cloud Storage, AWS S3, and local directories as a unified file-system object, I ensure that the FHIR Parser remains entirely agnostic to the physical location of the data. 

<img width="1533" height="2097" alt="mermaid-diagram-2026-03-20-161005" src="https://github.com/user-attachments/assets/390f5fa9-a43e-467f-98ad-b484ec74e980" />

