# Where Neural Machine Translation and Translation Memories Meet: Domain Adaptation for the Translation of HKSAR Government Press Releases

Author: SIU Sai Cheong (December 2021)

## Abstract

HKSAR Government Press Releases (https://www.info.gov.hk/gia/) by different bureaux and departments serve as an important channel of communication between the government and the public, and they are usually available in both English and Chinese, the two official languages of Hong Kong. The publication of the bilingual press releases could benefit from translation technology, especially with recent advances in neural machine translation (NMT). However, it would be suboptimal to use popular online NMT platforms as they are often designed for general texts and could have issues with terminology and style in the target language.

In this paper, we propose the method “pre-translation with translation memories” to adapt general NMT engines to the translation of the press releases from English into Chinese. Unlike conventional translation memories for human translators, our translation memory complements neural translation models, featuring length-ranked bilingual sentences and sub-sentential units for pre-translating the source text prior to NMT. Our experimental results show that our method outperforms the NMT-only baseline in terms of the BLEU score, suggesting that TMs may offer a simple solution to the adaptation of general NMT to domain-specific translation tasks, without the need of fine-tuning existing models.

## Download

Click [here](https://github.com/siusaicheong/where_NMT_and_MT_meet/blob/main/Where%20NMT%20and%20TM%20meet_siusaicheong_Dec2021.pdf) to view/download the article.

## Citation

Please cite as
``` bibtex
@misc{siu_2021,
  author = "Sai-cheong SIU",
  title = "Where Neural Machine Translation and Translation Memories Meet: Domain Adaptation for the Translation of HKSAR Government Press Releases",
  month = "Dec. 22",
  year = "2021. [Online]",
  url = "https://github.com/siusaicheong/where_nmt_and_tm_meet/"
}
```
