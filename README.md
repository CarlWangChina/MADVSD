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
@inproceedings{10.1145/3746027.3758210,
   author = {Wang, Zihao and Ji, Shulei and Ma, Le and Jin, Yuhang and Lei, Shun and Chen, Jianyi and Fu, Haoying and Dannenberg, Roger B. and Zhang, Kejun},
   title = {Multi-Accent Mandarin Dry-Vocal Singing Dataset: Benchmark for Singing Accent Recognition},
   year = {2025},
   isbn = {9798400720352},
   publisher = {Association for Computing Machinery},
   address = {New York, NY, USA},
   url = {https://doi.org/10.1145/3746027.3758210},
   doi = {10.1145/3746027.3758210},
   booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia},
   pages = {12714–12721},
   numpages = {8},
   keywords = {dry vocals, mandarin singing dataset, regional chinese accents, singing accent recognition},
   location = {Dublin, Ireland},
   series = {MM '25}
}
```

# MADVSD: 多口音普通话干声清唱数据集

**[论文] Multi-Accent Mandarin Dry-Vocal Singing Dataset: Benchmark for Singing Accent Recognition** *Proceedings of the 33rd ACM International Conference on Multimedia (MM '25)*

---

## 🗺️ 区域分布可视化

为了给读者提供直观的参考，我们在本项目仓库中展示了数据集的说话人地理分布图。我们在论文正文中并未包含此图，您可以在下方查看高清版本。该地图通过颜色编码将中国地理划分为九个不同的口音区域，以可视化说话人的分布情况。

![区域口音分布图](Figure_Regional_Distribution.pdf)

> **MADVSD数据集的区域口音分布、说话人统计及录音内容**
>
> * **灰色区域：** 表示由于数据采集限制，本次研究未包含的区域。我们与**某全国性连锁机构**合作设立录音中心，但受限于其**运营网络覆盖范围**，无法覆盖所有省份。未来我们将探索其他策略以补充这些未覆盖区域的数据。
> * **扩展的区域范围（如SGXR）：** 反映了口音类型粒度与每种类型说话人代表性之间的平衡，旨在优化模型训练效果。虽然我们的录音覆盖了每个省/市，但在划定口音区域时，我们优先考虑确保每个类别有足够的说话人数量，同时将口音类型保持在可管理的数量（10个以内），以便于口音识别任务。因此，说话人密集的东部沿海地区被划分为地理范围较小的口音区，而说话人较少的中西部地区则对应较大的地理范围。随着未来数据的丰富，我们将进一步细化口音类型和区域的划分。

---

## 📖 简介

相比于语音口音研究，歌唱口音的研究尚处于起步阶段，主要原因是缺乏合适的数据集。现有的歌唱数据集往往因伴奏分离过程导致细节丢失，且通常缺乏区域口音的标注。

为此，我们推出了 **MADVSD**（多口音普通话干声清唱数据集）。该数据集包含来自中国九个不同区域的 **4,206名** 母语为普通话的说话人录制的超过 **670小时** 的干声清唱录音。

### 主要特点
* **规模：** 12,618 首完整的无伴奏清唱歌曲。
* **内容：** 每位参与者用家乡口音录制了三首流行歌曲，以及涵盖所有普通话元音和全八度音阶的语音练习。
* **群体：** 4,206 名参与者，覆盖广泛的地理区域。
* **质量：** 在安静环境下录制的干声，并经过降噪和去混响处理。

---

## 📂 仓库文件结构与资源

除了数据集介绍外，我们在本仓库中还提供了以下文件，帮助研究人员了解我们的数据采集标准：

* **`Protocol_Phonetic_Exercises_EN.docx` / `_CN.docx`**：发放给参与者的标准化“元音与音阶”录音指导手册（含中英文版）。
* **`Recording_Guidelines_and_Standards.docx`**：员工录音素材的详细技术要求与演唱内容标准。
* **`samples/`**：包含音频样本的文件夹。
* **`Figure_Regional_Distribution.pdf`**：区域分布地图的高清矢量版。

---

## 🔒 数据可用性与隐私声明

### 当前开放状态
出于对用户隐私和道德伦理的考量，**MADVSD 完整数据集目前暂不提供公开下载。**

### 隐私保护与伦理考量
虽然我们致力于推动人工智能社区的开源与分享，但我们必须在开放研究与受试者的人权责任之间取得平衡。MADVSD 的原始音频包含**无法完全脱敏的个人身份信息 (PII)**。具体而言，录音中包含每位参与者自述的真实姓名和具体家乡位置。

公开这些数据存在显著的风险：
1.  **隐私泄露：** 用户的声纹特征与姓名、位置信息的结合属于高度敏感数据。
2.  **滥用风险：** 这些数据极易被用于训练深度伪造（Deepfake）模型，进而可能被用于 AI 电信诈骗或其他犯罪活动。

目前，我们正在处理相关的音色授权合同与法律合规审查。请耐心等待，我们会在确保安全的前提下探索未来的开放形式。

### 样本与验证
为了证明数据集的质量和真实性，我们提供了以下内容：

1.  **音频样本：** `samples/` 文件夹中包含来自 **2位代表性说话人**（一位河南男性，一位北京女性）的共 **4个音频文件**。样本包含歌曲清唱和音阶练习两种类型。
2.  **数据规模概览：** 下图展示了存储在私有云端的数据集完整目录结构截图（已对敏感信息打码），以证明数据规模的真实性。

![数据集文件结构截图](figures/drive_snapshot.png)

### 相关推荐
* **歌唱评价研究：** 如果您正在从事歌唱评分或相关工作，欢迎参考我们的另一个开源项目：[**QwenFeat-Vocal-Score**](https://github.com/CarlWangChina/QwenFeat-Vocal-Score)。
* **其他歌唱数据：** 对于开源的歌唱资源，请关注我们的姐妹项目 **VocalVerse**。

---

## 📝 引用

如果您在研究中使用了本作品或参考了其中的概念，请引用我们的论文：

**ACM Reference Format:**
> Zihao Wang, Shulei Ji, Le Ma, Yuhang Jin, Shun Lei, Jianyi Chen, Haoying Fu, Roger B. Dannenberg, and Kejun Zhang. 2025. Multi-Accent Mandarin Dry-Vocal Singing Dataset: Benchmark for Singing Accent Recognition. In *Proceedings of the 33rd ACM International Conference on Multimedia (MM '25)*. Association for Computing Machinery, New York, NY, USA, 12714–12721. [https://doi.org/10.1145/3746027.3758210](https://doi.org/10.1145/3746027.3758210).

**BibTeX:**

```bibtex
@inproceedings{10.1145/3746027.3758210,
   author = {Wang, Zihao and Ji, Shulei and Ma, Le and Jin, Yuhang and Lei, Shun and Chen, Jianyi and Fu, Haoying and Dannenberg, Roger B. and Zhang, Kejun},
   title = {Multi-Accent Mandarin Dry-Vocal Singing Dataset: Benchmark for Singing Accent Recognition},
   year = {2025},
   isbn = {9798400720352},
   publisher = {Association for Computing Machinery},
   address = {New York, NY, USA},
   url = {https://doi.org/10.1145/3746027.3758210},
   doi = {10.1145/3746027.3758210},
   booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia},
   pages = {12714–12721},
   numpages = {8},
   keywords = {dry vocals, mandarin singing dataset, regional chinese accents, singing accent recognition},
   location = {Dublin, Ireland},
   series = {MM '25}
}
```
