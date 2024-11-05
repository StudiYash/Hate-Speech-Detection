# ![DweshaMukt](https://github.com/StudiYash/DweshaMukt/blob/main/DweshaMukt%20Logo.png)

## 1. Project Introduction 🛡️

### Abstract 📄
In today’s digital landscape, hate speech is an escalating concern, often fueling division and unrest across communities. DweshaMukt is an **Advanced Multilingual and Multimodal Hate Speech Detection System** designed to counteract this issue by harnessing the power of **Bidirectional Encoder Representations from Transformers (BERT)** alongside cutting-edge **Deep Learning** and **Natural Language Processing (NLP)** techniques.

Our system tackles a unique challenge: detecting hate speech within **Hinglish**—a dynamic blend of Hindi and English—while also supporting **Hindi** and **English** languages individually. DweshaMukt leverages a pre-trained BERT model, specially optimized for real-time scenarios, offering robust analysis across a range of media. Its **multilingual and multimodal architecture** enables hate speech detection across diverse content types: **text**, **audio**, **video**, **images**, **GIFs**, and **YouTube comments**.

With an accuracy of **88%**, DweshaMukt stands as a promising solution for real-world hate speech detection applications, bridging language and media barriers to ensure safer, more inclusive online spaces.

**Index Terms:** Hate Speech Detection, BERT, Deep Learning, Natural Language Processing, Multilingual, Multimodal, Hinglish, Real-Time Analysis

---

### Project Timeline 📅

- **Start Date**: 15th February 2023
- **End Date**: 20th October 2024
- **Total Time Required**: 1 Year, 8 Months, and 5 Days

---

### Team Members 👥

| Team Members                   | GitHub Profile | LinkedIn Profile |
|--------------------------------|----------------|------------------|
| **Yash Suhas Shukla**          | [GitHub](https://github.com/StudiYash) | [LinkedIn](https://www.linkedin.com/in/yash-shukla-2024aiguy/) |
| **Tanmay Dnyaneshwar Nigade**   | [GitHub](#) | [LinkedIn](https://www.linkedin.com/in/tanmay-nigade-0ba002230/) |
| **Suyash Vikas Khodade**        | [GitHub](#) | [LinkedIn](https://www.linkedin.com/in/suyash-khodade/) |
| **Prathamesh Dilip Pimpalkar**  | [GitHub](#) | [LinkedIn](https://www.linkedin.com/in/prathamesh-pimpalkar-5a9545204/) |

### Project Guide 🎓

| Guide                           | GitHub Profile | LinkedIn Profile |
|---------------------------------|----------------|------------------|
| **Prof. Rajkumar Panchal**       | [GitHub](#) | [LinkedIn](#) |

---

## 2. Backend Preparation 🔧

### Mark Models Index

The backend development was an intricate journey, involving months of rigorous research, experimentation, and iterative coding. Each phase contributed to refining the system’s ability to detect hate speech across various input types and languages. 

Our **Mark Model Index Document** provides a comprehensive overview of this journey, showcasing each model’s evolution, from early concepts to the final optimized versions. Dive into the document to see how each model was crafted, tested, and fine-tuned to tackle the challenges of multilingual, multimodal hate speech detection.

[![Read the Full Mark Model Index Document](https://img.shields.io/badge/View-Mark%20Model%20Index%20Document-blue?style=for-the-badge)](https://github.com/StudiYash/DweshaMukt/blob/main/Mark%20Model%20Index.pdf)

---

## 3. Backend Explanation 🖥️

The backend architecture of DweshaMukt enables the system to classify various forms of input **text, audio, video, images, GIFs, and live YouTube comments** by first converting each to text before applying the hate speech detection model. Here are the main scenarios handled by the system:

1. **Text Input**: Processes user-entered text directly.
2. **Audio Input**: Converts audio to text using `Google Speech to Text API`, then classifies it.
3. **Image Input**: Extracts text from images via `Google Cloud Vision API`.
4. **GIF Input**: Analyzes GIFs using `Google Video Intelligence API` for text extraction.
5. **Video Input**: Extracts audio from videos, transcribes it, and classifies it.
6. **Live YouTube Video**: Fetches live comments using `pytchat` library, then classifies them.

The combined code integrates all these scenarios into a unified detection system, including added emoticon-based classification for enhanced accuracy.

---

## 4. Project Dataset 📊

### Mark 12 Saved Model 3 Dataset Details
- **Datasets Used**: CONSTRAINT 2021 and Hindi Hate Speech Detection (HHSD)
- **Total Comments**: 22,977
  - **Hate**: 9,705 comments
  - **Non-Hate**: 13,272 comments

![Dataset Graph](https://github.com/StudiYash/DweshaMukt/blob/main/Dataset%20Details.png)  
[](https://forms.gle/RHNkoFQx4W94tXN37)

[![Dataset Requesting Google Form](https://img.shields.io/badge/Fill-Dataset%20Requesting%20Google%20Form-purple?style=for-the-badge)](https://forms.gle/RHNkoFQx4W94tXN37)

---