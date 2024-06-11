# Repository for latest PDF versions of the timeline project

This website contains the latest PDFs for download, linked from the QR codes on the timelines itself.

![timeline 4.6](https://raw.githubusercontent.com/kreier/timeline/main/docs/timeline20240516_4.6.png)

| language                                                                | print | version | last updated |
|-------------------------------------------------------------------------|:-----:|:-------:|:------------:|
| [English](https://timeline24.github.io/timeline_en.pdf)                 | [link](https://timeline24.github.io/timeline_en_print.pdf)  |   4.6   |  2024-06-07  |
| [German (Deutsch)](https://timeline24.github.io/timeline_de.pdf)        | [link](https://timeline24.github.io/timeline_de_print.pdf)  |   4.6   |  2024-06-07  |
| [Vietnamese (Tiếng Việt)](https://timeline24.github.io/timeline_vi.pdf) | [link](https://timeline24.github.io/timeline_vi_print.pdf)  |   4.6   |  2024-06-11  |
| [French (Français)](https://timeline24.github.io/timeline_fr.pdf)       |       |   4.5   |  2024-04-14  |
| [Spanish (Español)](https://timeline24.github.io/timeline_es.pdf)       |       |   4.5   |  2024-04-23  |
| [Russian (Русский)](https://timeline24.github.io/timeline_ru.pdf)       |       |   4.5   |  2024-04-15  |
| [Iloko (Ilocano)](https://timeline24.github.io/timeline_ilo.pdf)        | [link](https://timeline24.github.io/timeline_ilo_print.pdf) |   4.6   |  2024-06-10  |
| [Kankana-ey](https://timeline24.github.io/timeline_kne.pdf)             | [link](https://timeline24.github.io/timeline_kne_print.pdf) |   4.6   |  2024-06-10  |
| [Finnish (Suomi)](https://timeline24.github.io/timeline_fi.pdf)         |       |   4.5   |  2024-04-17  |
| [Tagalog (Filipino)](https://timeline24.github.io/timeline_tl.pdf)      | [link](https://timeline24.github.io/timeline_tl_print.pdf)  |   4.6   |  2024-06-10  |
| [Norwegian (Norsk)](https://timeline24.github.io/timeline_no.pdf)       |       |   4.3   |  2024-03-30  |
| [Japanese (日本語)](https://timeline24.github.io/timeline_ja.pdf)        | [link](https://timeline24.github.io/timeline_ja_print.pdf)  |   4.6   |  2024-06-11  |
| [Korean (한국인)](https://timeline24.github.io/timeline_ko.pdf)          |       |   4.4   |  2024-03-30  |
| [Sinhala (සිංහල)](https://timeline24.github.io/timeline_si.pdf)         |       |   4.3   |  2024-03-30   |
| [Chinese Mandarin (Simplified) (普通话)](https://timeline24.github.io/timeline_zh.pdf) |       | 4.4 | 2024-04-04 |
| [Chinese Cantonese (Simplified)  (广东话)](https://timeline24.github.io/timeline_yue.pdf) |       | 4.4 | 2024-04-04 |
| [Khmer (ខ្មែរ)](https://timeline24.github.io/timeline_km.pdf)             |       |   4.5   |  2024-04-22  |
| [Arabic (العربية)](https://timeline24.github.io/timeline_ar.pdf)       |        |   3.6   |              |
| [Igbo (Ásụ̀sụ́ Ìgbò)](https://timeline24.github.io/timeline_ig.pdf)       |       |   3.6   |              |
| [Thai (ภาษาไทย)](https://timeline24.github.io/timeline_th.pdf)          |       |   3.6   |              |

## Project repository

The work on the timeline is done and documented at the repository [https://github.com/kreier/timeline](https://github.com/kreier/timeline).

The idea for this project started with spreadsheets in 2009. I moved to vector graphics in 2015. Then from 2023 on it was finally generated with a python program and the __reportlab package__ to make the creation, translation and editing much faster and easier. We stopped using reportlab with version 4.6 in summer 2024 and moved to [fpdf2](https://py-pdf.github.io/fpdf2/index.html) with 4.7 to support complicated glyph composition for languages like Khmer, Sinhala and Arabic that requires a specific shape engine like [harfbuzz](https://github.com/harfbuzz/harfbuzz).

## Improvement - report mistakes

If you spot a mistake, please add an issue at [https://github.com/kreier/timeline/issues](https://github.com/kreier/timeline/issues)

## Create your own PDF in a browser

To greate your own version just using a browser you can try out this [Jupyter Notebook at Google Colab](https://colab.research.google.com/drive/1G0z6jKIs_B_Md_y6Wen108Keo5WazalZ?usp=sharing). Simply press __Runtime - Run all__. It requires less than 60 seconds.

## Edit your own edition in a browser

To edit the files in the browser its best to have your own Github account. Fork the [timeline](https://github.com/kreier/timeline) repository and create a Codespace within the fork. Install the needed 3 libraries (reportlab, svglib and googletranslate) and the CSV extention to Visual Studio Code. You're good to go! Change everything you want - just using the browser.
