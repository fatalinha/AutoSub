# AutoSub
This repository documents relevant resources for automatic subtitling. 

## Data
**MuST-Cinema (https://ict.fbk.eu/must-cinema/)**

MuST-Cinema is a Multilingual Speech-to-Subtitles corpus. It comprises English audio recordings automatically aligned at the sentence level with their manual transcriptions and translations. Subtitle breaks are marked as special symbols; <eob>: block break (breaks between subtitle blocks) and <eol>: line breaks (breaks between lines inside the same subtitle block)

English to-{Dutch,French,German,Italian,Portuguese,Romanian,Spanish}

## Test sets and benchmarks
  - MuST-Cinema v1.0: 9 TED talks, duration 1 hour [(info)](https://ict.fbk.eu/must-cinema/)
  - MuST-Cinema IWSLT 2023: 14 TED talks, duration 80 minutes [(info)](https://iwslt.org/2023/subtitling)
  - EuroParlTV: European Union, interviews. 12 videos, duration 1 hour [(info)](https://arxiv.org/abs/2209.13192)
  - EC short clips: European Comminssion, informative clips on various social topics. 27 videos, duration 1 hour [(info)](https://arxiv.org/abs/2209.13192)
  - Pelotron: fitness training [(info)](https://iwslt.org/2023/subtitling)
  - ITV Studios: UK series [(info)](https://iwslt.org/2023/subtitling)

## Evaluation metrics
Subtitle quality:
- SubER (Subtitle Edit Rate):
[(code)](https://github.com/apptek/SubER)
- Sigma: Subtitle Segmentation Score
[(code)](https://github.com/fyvo/EvalSubtitle)  

Subtitle conformity:
- CPL conformity: percentage of subtitles not exceeding a specific subtitle length (in characters per line)
- CPS conformity: percentage of subtitles not exceeding a specific reading speed (in characters per second)
- NOL conformity: percentage of subtitles not exceeding the max. number of lines 
[(code)](https://github.com/hlt-mt/FBK-fairseq/blob/master/examples/speech_to_text/scripts/subtitle_compliance.py)

## Campaings
IWSLT 2023 Subtitling task: https://iwslt.org/2023/subtitling
  
## Software
- EvalSubtitle: A toolkit for computing a variety of segmentation scores [(code)](https://github.com/fyvo/EvalSubtitle)

## Automatic subtitling tools
- MateSub: [matesub.com/]
  - Sonix [https://sonix.ai]
  - Zeemo [https://zeemo.ai/]
  - HappyScribe
  - ClosedCaptionCreator
  - Kapwing
  - Veed.io
  - YellaUmbrella
  - Omniscien
  - Apptek + Ooona
  - Recastly
  - MaestraSuite

  
## Papers
  - Alina Karakanta, Fran´cois Buet, Mauro Cettolo, and Fran´cois Yvon. 2022. Evaluating Subtitle Segmentation for End-to-end Generation Systems. In Proceedings of the 13th Language Resources and Evaluation Conference (LREC), pages 3069–3078, Marseilles, France.
  - Alina Karakanta, Marco Gaido, Matteo Negri, and Marco Turchi. 2021. Between flexibility and consistency: Joint generation of captions and subtitles. In Proceedings of the 18th International Conference on Spoken Language Translation (IWSLT 2021), pages 215–225, Bangkok, Thailand (online).
  - Alina Karakanta, Matteo Negri, and Marco Turchi. 2020a. Is 42 the answer to everything in subtitling-oriented speech translation? In Proceedings of the 17th International Conference on Spoken Language Translation, pages 209–219, Online.
  - Alina Karakanta, Matteo Negri, and Marco Turchi. 2020b. MuST-cinema: a speech-to-subtitles corpus. In Proc. of the 12th Language Resources and Evaluation Conference, pages 3727–3734, Marseille, France.
  - Danni Liu, Jan Niehues, and Gerasimos Spanakis. 2020a. Adapting end-to-end speech recognition for readable subtitles. In Proceedings of the 17th International Conference on Spoken Language Translation, pages 247–256, Online.
  - Maarit Koponen, Umut Sulubacak, Kaisa Vitikainen, and Jörg Tiedemann. 2020. MT for subtitling: User evaluation of post-editing productivity. In Proceedings of the 22nd Annual Conference of the European Association for Machine Translation, pages 115–124, Lisboa, Portugal
  Evgeny Matusov, Patrick Wilken, and Yota Georgakopoulou. 2019. Customizing neural machine translation for subtitling. In Proceedings of the Fourth Conference on Machine Translation (Volume 1: Research Papers), pages 82–93, Florence, Italy.
  - Evgeny Matusov, Patrick Wilken, and Christian Herold. 2020. Flexible customization of a single neural machine translation system with multidimensional
metadata inputs. In Proceedings of the 14th Conference of the Association for Machine Translation in the Americas (Volume 2: User Track), pages 204–216.
  - Maite Melero, Antoni Oliver, and Toni Badia. 2006. Automatic Multilingual Subtitling in the eTITLE Project. In Proceedings of ASLIB Translating and the Computer 28.
## Others
  - Experimental research: [reproducibility checklist](https://github.com/fatalinha/AutoSub/blob/main/reproList.docx)
  
## Blogs
  - Las herramientas del futuro del subtitulado: https://jugandoatraducir.com/las-herramientas-del-futuro-del-subtitulado-transcripciones-y-subtitulos-automaticos/
  
# Contact
  If you have any resources or information that you want to include, please get in touch.
  alina [at] karakanta [dot] com
