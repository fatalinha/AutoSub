# AutoSub
Resources for automatic subtitling

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
[code](https://github.com/apptek/SubER)
- Sigma: Subtitle Segmentation Score
[code](https://github.com/fyvo/EvalSubtitle)

Subtitle conformity:
- CPL conformity: percentage of subtitles not exceeding a specific subtitle length (in characters per line)
- CPS conformity: percentage of subtitles not exceeding a specific reading speed (in characters per second)
- NOL conformity: percentage of subtitles not exceeding the max. number of lines 
[code](https://github.com/hlt-mt/FBK-fairseq/blob/master/examples/speech_to_text/scripts/subtitle_compliance.py)

## Campaings
IWSLT 2023 Subtitling task: https://iwslt.org/2023/subtitling
