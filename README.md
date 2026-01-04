# MADVSD: Multi-Accent Mandarin Dry-Vocal Singing Dataset

**[Paper] Multi-Accent Mandarin Dry-Vocal Singing Dataset: Benchmark for Singing Accent Recognition** *Proceedings of the 33rd ACM International Conference on Multimedia (MM '25)*

[![arXiv](https://img.shields.io/badge/arXiv-2512.07005-b31b1b.svg)](https://www.arxiv.org/abs/2512.07005)
[![ACM DL](https://img.shields.io/badge/ACM%20DL-10.1145%2F3746027.3758210-blue)](https://dl.acm.org/doi/10.1145/3746027.3758210)

---

## 🗺️ Regional Distribution Visualization

For readers interested in a visual reference regarding the dataset's geographical coverage, we provide the high-resolution visualization of the speaker distribution below. This map color-codes the geography into nine distinct regions to visualize the speaker distribution across China.

![Regional Accent Distribution](Figure_Regional_Distribution.pdf)
*(Note: Please ensure the image file is converted to an image format like PNG/JPG for display if PDF rendering is not supported by your markdown viewer)*

> **Regional Accent Distribution, Speaker Demographics, and Recording Content of the MADVSD Dataset.**
>
> * **Gray Areas:** Indicate regions not included in this study due to limitations in data collection. Collaboration with our **nationwide partner** was constrained by their **operational network coverage**, hindering data acquisition from all provinces. Future endeavors will explore alternative strategies to incorporate data from these uncovered regions.
> * **Extended Regional Scope (e.g., SGXR):** Reflects a balance between accent type granularity and speaker representation per type, optimized for model training efficacy. While recordings spanned every province/city, accent region demarcation prioritized sufficient speaker counts per category while maintaining a manageable number of accent types (under ten) for the accent identification task. Consequently, geographically smaller accent regions are defined in eastern coastal areas with a higher speaker count, whereas larger regions correspond to the central and western areas with a lower speaker count. Future data enrichment is expected to facilitate a more refined and geographically precise categorization of accent types and regions.

---

## 📖 Introduction

Singing accent research is underexplored compared to speech accent studies, primarily due to the scarcity of suitable datasets. Existing singing datasets often suffer from detail loss (resulting from vocal-instrumental separation) or lack regional accent annotations.

To address this, we introduce **MADVSD** (Multi-Accent Mandarin Dry-Vocal Singing Dataset). MADVSD comprises over **670 hours** of dry vocal recordings from **4,206 native Mandarin speakers** across nine distinct Chinese regions.

### Key Features
* **Scale:** 12,618 full-length a cappella song performances.
* **Content:** Each participant recorded audio of three popular songs in their native accent, plus phonetic exercises covering all Mandarin vowels and a full octave range.
* **Demographics:** 4,206 participants from diverse regions (SZR, JR, SSHR, BMLR, SGXR, FR, HHAR, GGR, YGSR).
* **Quality:** Dry vocals recorded in quiet environments, processed for noise reduction and dereverberation.

---

## 📂 Repository Structure & Resources

In addition to the dataset information, we provide the following resources in this repository to assist researchers in understanding our data collection protocols:

* **`Protocol_Phonetic_Exercises_EN.docx` / `_CN.docx`**: The standardized instructions given to participants for the phonetic vowel and scale exercises (available in English and Chinese).
* **`Recording_Guidelines_and_Standards.docx`**: The detailed technical requirements and content standards provided to the participants to ensure recording quality.
* **`samples/`**: A folder containing sample audio files.
* **`Figure_Regional_Distribution.pdf`**: The high-resolution vector version of the regional distribution map.

---

## 🔒 Data Availability & Privacy Statement

### Current Access Status
Due to stringent privacy and ethical considerations, **the full MADVSD dataset is not currently open for public download.**

### Ethical Context
While we are strong advocates for open science and community sharing, we must balance research advancement with the protection of human subjects. The MADVSD raw audio contains **non-redactable Personally Identifiable Information (PII)**. Specifically, participants state their real names and specific hometowns within the recordings.

Releasing this data publicly poses significant risks, including:
1.  **Privacy Violation:** The combination of voice biometrics, names, and location data is sensitive.
2.  **Potential for Misuse:** High-quality voice data paired with identity verification can be exploited for malicious purposes, such as deepfakes or telecommunications fraud.

We are currently undergoing legal review to explore licensing frameworks that might allow for controlled access in the future. We appreciate your patience and understanding as we prioritize the safety and rights of our participants.

### Samples and Verification
To demonstrate the quality and existence of the dataset, we have provided:

1.  **Sample Audio:** A small set of 4 audio files from **2 representative speakers** (one Male from Henan, one Female from Beijing) can be found in the `samples/` folder. These include both song performances and phonetic exercises.
2.  **Dataset Structure:** Below is a screenshot of the full dataset directory (hosted on private storage), demonstrating the scale of the data collected.

![Dataset Structure Snapshot](figures/drive_snapshot.png)
*(Screenshot of the file directory, with PII blurred)*

### Recommended Alternatives
* **For Singing Evaluation:** If you are working on singing voice assessment or related tasks, we recommend checking our related project: [**QwenFeat-Vocal-Score**](https://github.com/CarlWangChina/QwenFeat-Vocal-Score).
* **For Other Singing Data:** Please refer to our sister project **VocalVerse** (details forthcoming) for open-source singing resources.

---

## 📝 Citation

If you reference this work or the concepts presented, please cite our paper:

**ACM Reference Format:**
> Zihao Wang, Shulei Ji, Le Ma, Yuhang Jin, Shun Lei, Jianyi Chen, Haoying Fu, Roger B. Dannenberg, and Kejun Zhang. 2025. Multi-Accent Mandarin Dry-Vocal Singing Dataset: Benchmark for Singing Accent Recognition. In *Proceedings of the 33rd ACM International Conference on Multimedia (MM '25)*. Association for Computing Machinery, New York, NY, USA, 12714–12721. https://doi.org/10.1145/3746027.3758210.

**BibTeX:**

```bibtex
@inproceedings{Wang_2025,
   series={MM ’25},
   title={Multi-Accent Mandarin Dry-Vocal Singing Dataset: Benchmark for Singing Accent Recognition},
   url={[http://dx.doi.org/10.1145/3746027.3758210](http://dx.doi.org/10.1145/3746027.3758210)},
   DOI={10.1145/3746027.3758210},
   booktitle={Proceedings of the 33rd ACM International Conference on Multimedia},
   publisher={ACM},
   author={Wang, Zihao and Ji, Shulei and Ma, Le and Jin, Yuhang and Lei, Shun and Chen, Jianyi and Fu, Haoying and Dannenberg, Roger B. and Zhang, Kejun},
   year={2025},
   month=oct,
   pages={12714–12721},
   collection={MM ’25}
}

@inproceedings{10.1145/3746027.3758210,
   author = {Wang, Zihao and Ji, Shulei and Ma, Le and Jin, Yuhang and Lei, Shun and Chen, Jianyi and Fu, Haoying and Dannenberg, Roger B. and Zhang, Kejun},
   title = {Multi-Accent Mandarin Dry-Vocal Singing Dataset: Benchmark for Singing Accent Recognition},
   year = {2025},
   isbn = {9798400720352},
   publisher = {Association for Computing Machinery},
   address = {New York, NY, USA},
   url = {[https://doi.org/10.1145/3746027.3758210](https://doi.org/10.1145/3746027.3758210)},
   doi = {10.1145/3746027.3758210},
   booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia},
   pages = {12714–12721},
   numpages = {8},
   keywords = {dry vocals, mandarin singing dataset, regional chinese accents, singing accent recognition},
   location = {Dublin, Ireland},
   series = {MM '25}
}
```
