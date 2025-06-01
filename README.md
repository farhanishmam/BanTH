# BanTH: A Multi-label Hate Speech Detection Dataset for Transliterated Bangla

[![anthology](https://img.shields.io/badge/ACL%20Anthology-NAACL%20Findings%202025-EE161F?logo=data:image/png;base64,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&style=flat")](https://aclanthology.org/2025.findings-naacl.403/)
[![code](https://img.shields.io/badge/Code-farhanishmam/BanTH-blue?logo=GitHub)](https://github.com/farhanishmam/BanTH)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20_Dataset-aplycaebous/BanTH-ffc107?color=ffc107&logoColor=white)](https://huggingface.co/datasets/aplycaebous/BanTH)
[![Poster](https://img.shields.io/badge/Poster-EF3939?style=flat&logo=airplayvideo&logoColor=white&color=gray&labelColor=00877a)](https://drive.google.com/file/d/1hfdV5-FcHgfci0IOEJKGgFzJlXC6XuTO/view?usp=sharing)
[![Slides](https://img.shields.io/badge/Slides-EF3939?style=flat&logo=googleslides&logoColor=white&color=gray&labelColor=B7472A)](https://drive.google.com/file/d/1k3dR8KXX-yeoD-H7zM2Cf6_LuTjOEMOR/view?usp=sharing)
[![Video](https://img.shields.io/badge/Video-4285F4?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1NzYgNTEyIj48IS0tIUZvbnQgQXdlc29tZSBGcmVlIDYuNS4yIGJ5IEBmb250YXdlc29tZSAtIGh0dHBzOi8vZm9udGF3ZXNvbWUuY29tIExpY2Vuc2UgLSBodHRwczovL2ZvbnRhd2Vzb21lLmNvbS9saWNlbnNlL2ZyZWUgQ29weXJpZ2h0IDIwMjQgRm9udGljb25zLCBJbmMuLS0+PHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTAgMTI4QzAgOTIuNyAyOC43IDY0IDY0IDY0SDMyMGMzNS4zIDAgNjQgMjguNyA2NCA2NFYzODRjMCAzNS4zLTI4LjcgNjQtNjQgNjRINjRjLTM1LjMgMC02NC0yOC43LTY0LTY0VjEyOHpNNTU5LjEgOTkuOGMxMC40IDUuNiAxNi45IDE2LjQgMTYuOSAyOC4yVjM4NGMwIDExLjgtNi41IDIyLjYtMTYuOSAyOC4ycy0yMyA1LTMyLjktMS42bC05Ni02NEw0MTYgMzM3LjFWMzIwIDE5MiAxNzQuOWwxNC4yLTkuNSA5Ni02NGM5LjgtNi41IDIyLjQtNy4yIDMyLjktMS42eiIvPjwvc3ZnPg==&logoColor=white&color=gray&labelColor=B197FC)](
https://drive.google.com/file/d/1N0GSOMRfacmgEDUvrUpZnkQ8dj0Juneb/view?usp=sharing)

[Fabiha Haider*](https://github.com/FabihaHaider),
[Fariha Tanjim Shifat*](https://github.com/fariha6412),
[Md Farhan Ishmam*](https://farhanishmam.github.io/),
[Deeparghya Dutta Barua](https://github.com/arg274), 
[Md Sakib Ul Rahman Sourove](https://github.com/souroveskb), 
[Md Fahim](https://github.com/md-fahim/), and
[Farhad Alam Bhuiyan](https://github.com/pdfarhad).

## Dataset Overview
- Hate detection (binary) and target identification (multi-label) dataset on 37.3 k transliterated Bangla samples.
- ~38% hate samples and 7 target classes: Political, Religious, Gender, Personal Offense, Abusive/Violence, Origin, and Body Shaming.
- Sourced from 26 YouTube channels of 3 categories: News & Politics, People & Blogs, and Entertainment.
- Each sample is labeled by 3 annotators and verified by experts.

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

## Getting started

To run the code, please check the `.pynb` files in the `notebooks` folder.

## Fine-tuned Language Model Performance
We evaluate baselines using Bangla, Indian, Multi-lingual, and Character-based Language Models. We also propose novel encoders, further pre-trained on the Transliterated Bangla (TB) pre-training corpus.

|Model           | F1(Binary) | Acc(Binary) | F1(Multi-Label) | Subset Acc | Hamming Loss |
|-----------------|----------|----------|----------|----------|----------|
| BanglaBERT      | 76.50    | 81.04    | 20.82    | 54.08    | 7.26     |
| BanglishBERT    | 75.07    | 80.62    | 20.61    | 52.74    | 7.42     |
| BanglaHateBERT  | 70.92    | 77.54    | 11.34    | 49.83    | 7.97     |
| VAC-BERT        | 74.19    | 79.76    | 18.45    | 52.56    | 7.50     |
| MuRIL    | 75.29    | 80.83    | 14.58    | 53.98    | 7.55     |
| IndicBERT| 74.51    | 80.48    | 13.39    | 51.56    | 7.88     |
| mBERT    | 74.97    | 80.37    | 28.24    | 52.19    | 7.78     |
| XLM-R    | 77.35    | 81.37    | 29.29    | 53.28    | 7.23     |
| CharBERT  | 76.61    | 80.91    | 19.66    | 53.21    | 7.44     |
| TB-BERT           | 76.27    | 79.25    | **30.17**| 54.19    | **7.18** |
| TB-mBERT          | **77.36**| **82.57**| 27.07    | **54.71**| 7.28     |
| TB-XLM-R          | 77.04    | 81.29    | 29.04    | 52.86    | 7.26     |
| TB-BanglaBERT     | 77.12    | 81.61    | 22.52    | 53.97    | 7.37     |
| TB-BanglishBERT   | 77.12    | 81.39    | 21.41    | 52.79    | 7.42     |

## Prompting Strategies
We propose a novel prompting strategy that translates the transliterated Bangla into either Bangla or English before inferencing. Our strategy achieves sota at the 0-shot setting.

| Strategy               | Prompt                                                                                       |
|-------------------------------|----------------------------------------------------------------------------------------------|
| Non-Explanatory               | Base-prompt                                                                                  |
| Chain of Thought (CoT)        | Base-prompt + "Let’s think step by step"                                                     |
| Explanation-based (Exp)       | Base-prompt + "Explain why"                                                                  |
| HARE                          | Base-prompt + "Let’s explain step by step"                                                   |
| Why [Positive]                | Base-prompt + "Explain why the comment is positive"                                          |
| Why [Negative]                | Base-prompt + "Explain why the comment is negative"                                          |
| Translation Based [BAN]       | "Translate the following transliterated text into standard Bangla" + Prompt-Strategy         |
| Translation Based [ENG]       | "Translate the following transliterated text into standard English" + Prompt-Strategy        |

## Prompt-based Large Language Model Performance
|Model           | F1(Binary) | Acc(Binary) | F1(Multi-Label) | Subset Acc | Hamming Loss |
|----------------------------|----------|----------|----------|----------|----------|
| GPT 3.5                    | 61.44    | 64.02    | 24.12    | 18.27    | 19.77    |
| GPT 4.0                    | 70.05    | 74.30    | 36.07    | 22.60    | 16.91    |
| GPT 3.5 + Few-shot         | 61.85    | 65.65    | 23.86    | 16.85    | 20.36    |
| GPT 4.0 + Few-shot         | 68.77    | 74.18    | **39.53**| **26.76**| **14.16**|
| GPT 3.5 + CoT              | 61.87    | 65.77    | 25.61    | 20.34    | 19.28    |
| GPT 4.0 + CoT              | 69.87    | 74.14    | 35.97    | 22.60    | 16.64    |
| GPT 3.5 + CoT + Few-shot   | 63.30    | 67.80    | 28.35    | 20.15    | 19.15    |
| GPT 4.0 + CoT + Few-shot   | 69.50    | 74.94    | 36.49    | 21.10    | 17.36    |
| GPT 3.5 + Exp              | 61.69    | 65.16    | 22.61    | 17.33    | 19.84    |
| GPT 4.0 + Exp              | 69.91    | 74.16    | 32.58    | 19.12    | 17.94    |
| GPT 3.5 + Exp + Few-shot   | 62.69    | 66.60    | 25.00    | 18.36    | 19.57    |
| GPT 4.0 + Exp + Few-shot   | **70.70**| 75.15    | 35.61    | 21.33    | 17.15    |
| GPT 3.5 + HARE             | 62.64    | 66.77    | 25.99    | 20.90    | 18.94    |
| GPT 4.0 + HARE             | 69.71    | 74.75    | 36.67    | 20.80    | 17.10    |
| GPT 3.5 + HARE + Few-shot  | 62.20    | 66.72    | 24.68    | 20.06    | 19.96    |
| GPT 4.0 + HARE + Few-shot  | 69.12    | 74.75    | 34.06    | 21.59    | 17.37    |
| GPT 4.0 + Translation [BAN]        | 69.63    | 72.70    | 35.72    | 23.28    | 16.73    |
| GPT 4.0 + Translation [ENG]        | 69.38    | 72.96    | 34.28    | 22.08    | 16.91    |
| GPT 4.0 + Translation [BAN] + CoT  | 69.74    | 72.66    | 35.30    | 21.35    | 17.61    |
| GPT 4.0 + Translation [ENG] + CoT  | 69.14    | **74.87**    | 34.87| 19.96    | 16.91    |
| GPT 4.0 + Translation [BAN] + Exp  | 70.33    | 73.65    | 20.36    | 21.54    | 16.46    |
| GPT 4.0 + Translation [ENG] + Exp  | 70.19    | 73.84    | 36.25    | 23.92    | 16.23    |






