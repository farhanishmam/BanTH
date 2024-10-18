# BanTH: A Multi-label Hate Speech Detection Dataset for Transliterated Bangla

[![arXiv](https://img.shields.io/badge/arXiv-2410.13281-b31b1b.svg?logo=arxiv)](https://arxiv.org/abs/2410.13281)
[![paper](https://img.shields.io/badge/Paper_Status-In--Review-yellow)](https://arxiv.org/abs/2410.13281)
[![arXiv](https://img.shields.io/badge/Code-farhanishmam/BanTH-blue?logo=GitHub)](https://github.com/farhanishmam/BanTH)

[Fabiha Haider](https://github.com/FabihaHaider),
[Fariha Tanjim Shifat](https://github.com/fariha6412),
[Md Farhan Ishmam](https://farhanishmam.github.io/),
[Deeparghya Dutta Barua*](https://github.com/arg274), 
[Md Sakib Ul Rahman Sourove*](https://github.com/souroveskb), 
[Md Fahim*](https://github.com/md-fahim/), and
[Farhad Alam Bhuiyan](https://github.com/pdfarhad).

---

BanTH is a multi-labeled hate speech dataset comprising 37.3k transliterated Bangla samples. We establish several baselines including further pre-trained encoders and novel prompting strategies on Large Language Models (LLMs).

## Data Format

| **Column Title**             | **Description**                                  |
|----------------------------|------------------------------------------------|
| `text_id`                  | Unique identifier for each text entry.         |
| `text_content`             | The actual transliterated Bangla text.        |
| `hate label`               | Indicates whether the text contains hate speech (Yes/No). |
| `political`              | Flags political hate content (Yes/No). |
| `religious`          | Flags religious hate content (Yes/No). |
| `gender`                   | Identifies gender-based hate content (Yes/No). |
| `personal offense`         | Indicates if the text contains personal attacks (Yes/No). |
| `abusive`                  | Flags text with abusive language or can promote violence (Yes/No).   |
| `origin`                   | Hate speech targeting someone's origin, e.g. race, nationality (Yes/No).   |
| `body_shaming`             | Identifies body-shaming content (Yes/No).      |
| `BN`   | Back-transliteration of the text content in Bangla. |
| `EN`      | Translation of the text content in English.       |


