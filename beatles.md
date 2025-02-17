---
title: beatles
{:.no_toc}
layout: default
---

# beatles
{:.no_toc}

This is the [tempo_eval](https://tempoeval.github.io/tempo_eval/) report for the 'beatles' corpus.

Reports for other corpora may be found [here](index.md).

## Table of Contents
{:.no_toc}

- TOC
{:toc}

# References for 'beatles'

## References

### 1.2

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 1.2 |
| **Curator** | [Christopher Harte](mailto:chris@melodient.com) |
| **Data&nbsp;Source** | manual annotation |
| **Annotation&nbsp;Tools** | derived from beat annotations |
| **Annotation&nbsp;Rules** | median of corresponding inter beat intervals |
| **Annotator,&nbsp;bibtex** |[Harte2010](bib/Harte2010.bib) |
| **Annotator,&nbsp;ref_url** | [http://isophonics.net/content/reference-annotations-beatles](http://isophonics.net/content/reference-annotations-beatles) |

## Basic Statistics

| Reference| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [1.2](#12)                                         |   179   |   66.06   |   184.62   |   117.45   |   27.30   |   79.00   |   0.84   |

<a name="table1"></a>Table 1: Basic statistics.

[CSV](data/beatles_reference_basic_stats.csv "Download data as CSV") [JSON](data/beatles_reference_basic_stats.json "Download data as JSON") [LATEX](data/beatles_reference_basic_stats.latex "Download data as LATEX") [PICKLE](data/beatles_reference_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/beatles_reference_dist.svg">
</figure>

<a name="figure1"></a>Figure 1: Percentage of values in tempo interval.

[CSV](data/beatles_reference_dist.csv "Download data as CSV") [JSON](data/beatles_reference_dist.json "Download data as JSON") [LATEX](data/beatles_reference_dist.latex "Download data as LATEX") [PICKLE](data/beatles_reference_dist.pickle "Download data as PICKLE") [SVG](figures/beatles_reference_dist.svg "Open Figure") [PDF](figures/beatles_reference_dist.pdf "Open Figure") [PNG](figures/beatles_reference_dist.png "Open Figure") 

## Beat-Based Tempo Variation

<figure>
<embed type="image/svg+xml" src="figures/beatles_variation.svg">
</figure>

<a name="figure2"></a>Figure 2: Fraction of the dataset with beat-annotated tracks with c<sub>var</sub> < τ.

[CSV](data/beatles_variation.csv "Download data as CSV") [JSON](data/beatles_variation.json "Download data as JSON") [LATEX](data/beatles_variation.latex "Download data as LATEX") [PICKLE](data/beatles_variation.pickle "Download data as PICKLE") [SVG](figures/beatles_variation.svg "Open Figure") [PDF](figures/beatles_variation.pdf "Open Figure") [PNG](figures/beatles_variation.png "Open Figure") 

# Estimates for 'beatles'

## Estimators

### boeck2015/tempodetector2016_default

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.17.dev0 |
| **Annotation&nbsp;Tools** | TempoDetector.2016, madmom, https://github.com/CPJKU/madmom |
| **Annotator,&nbsp;bibtex** |[Boeck2015](bib/Boeck2015.bib) |

### boeck2019/multi_task

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

### boeck2019/multi_task_hjdb

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | model=multi_task_hjdb, https://github.com/superbock/ISMIR2019 |
| **Annotator,&nbsp;bibtex** |[Boeck2019](bib/Boeck2019.bib) |

### boeck2020/dar

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | https://github.com/superbock/ISMIR2020 |
| **Annotator,&nbsp;bibtex** |[Boeck2020](bib/Boeck2020.bib) |

### davies2009/mirex_qm_tempotracker

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | QM Tempotracker, Sonic Annotator plugin. https://code.soundsoftware.ac.uk/projects/mirex2013/repository/show/audio_tempo_estimation/qm-tempotracker Note that the current macOS build of 'qm-vamp-plugins' was used. |
| **Annotator,&nbsp;bibtex** |[Davies2009](bib/Davies2009.bib) |[Davies2007](bib/Davies2007.bib) |

### percival2014/stem

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 1.0 |
| **Annotation&nbsp;Tools** | percival 2014, 'tempo' implementation from Marsyas, http://marsyas.info, git checkout tempo-stem |
| **Annotator,&nbsp;bibtex** |[Percival2014](bib/Percival2014.bib) |

### schreiber2014/default

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.0.1 |
| **Annotation&nbsp;Tools** | schreiber 2014, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2014](bib/Schreiber2014.bib) |

### schreiber2017/ismir2017

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=ismir2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2017/mirex2017

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.0.4 |
| **Annotation&nbsp;Tools** | schreiber 2017, model=mirex2017, http://www.tagtraum.com/tempo_estimation.html |
| **Annotator,&nbsp;bibtex** |[Schreiber2017](bib/Schreiber2017.bib) |

### schreiber2018/cnn

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=cnn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/fcn

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=fcn), https://github.com/hendriks73/tempo-cnn |

### schreiber2018/ismir2018

| Attribute | Value |
| --- | --- |
| **Corpus** | beatles |
| **Version** | 0.0.2 |
| **Data&nbsp;Source** | Hendrik Schreiber, Meinard Müller. A Single-Step Approach to Musical Tempo Estimation Using a Convolutional Neural Network. In Proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR), Paris, France, Sept. 2018. |
| **Annotation&nbsp;Tools** | schreiber tempo-cnn (model=ismir2018), https://github.com/hendriks73/tempo-cnn |

## Basic Statistics

| Estimator| Size | Min | Max | Avg | Stdev | Sweet Oct. Start | Sweet Oct. Coverage |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   180   |   45.80   |   181.82   |   114.26   |   28.16   |   72.00   |   0.83   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   180   |   63.02   |   199.41   |   114.82   |   27.23   |   72.00   |   0.87   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   180   |   63.83   |   182.90   |   116.71   |   26.92   |   72.00   |   0.84   |
| [boeck2020/dar](#boeck2020dar)                     |   180   |   58.61   |   193.94   |   117.35   |   29.05   |   78.00   |   0.82   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   180   |   77.13   |   184.57   |   127.49   |   24.88   |   87.00   |   0.96   |
| [percival2014/stem](#percival2014stem)             |   180   |   50.92   |   156.60   |   105.01   |   23.19   |   70.00   |   0.92   |
| [schreiber2014/default](#schreiber2014default)     |   180   |   54.35   |   149.20   |   97.61   |   23.07   |   67.00   |   0.89   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   180   |   40.53   |   174.90   |   112.25   |   26.21   |   72.00   |   0.87   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   180   |   40.53   |   206.84   |   111.57   |   27.97   |   72.00   |   0.84   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   180   |   58.00   |   200.00   |   121.86   |   31.59   |   76.00   |   0.78   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   180   |   38.00   |   199.00   |   116.51   |   32.40   |   76.00   |   0.77   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   180   |   67.00   |   195.00   |   120.38   |   28.06   |   76.00   |   0.86   |

<a name="table2"></a>Table 2: Basic statistics.

[CSV](data/beatles_estimates_basic_stats.csv "Download data as CSV") [JSON](data/beatles_estimates_basic_stats.json "Download data as JSON") [LATEX](data/beatles_estimates_basic_stats.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_basic_stats.pickle "Download data as PICKLE") 

## Smoothed Tempo Distribution

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_dist.svg">
</figure>

<a name="figure3"></a>Figure 3: Percentage of values in tempo interval.

[CSV](data/beatles_estimates_dist.csv "Download data as CSV") [JSON](data/beatles_estimates_dist.json "Download data as JSON") [LATEX](data/beatles_estimates_dist.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_dist.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_dist.svg "Open Figure") [PDF](figures/beatles_estimates_dist.pdf "Open Figure") [PNG](figures/beatles_estimates_dist.png "Open Figure") 

## Accuracy

Accuracy<sub>1</sub> is defined as the percentage of correct estimates, allowing a 4% tolerance for individual BPM values.

Accuracy<sub>2</sub> additionally permits estimates to be wrong by a factor of 2, 3, 1/2 or 1/3 (so-called *octave errors*).

See [[Gouyon2006](bib/Gouyon2006.bib)].

*Note: When comparing accuracy values for different algorithms, keep in mind that an algorithm may have been trained on the test set or that the test set may have even been created using one of the tested algorithms.*

### Accuracy Results for 1.2

| Estimator| Accuracy1 | Accuracy2 |
| ---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.9162__ | __0.9944__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.8883   |   0.9777   |
| [boeck2020/dar](#boeck2020dar)                     |   0.8715   |   0.9553   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.8603   |   0.9721   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.8547   |   0.9832   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8492   |   0.9777   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.8492   |   0.9888   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.8436   |   0.9777   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.8324   |   0.9665   |
| [percival2014/stem](#percival2014stem)             |   0.8156   | __0.9944__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.8045   |   0.9721   |
| [schreiber2014/default](#schreiber2014default)     |   0.6536   |   0.9050   |

<a name="table3"></a>Table 3: Mean accuracy of estimates compared to version [1.2](#12) with 4% tolerance ordered by Accuracy<sub>1</sub>.

[CSV](data/beatles_estimates_1.2_accuracy_tol04.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_accuracy_tol04.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_accuracy_tol04.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_accuracy_tol04.pickle "Download data as PICKLE") 

Raw data Accuracy<sub>1</sub>: [CSV](data/beatles_estimates_1.2_raw_accuracy1_tol04.csv "Download raw data as CSV") [JSON](data/beatles_estimates_1.2_raw_accuracy1_tol04.json "Download raw data as JSON") [LATEX](data/beatles_estimates_1.2_raw_accuracy1_tol04.latex "Download raw data as LATEX") [PICKLE](data/beatles_estimates_1.2_raw_accuracy1_tol04.pickle "Download raw data as PICKLE") 

Raw data Accuracy<sub>2</sub>: [CSV](data/beatles_estimates_1.2_raw_accuracy2_tol04.csv "Download raw data as CSV") [JSON](data/beatles_estimates_1.2_raw_accuracy2_tol04.json "Download raw data as JSON") [LATEX](data/beatles_estimates_1.2_raw_accuracy2_tol04.latex "Download raw data as LATEX") [PICKLE](data/beatles_estimates_1.2_raw_accuracy2_tol04.pickle "Download raw data as PICKLE") 

### Accuracy<sub>1</sub> for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_accuracy1.svg">
</figure>

<a name="figure4"></a>Figure 4: Mean Accuracy<sub>1</sub> for estimates compared to version [1.2](#12) depending on tolerance.

[CSV](data/beatles_estimates_1.2_accuracy1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_accuracy1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_accuracy1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_accuracy1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_accuracy1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_accuracy1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_accuracy2.svg">
</figure>

<a name="figure5"></a>Figure 5: Mean Accuracy<sub>2</sub> for estimates compared to version [1.2](#12) depending on tolerance.

[CSV](data/beatles_estimates_1.2_accuracy2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_accuracy2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_accuracy2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_accuracy2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_accuracy2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_accuracy2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_accuracy2.png "Open Figure") 

### Differing Items

For which items did a given estimator not estimate a correct value with respect to a given ground truth? Are there items which are either very difficult, not suitable for the task, or incorrectly annotated and therefore never estimated correctly, regardless which estimator is used?

#### Differing Items Accuracy<sub>1</sub>

Items with different tempo annotations (Accuracy<sub>1</sub>, 4% tolerance) in different versions:

*[1.2](#12) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (15 differences):*
'04\_-\_Beatles\_for\_Sale/02\_-\_I'm\_a\_Loser' '05\_-\_Help!/02\_-\_The\_Night\_Before' '05\_-\_Help!/03\_-\_You've\_Got\_To\_Hide\_Your\_Love\_Away' '05\_-\_Help!/05\_-\_Another\_Girl' '05\_-\_Help!/10\_-\_You\_Like\_Me\_Too\_Much' '06\_-\_Rubber\_Soul/02\_-\_Norwegian\_Wood\_(This\_Bird\_Has\_Flown)' '07\_-\_Revolver/10\_-\_For\_No\_One' '07\_-\_Revolver/11\_-\_Doctor\_Robert' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/09\_-\_When\_I'm\_Sixty-Four' '09\_-\_Magical\_Mystery\_Tour/01\_-\_Magical\_Mystery\_Tour' ...
[CSV](data/beatles_estimates_1.2_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [boeck2019/multi_task](#boeck2019multi_task) (27 differences):*
'02\_-\_With\_the\_Beatles/04\_-\_Don't\_Bother\_Me' '02\_-\_With\_the\_Beatles/05\_-\_Little\_Child' '02\_-\_With\_the\_Beatles/10\_-\_You\_Really\_Got\_A\_Hold\_On\_Me' '04\_-\_Beatles\_for\_Sale/02\_-\_I'm\_a\_Loser' '04\_-\_Beatles\_for\_Sale/03\_-\_Baby's\_In\_Black' '04\_-\_Beatles\_for\_Sale/04\_-\_Rock\_and\_Roll\_Music' '04\_-\_Beatles\_for\_Sale/14\_-\_Everybody's\_Trying\_to\_Be\_My\_Baby' '05\_-\_Help!/02\_-\_The\_Night\_Before' '05\_-\_Help!/05\_-\_Another\_Girl' '05\_-\_Help!/10\_-\_You\_Like\_Me\_Too\_Much' '06\_-\_Rubber\_Soul/02\_-\_Norwegian\_Wood\_(This\_Bird\_Has\_Flown)' ...
[CSV](data/beatles_estimates_1.2_boeck2019_multi_task_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (20 differences):*
'02\_-\_With\_the\_Beatles/04\_-\_Don't\_Bother\_Me' '02\_-\_With\_the\_Beatles/10\_-\_You\_Really\_Got\_A\_Hold\_On\_Me' '04\_-\_Beatles\_for\_Sale/02\_-\_I'm\_a\_Loser' '04\_-\_Beatles\_for\_Sale/04\_-\_Rock\_and\_Roll\_Music' '04\_-\_Beatles\_for\_Sale/14\_-\_Everybody's\_Trying\_to\_Be\_My\_Baby' '05\_-\_Help!/02\_-\_The\_Night\_Before' '05\_-\_Help!/05\_-\_Another\_Girl' '05\_-\_Help!/10\_-\_You\_Like\_Me\_Too\_Much' '06\_-\_Rubber\_Soul/10\_-\_I'm\_Looking\_Through\_You' '06\_-\_Rubber\_Soul/14\_-\_Run\_For\_Your\_Life' '07\_-\_Revolver/10\_-\_For\_No\_One' ...
[CSV](data/beatles_estimates_1.2_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [boeck2020/dar](#boeck2020dar) (23 differences):*
'02\_-\_With\_the\_Beatles/04\_-\_Don't\_Bother\_Me' '04\_-\_Beatles\_for\_Sale/02\_-\_I'm\_a\_Loser' '05\_-\_Help!/05\_-\_Another\_Girl' '05\_-\_Help!/10\_-\_You\_Like\_Me\_Too\_Much' '06\_-\_Rubber\_Soul/08\_-\_What\_Goes\_On' '06\_-\_Rubber\_Soul/10\_-\_I'm\_Looking\_Through\_You' '06\_-\_Rubber\_Soul/14\_-\_Run\_For\_Your\_Life' '07\_-\_Revolver/10\_-\_For\_No\_One' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/08\_-\_Within\_You\_Without\_You' '09\_-\_Magical\_Mystery\_Tour/01\_-\_Magical\_Mystery\_Tour' ...
[CSV](data/beatles_estimates_1.2_boeck2020_dar_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (35 differences):*
'01\_-\_Please\_Please\_Me/12\_-\_A\_Taste\_Of\_Honey' '03\_-\_A\_Hard\_Day's\_Night/07\_-\_Can't\_Buy\_Me\_Love' '04\_-\_Beatles\_for\_Sale/03\_-\_Baby's\_In\_Black' '04\_-\_Beatles\_for\_Sale/14\_-\_Everybody's\_Trying\_to\_Be\_My\_Baby' '05\_-\_Help!/03\_-\_You've\_Got\_To\_Hide\_Your\_Love\_Away' '05\_-\_Help!/10\_-\_You\_Like\_Me\_Too\_Much' '06\_-\_Rubber\_Soul/02\_-\_Norwegian\_Wood\_(This\_Bird\_Has\_Flown)' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/13\_-\_A\_Day\_In\_The\_Life' '09\_-\_Magical\_Mystery\_Tour/01\_-\_Magical\_Mystery\_Tour' '09\_-\_Magical\_Mystery\_Tour/02\_-\_The\_Fool\_On\_The\_Hill' ...
[CSV](data/beatles_estimates_1.2_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [percival2014/stem](#percival2014stem) (33 differences):*
'01\_-\_Please\_Please\_Me/01\_-\_I\_Saw\_Her\_Standing\_There' '01\_-\_Please\_Please\_Me/08\_-\_Love\_Me\_Do' '02\_-\_With\_the\_Beatles/03\_-\_All\_My\_Loving' '02\_-\_With\_the\_Beatles/04\_-\_Don't\_Bother\_Me' '02\_-\_With\_the\_Beatles/05\_-\_Little\_Child' '02\_-\_With\_the\_Beatles/08\_-\_Roll\_Over\_Beethoven' '03\_-\_A\_Hard\_Day's\_Night/06\_-\_Tell\_Me\_Why' '03\_-\_A\_Hard\_Day's\_Night/07\_-\_Can't\_Buy\_Me\_Love' '04\_-\_Beatles\_for\_Sale/04\_-\_Rock\_and\_Roll\_Music' '04\_-\_Beatles\_for\_Sale/08\_-\_Eight\_Days\_a\_Week' '04\_-\_Beatles\_for\_Sale/10\_-\_Honey\_Don't' ...
[CSV](data/beatles_estimates_1.2_percival2014_stem_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2014/default](#schreiber2014default) (62 differences):*
'01\_-\_Please\_Please\_Me/01\_-\_I\_Saw\_Her\_Standing\_There' '01\_-\_Please\_Please\_Me/02\_-\_Misery' '01\_-\_Please\_Please\_Me/05\_-\_Boys' '01\_-\_Please\_Please\_Me/06\_-\_Ask\_Me\_Why' '01\_-\_Please\_Please\_Me/07\_-\_Please\_Please\_Me' '01\_-\_Please\_Please\_Me/08\_-\_Love\_Me\_Do' '01\_-\_Please\_Please\_Me/09\_-\_P.\_S.\_I\_Love\_You' '01\_-\_Please\_Please\_Me/13\_-\_There's\_A\_Place' '02\_-\_With\_the\_Beatles/03\_-\_All\_My\_Loving' '02\_-\_With\_the\_Beatles/04\_-\_Don't\_Bother\_Me' '02\_-\_With\_the\_Beatles/05\_-\_Little\_Child' ...
[CSV](data/beatles_estimates_1.2_schreiber2014_default_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (27 differences):*
'02\_-\_With\_the\_Beatles/03\_-\_All\_My\_Loving' '02\_-\_With\_the\_Beatles/04\_-\_Don't\_Bother\_Me' '03\_-\_A\_Hard\_Day's\_Night/06\_-\_Tell\_Me\_Why' '04\_-\_Beatles\_for\_Sale/03\_-\_Baby's\_In\_Black' '04\_-\_Beatles\_for\_Sale/10\_-\_Honey\_Don't' '04\_-\_Beatles\_for\_Sale/14\_-\_Everybody's\_Trying\_to\_Be\_My\_Baby' '05\_-\_Help!/03\_-\_You've\_Got\_To\_Hide\_Your\_Love\_Away' '05\_-\_Help!/10\_-\_You\_Like\_Me\_Too\_Much' '06\_-\_Rubber\_Soul/02\_-\_Norwegian\_Wood\_(This\_Bird\_Has\_Flown)' '07\_-\_Revolver/10\_-\_For\_No\_One' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' ...
[CSV](data/beatles_estimates_1.2_schreiber2017_ismir2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (28 differences):*
'01\_-\_Please\_Please\_Me/06\_-\_Ask\_Me\_Why' '01\_-\_Please\_Please\_Me/08\_-\_Love\_Me\_Do' '03\_-\_A\_Hard\_Day's\_Night/06\_-\_Tell\_Me\_Why' '04\_-\_Beatles\_for\_Sale/03\_-\_Baby's\_In\_Black' '04\_-\_Beatles\_for\_Sale/10\_-\_Honey\_Don't' '04\_-\_Beatles\_for\_Sale/14\_-\_Everybody's\_Trying\_to\_Be\_My\_Baby' '05\_-\_Help!/02\_-\_The\_Night\_Before' '05\_-\_Help!/03\_-\_You've\_Got\_To\_Hide\_Your\_Love\_Away' '05\_-\_Help!/10\_-\_You\_Like\_Me\_Too\_Much' '05\_-\_Help!/11\_-\_Tell\_Me\_What\_You\_See' '06\_-\_Rubber\_Soul/10\_-\_I'm\_Looking\_Through\_You' ...
[CSV](data/beatles_estimates_1.2_schreiber2017_mirex2017_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2018/cnn](#schreiber2018cnn) (30 differences):*
'02\_-\_With\_the\_Beatles/04\_-\_Don't\_Bother\_Me' '03\_-\_A\_Hard\_Day's\_Night/09\_-\_I'll\_Cry\_Instead' '04\_-\_Beatles\_for\_Sale/02\_-\_I'm\_a\_Loser' '04\_-\_Beatles\_for\_Sale/12\_-\_I\_Don't\_Want\_to\_Spoil\_the\_Party' '05\_-\_Help!/01\_-\_Help!' '05\_-\_Help!/02\_-\_The\_Night\_Before' '05\_-\_Help!/05\_-\_Another\_Girl' '05\_-\_Help!/08\_-\_Act\_Naturally' '06\_-\_Rubber\_Soul/08\_-\_What\_Goes\_On' '06\_-\_Rubber\_Soul/10\_-\_I'm\_Looking\_Through\_You' '06\_-\_Rubber\_Soul/14\_-\_Run\_For\_Your\_Life' ...
[CSV](data/beatles_estimates_1.2_schreiber2018_cnn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2018/fcn](#schreiber2018fcn) (26 differences):*
'01\_-\_Please\_Please\_Me/07\_-\_Please\_Please\_Me' '02\_-\_With\_the\_Beatles/05\_-\_Little\_Child' '02\_-\_With\_the\_Beatles/10\_-\_You\_Really\_Got\_A\_Hold\_On\_Me' '02\_-\_With\_the\_Beatles/11\_-\_I\_Wanna\_Be\_Your\_Man' '03\_-\_A\_Hard\_Day's\_Night/06\_-\_Tell\_Me\_Why' '03\_-\_A\_Hard\_Day's\_Night/09\_-\_I'll\_Cry\_Instead' '04\_-\_Beatles\_for\_Sale/02\_-\_I'm\_a\_Loser' '04\_-\_Beatles\_for\_Sale/08\_-\_Eight\_Days\_a\_Week' '05\_-\_Help!/02\_-\_The\_Night\_Before' '05\_-\_Help!/08\_-\_Act\_Naturally' '06\_-\_Rubber\_Soul/08\_-\_What\_Goes\_On' ...
[CSV](data/beatles_estimates_1.2_schreiber2018_fcn_diff_items_tol04_accuracy1.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (25 differences):*
'02\_-\_With\_the\_Beatles/03\_-\_All\_My\_Loving' '02\_-\_With\_the\_Beatles/04\_-\_Don't\_Bother\_Me' '03\_-\_A\_Hard\_Day's\_Night/09\_-\_I'll\_Cry\_Instead' '04\_-\_Beatles\_for\_Sale/02\_-\_I'm\_a\_Loser' '05\_-\_Help!/02\_-\_The\_Night\_Before' '05\_-\_Help!/05\_-\_Another\_Girl' '05\_-\_Help!/08\_-\_Act\_Naturally' '06\_-\_Rubber\_Soul/08\_-\_What\_Goes\_On' '06\_-\_Rubber\_Soul/14\_-\_Run\_For\_Your\_Life' '07\_-\_Revolver/10\_-\_For\_No\_One' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' ...
[CSV](data/beatles_estimates_1.2_schreiber2018_ismir2018_diff_items_tol04_accuracy1.csv "Download list as CSV")

__None of the estimators estimated the following item 'correctly' using Accuracy<sub>1</sub>:__
'08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' 
[CSV](data/beatles_estimates_all_diff_items_tol04_accuracy1.csv "Download list as CSV")

#### Differing Items Accuracy<sub>2</sub>

Items with different tempo annotations (Accuracy<sub>2</sub>, 4% tolerance) in different versions:

*[1.2](#12) compared with [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) (1 differences):*
'08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' 
[CSV](data/beatles_estimates_1.2_boeck2015_tempodetector2016_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [boeck2019/multi_task](#boeck2019multi_task) (4 differences):*
'02\_-\_With\_the\_Beatles/10\_-\_You\_Really\_Got\_A\_Hold\_On\_Me' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '11\_-\_Abbey\_Road/06\_-\_I\_Want\_You' '12\_-\_Let\_It\_Be/04\_-\_I\_Me\_Mine' 
[CSV](data/beatles_estimates_1.2_boeck2019_multi_task_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) (4 differences):*
'02\_-\_With\_the\_Beatles/10\_-\_You\_Really\_Got\_A\_Hold\_On\_Me' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '11\_-\_Abbey\_Road/06\_-\_I\_Want\_You' '12\_-\_Let\_It\_Be/04\_-\_I\_Me\_Mine' 
[CSV](data/beatles_estimates_1.2_boeck2019_multi_task_hjdb_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [boeck2020/dar](#boeck2020dar) (8 differences):*
'08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/08\_-\_Within\_You\_Without\_You' '09\_-\_Magical\_Mystery\_Tour/01\_-\_Magical\_Mystery\_Tour' '09\_-\_Magical\_Mystery\_Tour/06\_-\_I\_Am\_The\_Walrus' '09\_-\_Magical\_Mystery\_Tour/11\_-\_All\_You\_Need\_Is\_Love' '10CD1\_-\_The\_Beatles/CD1\_-\_02\_-\_Dear\_Prudence' '11\_-\_Abbey\_Road/06\_-\_I\_Want\_You' '11\_-\_Abbey\_Road/09\_-\_You\_Never\_Give\_Me\_Your\_Money' 
[CSV](data/beatles_estimates_1.2_boeck2020_dar_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) (5 differences):*
'01\_-\_Please\_Please\_Me/12\_-\_A\_Taste\_Of\_Honey' '04\_-\_Beatles\_for\_Sale/03\_-\_Baby's\_In\_Black' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '09\_-\_Magical\_Mystery\_Tour/04\_-\_Blue\_Jay\_Way' '12\_-\_Let\_It\_Be/05\_-\_Dig\_It' 
[CSV](data/beatles_estimates_1.2_davies2009_mirex_qm_tempotracker_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [percival2014/stem](#percival2014stem) (1 differences):*
'08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' 
[CSV](data/beatles_estimates_1.2_percival2014_stem_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2014/default](#schreiber2014default) (17 differences):*
'04\_-\_Beatles\_for\_Sale/03\_-\_Baby's\_In\_Black' '07\_-\_Revolver/04\_-\_Love\_You\_To' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/05\_-\_Fixing\_A\_Hole' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/08\_-\_Within\_You\_Without\_You' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/13\_-\_A\_Day\_In\_The\_Life' '09\_-\_Magical\_Mystery\_Tour/04\_-\_Blue\_Jay\_Way' '09\_-\_Magical\_Mystery\_Tour/08\_-\_Strawberry\_Fields\_Forever' '09\_-\_Magical\_Mystery\_Tour/11\_-\_All\_You\_Need\_Is\_Love' '10CD1\_-\_The\_Beatles/CD1\_-\_10\_-\_I'm\_So\_Tired' '10CD2\_-\_The\_Beatles/CD2\_-\_08\_-\_Revolution\_1' ...
[CSV](data/beatles_estimates_1.2_schreiber2014_default_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2017/ismir2017](#schreiber2017ismir2017) (2 differences):*
'04\_-\_Beatles\_for\_Sale/03\_-\_Baby's\_In\_Black' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' 
[CSV](data/beatles_estimates_1.2_schreiber2017_ismir2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2017/mirex2017](#schreiber2017mirex2017) (4 differences):*
'04\_-\_Beatles\_for\_Sale/03\_-\_Baby's\_In\_Black' '05\_-\_Help!/03\_-\_You've\_Got\_To\_Hide\_Your\_Love\_Away' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '12\_-\_Let\_It\_Be/04\_-\_I\_Me\_Mine' 
[CSV](data/beatles_estimates_1.2_schreiber2017_mirex2017_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2018/cnn](#schreiber2018cnn) (6 differences):*
'08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/13\_-\_A\_Day\_In\_The\_Life' '09\_-\_Magical\_Mystery\_Tour/04\_-\_Blue\_Jay\_Way' '10CD1\_-\_The\_Beatles/CD1\_-\_10\_-\_I'm\_So\_Tired' '11\_-\_Abbey\_Road/06\_-\_I\_Want\_You' '12\_-\_Let\_It\_Be/04\_-\_I\_Me\_Mine' 
[CSV](data/beatles_estimates_1.2_schreiber2018_cnn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2018/fcn](#schreiber2018fcn) (3 differences):*
'08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '09\_-\_Magical\_Mystery\_Tour/04\_-\_Blue\_Jay\_Way' '11\_-\_Abbey\_Road/09\_-\_You\_Never\_Give\_Me\_Your\_Money' 
[CSV](data/beatles_estimates_1.2_schreiber2018_fcn_diff_items_tol04_accuracy2.csv "Download list as CSV")

*[1.2](#12) compared with [schreiber2018/ismir2018](#schreiber2018ismir2018) (5 differences):*
'08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' '08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/13\_-\_A\_Day\_In\_The\_Life' '10CD2\_-\_The\_Beatles/CD2\_-\_02\_-\_Yer\_Blues' '11\_-\_Abbey\_Road/09\_-\_You\_Never\_Give\_Me\_Your\_Money' '12\_-\_Let\_It\_Be/04\_-\_I\_Me\_Mine' 
[CSV](data/beatles_estimates_1.2_schreiber2018_ismir2018_diff_items_tol04_accuracy2.csv "Download list as CSV")

__None of the estimators estimated the following item 'correctly' using Accuracy<sub>2</sub>:__
'08\_-\_Sgt.\_Pepper's\_Lonely\_Hearts\_Club\_Band/03\_-\_Lucy\_In\_The\_Sky\_With\_Diamonds' 
[CSV](data/beatles_estimates_all_diff_items_tol04_accuracy2.csv "Download list as CSV")

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0169__ |   0.3323   |   0.1153   | __0.0017__ | __0.0005__ | __0.0000__ | __0.0290__ | __0.0146__ | __0.0107__ | __0.0433__ |   0.0872   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0169__ |   1.0000   | __0.0391__ |   0.5235   |   0.2800   |   0.3616   | __0.0000__ |   1.0000   |   1.0000   |   0.7201   |   1.0000   |   0.8450   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.3323   | __0.0391__ |   1.0000   |   0.6072   | __0.0275__ | __0.0241__ | __0.0000__ |   0.2478   |   0.2153   |   0.0755   |   0.3075   |   0.4049   |
| [boeck2020/dar](#boeck2020dar)                     |   0.1153   |   0.5235   |   0.6072   |   1.0000   |   0.0961   |   0.1433   | __0.0000__ |   0.5966   |   0.5114   |   0.2295   |   0.6900   |   0.8318   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0017__ |   0.2800   | __0.0275__ |   0.0961   |   1.0000   |   0.8877   | __0.0018__ |   0.2153   |   0.3604   |   0.5758   |   0.2624   |   0.1539   |
| [percival2014/stem](#percival2014stem)             | __0.0005__ |   0.3616   | __0.0241__ |   0.1433   |   0.8877   |   1.0000   | __0.0000__ |   0.3075   |   0.4583   |   0.7552   |   0.3105   |   0.2682   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0018__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0290__ |   1.0000   |   0.2478   |   0.5966   |   0.2153   |   0.3075   | __0.0000__ |   1.0000   |   1.0000   |   0.7552   |   1.0000   |   0.8601   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0146__ |   1.0000   |   0.2153   |   0.5114   |   0.3604   |   0.4583   | __0.0000__ |   1.0000   |   1.0000   |   0.8776   |   0.8714   |   0.7552   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0107__ |   0.7201   |   0.0755   |   0.2295   |   0.5758   |   0.7552   | __0.0001__ |   0.7552   |   0.8776   |   1.0000   |   0.5572   |   0.3593   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0433__ |   1.0000   |   0.3075   |   0.6900   |   0.2624   |   0.3105   | __0.0000__ |   1.0000   |   0.8714   |   0.5572   |   1.0000   |   1.0000   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0872   |   0.8450   |   0.4049   |   0.8318   |   0.1539   |   0.2682   | __0.0000__ |   0.8601   |   0.7552   |   0.3593   |   1.0000   |   1.0000   |

<a name="table4"></a>Table 4: McNemar p-values, using reference annotations [1.2](#12) as groundtruth with Accuracy<sub>1</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/beatles_estimates_accuracy1_significance.csv "Download data as CSV") [JSON](data/beatles_estimates_accuracy1_significance.json "Download data as JSON") [LATEX](data/beatles_estimates_accuracy1_significance.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_accuracy1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.2500   |   0.2500   | __0.0156__ |   0.1250   |   1.0000   | __0.0000__ |   1.0000   |   0.2500   |   0.0625   |   0.5000   |   0.1250   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.2500   |   1.0000   |   1.0000   |   0.2891   |   1.0000   |   0.2500   | __0.0010__ |   0.6250   |   1.0000   |   0.6250   |   1.0000   |   1.0000   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.2500   |   1.0000   |   1.0000   |   0.2891   |   1.0000   |   0.2500   | __0.0010__ |   0.6250   |   1.0000   |   0.6250   |   1.0000   |   1.0000   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0156__ |   0.2891   |   0.2891   |   1.0000   |   0.5488   | __0.0156__ | __0.0352__ |   0.0703   |   0.3437   |   0.7539   |   0.1250   |   0.5078   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1250   |   1.0000   |   1.0000   |   0.5488   |   1.0000   |   0.1250   | __0.0042__ |   0.2500   |   1.0000   |   1.0000   |   0.6250   |   1.0000   |
| [percival2014/stem](#percival2014stem)             |   1.0000   |   0.2500   |   0.2500   | __0.0156__ |   0.1250   |   1.0000   | __0.0000__ |   1.0000   |   0.2500   |   0.0625   |   0.5000   |   0.1250   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0010__ | __0.0010__ | __0.0352__ | __0.0042__ | __0.0000__ |   1.0000   | __0.0001__ | __0.0010__ | __0.0010__ | __0.0001__ | __0.0018__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   1.0000   |   0.6250   |   0.6250   |   0.0703   |   0.2500   |   1.0000   | __0.0001__ |   1.0000   |   0.5000   |   0.2188   |   1.0000   |   0.3750   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2500   |   1.0000   |   1.0000   |   0.3437   |   1.0000   |   0.2500   | __0.0010__ |   0.5000   |   1.0000   |   0.6875   |   1.0000   |   1.0000   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0625   |   0.6250   |   0.6250   |   0.7539   |   1.0000   |   0.0625   | __0.0010__ |   0.2188   |   0.6875   |   1.0000   |   0.3750   |   1.0000   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5000   |   1.0000   |   1.0000   |   0.1250   |   0.6250   |   0.5000   | __0.0001__ |   1.0000   |   1.0000   |   0.3750   |   1.0000   |   0.6250   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1250   |   1.0000   |   1.0000   |   0.5078   |   1.0000   |   0.1250   | __0.0018__ |   0.3750   |   1.0000   |   1.0000   |   0.6250   |   1.0000   |

<a name="table5"></a>Table 5: McNemar p-values, using reference annotations [1.2](#12) as groundtruth with Accuracy<sub>2</sub> [[Gouyon2006](bib/Gouyon2006.bib)]. H<sub>0</sub>: both estimators disagree with the groundtruth to the same amount. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference in the disagreement with the groundtruth. In the table, p-values<0.05 are set in bold.

[CSV](data/beatles_estimates_accuracy2_significance.csv "Download data as CSV") [JSON](data/beatles_estimates_accuracy2_significance.json "Download data as JSON") [LATEX](data/beatles_estimates_accuracy2_significance.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_accuracy2_significance.pickle "Download data as PICKLE") 

### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>1</sub> on c<sub>var</sub>-Subsets for 1.2 based on c<sub>var</sub>-Values from 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_1.2_cv_accuracy1.svg">
</figure>

<a name="figure6"></a>Figure 6: Mean Accuracy<sub>1</sub> compared to version [1.2](#12) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.2](#12).

[CSV](data/beatles_estimates_1.2_1.2_cv_accuracy1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_1.2_cv_accuracy1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_1.2_cv_accuracy1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_1.2_cv_accuracy1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_1.2_cv_accuracy1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_1.2_cv_accuracy1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_1.2_cv_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### Accuracy<sub>2</sub> on c<sub>var</sub>-Subsets for 1.2 based on c<sub>var</sub>-Values from 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_1.2_cv_accuracy2.svg">
</figure>

<a name="figure7"></a>Figure 7: Mean Accuracy<sub>2</sub> compared to version [1.2](#12) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.2](#12).

[CSV](data/beatles_estimates_1.2_1.2_cv_accuracy2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_1.2_cv_accuracy2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_1.2_cv_accuracy2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_1.2_cv_accuracy2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_1.2_cv_accuracy2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_1.2_cv_accuracy2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_1.2_cv_accuracy2.png "Open Figure") 

### Accuracy<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>1</sub> on Tempo-Subsets for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_inter_accuracy1.svg">
</figure>

<a name="figure8"></a>Figure 8: Mean Accuracy<sub>1</sub> for estimates compared to version [1.2](#12) for tempo intervals around T.

[CSV](data/beatles_estimates_1.2_inter_accuracy1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_inter_accuracy1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_inter_accuracy1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_inter_accuracy1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_inter_accuracy1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_inter_accuracy1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_inter_accuracy1.png "Open Figure") 

### Accuracy<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean Accuracy<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### Accuracy<sub>2</sub> on Tempo-Subsets for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_inter_accuracy2.svg">
</figure>

<a name="figure9"></a>Figure 9: Mean Accuracy<sub>2</sub> for estimates compared to version [1.2](#12) for tempo intervals around T.

[CSV](data/beatles_estimates_1.2_inter_accuracy2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_inter_accuracy2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_inter_accuracy2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_inter_accuracy2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_inter_accuracy2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_inter_accuracy2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_inter_accuracy2.png "Open Figure") 

### Estimated Accuracy<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>1</sub>-values and a ground truth, what Accuracy<sub>1</sub> can we expect with confidence?

#### Estimated Accuracy<sub>1</sub> for Tempo for 1.2

Predictions of GAMs trained on Accuracy<sub>1</sub> for estimates for reference [1.2](#12).

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_tempo_gam_accuracy1.svg">
</figure>

<a name="figure10"></a>Figure 10: Accuracy<sub>1</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>1</sub> results for [1.2](#12). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/beatles_estimates_1.2_tempo_gam_accuracy1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_tempo_gam_accuracy1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_tempo_gam_accuracy1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_tempo_gam_accuracy1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_tempo_gam_accuracy1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_tempo_gam_accuracy1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_tempo_gam_accuracy1.png "Open Figure") 

### Estimated Accuracy<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to Accuracy<sub>2</sub>-values and a ground truth, what Accuracy<sub>2</sub> can we expect with confidence?

#### Estimated Accuracy<sub>2</sub> for Tempo for 1.2

Predictions of GAMs trained on Accuracy<sub>2</sub> for estimates for reference [1.2](#12).

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_tempo_gam_accuracy2.svg">
</figure>

<a name="figure11"></a>Figure 11: Accuracy<sub>2</sub> predictions of a generalized additive model (GAM) fit to Accuracy<sub>2</sub> results for [1.2](#12). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/beatles_estimates_1.2_tempo_gam_accuracy2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_tempo_gam_accuracy2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_tempo_gam_accuracy2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_tempo_gam_accuracy2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_tempo_gam_accuracy2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_tempo_gam_accuracy2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_tempo_gam_accuracy2.png "Open Figure") 

## OE<sub>1</sub> and OE<sub>2</sub>

OE<sub>1</sub> is defined as octave error between an estimate <code>E</code> and a reference value <code>R</code>.This means that the most common errors&mdash;by a factor of 2 or &frac12;&mdash;have the same magnitude, namely 1: <code>OE<sub>2</sub>(E) = log<sub>2</sub>(E/R)</code>.

OE<sub>2</sub> is the signed OE<sub>1</sub> corresponding to the minimum absolute OE<sub>1</sub> allowing the octaveerrors 2, 3, 1/2, and 1/3: <code>OE<sub>2</sub>(E) = arg min<sub>x</sub>(|x|) with x ∈ {OE<sub>1</sub>(E), OE<sub>1</sub>(2E), OE<sub>1</sub>(3E), OE<sub>1</sub>(&frac12;E), OE<sub>1</sub>(&frac13;E)}</code>

### Mean OE<sub>1</sub>/OE<sub>2</sub> Results for 1.2

| Estimator| OE1_MEAN | OE1_STDEV | OE2_MEAN | OE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   -0.0381   | __0.2938__ |   -0.0013   |   0.0353   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   -0.0077   |   0.3235   |   -0.0045   |   0.0502   |
| [boeck2020/dar](#boeck2020dar)                     | __-0.0018__ |   0.3261   |   -0.0064   |   0.0424   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0360   |   0.3372   |   -0.0087   |   0.0599   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   -0.0221   |   0.3587   |   -0.0053   |   0.0376   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   -0.0726   |   0.3675   | __-0.0000__ |   0.0643   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.0467   |   0.3788   |   -0.0059   |   0.0522   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   -0.0327   |   0.3887   |   -0.0048   |   0.0506   |
| [percival2014/stem](#percival2014stem)             |   -0.1612   |   0.4016   |   -0.0015   | __0.0342__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1310   |   0.4028   |   0.0192   |   0.0567   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   -0.0591   |   0.4048   |   -0.0046   |   0.0449   |
| [schreiber2014/default](#schreiber2014default)     |   -0.2663   |   0.4512   |   -0.0060   |   0.0789   |

<a name="table6"></a>Table 6: Mean OE1/OE2 for estimates compared to version [1.2](#12) ordered by standard deviation.

[CSV](data/beatles_estimates_1.2_moe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_moe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_moe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_moe1.pickle "Download data as PICKLE") 

Raw data OE<sub>1</sub>: [CSV](data/beatles_estimates_1.2_raw_oe1.csv "Download raw data as CSV") [JSON](data/beatles_estimates_1.2_raw_oe1.json "Download raw data as JSON") [LATEX](data/beatles_estimates_1.2_raw_oe1.latex "Download raw data as LATEX") [PICKLE](data/beatles_estimates_1.2_raw_oe1.pickle "Download raw data as PICKLE") 

Raw data OE<sub>2</sub>: [CSV](data/beatles_estimates_1.2_raw_oe2.csv "Download raw data as CSV") [JSON](data/beatles_estimates_1.2_raw_oe2.json "Download raw data as JSON") [LATEX](data/beatles_estimates_1.2_raw_oe2.latex "Download raw data as LATEX") [PICKLE](data/beatles_estimates_1.2_raw_oe2.pickle "Download raw data as PICKLE") 

### OE<sub>1</sub> distribution for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_distribution_oe1.svg">
</figure>

<a name="figure12"></a>Figure 12: OE<sub>1</sub> for estimates compared to version [1.2](#12). Shown are the mean OE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/beatles_estimates_1.2_distribution_oe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_distribution_oe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_distribution_oe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_distribution_oe1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_distribution_oe1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_distribution_oe1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_distribution_oe1.png "Open Figure") 

### OE<sub>2</sub> distribution for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_distribution_oe2.svg">
</figure>

<a name="figure13"></a>Figure 13: OE<sub>2</sub> for estimates compared to version [1.2](#12). Shown are the mean OE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/beatles_estimates_1.2_distribution_oe2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_distribution_oe2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_distribution_oe2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_distribution_oe2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_distribution_oe2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_distribution_oe2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_distribution_oe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.8472   |   0.2037   |   0.1328   | __0.0000__ | __0.0000__ | __0.0000__ |   0.4735   |   0.2154   | __0.0050__ |   0.5662   | __0.0093__ |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.8472   |   1.0000   |   0.1687   |   0.2067   | __0.0000__ | __0.0000__ | __0.0000__ |   0.3611   |   0.2077   | __0.0108__ |   0.7245   | __0.0141__ |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.2037   |   0.1687   |   1.0000   |   0.7454   | __0.0000__ | __0.0000__ | __0.0000__ |   0.0895   | __0.0381__ |   0.0509   |   0.6188   |   0.0792   |
| [boeck2020/dar](#boeck2020dar)                     |   0.1328   |   0.2067   |   0.7454   |   1.0000   | __0.0003__ | __0.0000__ | __0.0000__ |   0.0754   | __0.0281__ | __0.0404__ |   0.4549   |   0.1192   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0003__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0357__ | __0.0001__ | __0.0057__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0009__ | __0.0002__ | __0.0033__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0009__ |   1.0000   | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.4735   |   0.3611   |   0.0895   |   0.0754   | __0.0000__ | __0.0002__ | __0.0000__ |   1.0000   |   0.6121   | __0.0039__ |   0.3002   | __0.0032__ |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.2154   |   0.2077   | __0.0381__ | __0.0281__ | __0.0000__ | __0.0033__ | __0.0000__ |   0.6121   |   1.0000   | __0.0006__ |   0.1210   | __0.0014__ |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0050__ | __0.0108__ |   0.0509   | __0.0404__ | __0.0357__ | __0.0000__ | __0.0000__ | __0.0039__ | __0.0006__ |   1.0000   | __0.0125__ |   0.6438   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.5662   |   0.7245   |   0.6188   |   0.4549   | __0.0001__ | __0.0000__ | __0.0000__ |   0.3002   |   0.1210   | __0.0125__ |   1.0000   | __0.0439__ |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) | __0.0093__ | __0.0141__ |   0.0792   |   0.1192   | __0.0057__ | __0.0000__ | __0.0000__ | __0.0032__ | __0.0014__ |   0.6438   | __0.0439__ |   1.0000   |

<a name="table7"></a>Table 7: Paired t-test p-values, using reference annotations [1.2](#12) as groundtruth with OE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/beatles_estimates_oe1_significance.csv "Download data as CSV") [JSON](data/beatles_estimates_oe1_significance.json "Download data as JSON") [LATEX](data/beatles_estimates_oe1_significance.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_oe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.2514   |   0.2982   | __0.0293__ | __0.0000__ |   0.8430   |   0.5248   |   0.1913   |   0.7584   |   0.1737   | __0.0348__ |   0.0744   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.2514   |   1.0000   |   0.3126   |   0.5892   | __0.0000__ |   0.2601   |   0.8685   |   0.9717   |   0.3319   |   0.7714   |   0.8738   |   0.4541   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.2982   |   0.3126   |   1.0000   |   0.5233   | __0.0000__ |   0.3090   |   0.8348   |   0.9638   |   0.3641   |   0.7207   |   0.8034   |   0.4277   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0293__ |   0.5892   |   0.5233   |   1.0000   | __0.0000__ | __0.0261__ |   0.9545   |   0.5979   |   0.1670   |   0.8972   |   0.6578   |   0.6242   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0009__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ | __0.0000__ |
| [percival2014/stem](#percival2014stem)             |   0.8430   |   0.2601   |   0.3090   | __0.0261__ | __0.0000__ |   1.0000   |   0.5338   |   0.1919   |   0.7233   |   0.1880   | __0.0379__ |   0.0800   |
| [schreiber2014/default](#schreiber2014default)     |   0.5248   |   0.8685   |   0.8348   |   0.9545   | __0.0009__ |   0.5338   |   1.0000   |   0.8442   |   0.3961   |   0.9939   |   0.9221   |   0.7627   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1913   |   0.9717   |   0.9638   |   0.5979   | __0.0000__ |   0.1919   |   0.8442   |   1.0000   |   0.1579   |   0.7601   |   0.8222   |   0.3918   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.7584   |   0.3319   |   0.3641   |   0.1670   | __0.0000__ |   0.7233   |   0.3961   |   0.1579   |   1.0000   |   0.3599   |   0.2480   |   0.2011   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1737   |   0.7714   |   0.7207   |   0.8972   | __0.0000__ |   0.1880   |   0.9939   |   0.7601   |   0.3599   |   1.0000   |   0.8655   |   0.4252   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0348__ |   0.8738   |   0.8034   |   0.6578   | __0.0000__ | __0.0379__ |   0.9221   |   0.8222   |   0.2480   |   0.8655   |   1.0000   |   0.4055   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0744   |   0.4541   |   0.4277   |   0.6242   | __0.0000__ |   0.0800   |   0.7627   |   0.3918   |   0.2011   |   0.4252   |   0.4055   |   1.0000   |

<a name="table8"></a>Table 8: Paired t-test p-values, using reference annotations [1.2](#12) as groundtruth with OE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/beatles_estimates_oe2_significance.csv "Download data as CSV") [JSON](data/beatles_estimates_oe2_significance.json "Download data as JSON") [LATEX](data/beatles_estimates_oe2_significance.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_oe2_significance.pickle "Download data as PICKLE") 

### OE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.2 based on c<sub>var</sub>-Values from 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_1.2_cv_oe1.svg">
</figure>

<a name="figure14"></a>Figure 14: Mean OE<sub>1</sub> compared to version [1.2](#12) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.2](#12).

[CSV](data/beatles_estimates_1.2_1.2_cv_oe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_1.2_cv_oe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_1.2_cv_oe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_1.2_cv_oe1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_1.2_cv_oe1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_1.2_cv_oe1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_1.2_cv_oe1.png "Open Figure") 

### OE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### OE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.2 based on c<sub>var</sub>-Values from 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_1.2_cv_oe2.svg">
</figure>

<a name="figure15"></a>Figure 15: Mean OE<sub>2</sub> compared to version [1.2](#12) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.2](#12).

[CSV](data/beatles_estimates_1.2_1.2_cv_oe2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_1.2_cv_oe2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_1.2_cv_oe2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_1.2_cv_oe2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_1.2_cv_oe2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_1.2_cv_oe2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_1.2_cv_oe2.png "Open Figure") 

### OE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>1</sub> on Tempo-Subsets for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_inter_oe1.svg">
</figure>

<a name="figure16"></a>Figure 16: Mean OE<sub>1</sub> for estimates compared to version [1.2](#12) for tempo intervals around T.

[CSV](data/beatles_estimates_1.2_inter_oe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_inter_oe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_inter_oe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_inter_oe1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_inter_oe1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_inter_oe1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_inter_oe1.png "Open Figure") 

### OE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean OE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### OE<sub>2</sub> on Tempo-Subsets for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_inter_oe2.svg">
</figure>

<a name="figure17"></a>Figure 17: Mean OE<sub>2</sub> for estimates compared to version [1.2](#12) for tempo intervals around T.

[CSV](data/beatles_estimates_1.2_inter_oe2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_inter_oe2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_inter_oe2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_inter_oe2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_inter_oe2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_inter_oe2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_inter_oe2.png "Open Figure") 

### Estimated OE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>1</sub>-values and a ground truth, what OE<sub>1</sub> can we expect with confidence?

#### Estimated OE<sub>1</sub> for Tempo for 1.2

Predictions of GAMs trained on OE<sub>1</sub> for estimates for reference [1.2](#12).

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_tempo_gam_oe1.svg">
</figure>

<a name="figure18"></a>Figure 18: OE<sub>1</sub> predictions of a generalized additive model (GAM) fit to OE<sub>1</sub> results for [1.2](#12). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/beatles_estimates_1.2_tempo_gam_oe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_tempo_gam_oe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_tempo_gam_oe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_tempo_gam_oe1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_tempo_gam_oe1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_tempo_gam_oe1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_tempo_gam_oe1.png "Open Figure") 

### Estimated OE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to OE<sub>2</sub>-values and a ground truth, what OE<sub>2</sub> can we expect with confidence?

#### Estimated OE<sub>2</sub> for Tempo for 1.2

Predictions of GAMs trained on OE<sub>2</sub> for estimates for reference [1.2](#12).

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_tempo_gam_oe2.svg">
</figure>

<a name="figure19"></a>Figure 19: OE<sub>2</sub> predictions of a generalized additive model (GAM) fit to OE<sub>2</sub> results for [1.2](#12). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/beatles_estimates_1.2_tempo_gam_oe2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_tempo_gam_oe2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_tempo_gam_oe2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_tempo_gam_oe2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_tempo_gam_oe2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_tempo_gam_oe2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_tempo_gam_oe2.png "Open Figure") 

## AOE<sub>1</sub> and AOE<sub>2</sub>

AOE<sub>1</sub> is defined as absolute octave error between an estimate and a reference value: <code>AOE<sub>1</sub>(E) = |log<sub>2</sub>(E/R)|</code>.

AOE<sub>2</sub> is the minimum of AOE<sub>1</sub> allowing the octave errors 2, 3, 1/2, and 1/3: <code>AOE<sub>2</sub>(E) = min(AOE<sub>1</sub>(E), AOE<sub>1</sub>(2E), AOE<sub>1</sub>(3E), AOE<sub>1</sub>(&frac12;E), AOE<sub>1</sub>(&frac13;E))</code>.

### Mean AOE<sub>1</sub>/AOE<sub>2</sub> Results for 1.2

| Estimator| AOE1_MEAN | AOE1_STDEV | AOE2_MEAN | AOE2_STDEV |
| ---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) | __0.0913__ | __0.2819__ |   0.0106   |   0.0337   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.1094   |   0.3045   |   0.0121   |   0.0489   |
| [boeck2020/dar](#boeck2020dar)                     |   0.1118   |   0.3063   |   0.0178   |   0.0390   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1283   |   0.3139   |   0.0177   |   0.0579   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.1412   |   0.3305   |   0.0143   |   0.0351   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.1512   |   0.3596   |   0.0118   |   0.0494   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.1530   |   0.3419   |   0.0175   |   0.0618   |
| [schreiber2018/cnn](#schreiber2018cnn)             |   0.1538   |   0.3493   |   0.0173   |   0.0496   |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.1618   |   0.3757   |   0.0129   |   0.0433   |
| [percival2014/stem](#percival2014stem)             |   0.1871   |   0.3902   | __0.0069__ | __0.0335__ |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) |   0.1964   |   0.3753   |   0.0282   |   0.0528   |
| [schreiber2014/default](#schreiber2014default)     |   0.2926   |   0.4346   |   0.0342   |   0.0713   |

<a name="table9"></a>Table 9: Mean AOE1/AOE2 for estimates compared to version [1.2](#12) ordered by mean.

[CSV](data/beatles_estimates_1.2_maoe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_maoe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_maoe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_maoe1.pickle "Download data as PICKLE") 

Raw data AOE<sub>1</sub>: [CSV](data/beatles_estimates_1.2_raw_aoe1.csv "Download raw data as CSV") [JSON](data/beatles_estimates_1.2_raw_aoe1.json "Download raw data as JSON") [LATEX](data/beatles_estimates_1.2_raw_aoe1.latex "Download raw data as LATEX") [PICKLE](data/beatles_estimates_1.2_raw_aoe1.pickle "Download raw data as PICKLE") 

Raw data AOE<sub>2</sub>: [CSV](data/beatles_estimates_1.2_raw_aoe2.csv "Download raw data as CSV") [JSON](data/beatles_estimates_1.2_raw_aoe2.json "Download raw data as JSON") [LATEX](data/beatles_estimates_1.2_raw_aoe2.latex "Download raw data as LATEX") [PICKLE](data/beatles_estimates_1.2_raw_aoe2.pickle "Download raw data as PICKLE") 

### AOE<sub>1</sub> distribution for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_distribution_aoe1.svg">
</figure>

<a name="figure20"></a>Figure 20: AOE<sub>1</sub> for estimates compared to version [1.2](#12). Shown are the mean AOE<sub>1</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/beatles_estimates_1.2_distribution_aoe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_distribution_aoe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_distribution_aoe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_distribution_aoe1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_distribution_aoe1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_distribution_aoe1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_distribution_aoe1.png "Open Figure") 

### AOE<sub>2</sub> distribution for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_distribution_aoe2.svg">
</figure>

<a name="figure21"></a>Figure 21: AOE<sub>2</sub> for estimates compared to version [1.2](#12). Shown are the mean AOE<sub>2</sub> and an empirical distribution of the sample, using kernel density estimation (KDE).

[CSV](data/beatles_estimates_1.2_distribution_aoe2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_distribution_aoe2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_distribution_aoe2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_distribution_aoe2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_distribution_aoe2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_distribution_aoe2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_distribution_aoe2.png "Open Figure") 

### Significance of Differences

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   | __0.0294__ |   0.4458   |   0.3911   | __0.0014__ | __0.0009__ | __0.0000__ | __0.0140__ | __0.0241__ | __0.0373__ |   0.0687   |   0.1897   |
| [boeck2019/multi_task](#boeck2019multi_task)       | __0.0294__ |   1.0000   | __0.0192__ |   0.1052   |   0.2068   |   0.2487   | __0.0001__ |   0.7128   |   0.9544   |   0.9338   |   0.7285   |   0.4132   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.4458   | __0.0192__ |   1.0000   |   0.8973   | __0.0105__ | __0.0087__ | __0.0000__ |   0.0805   |   0.1612   |   0.1101   |   0.2424   |   0.4422   |
| [boeck2020/dar](#boeck2020dar)                     |   0.3911   |   0.1052   |   0.8973   |   1.0000   | __0.0174__ | __0.0186__ | __0.0000__ |   0.1160   |   0.1981   |   0.0734   |   0.2723   |   0.4881   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0014__ |   0.2068   | __0.0105__ | __0.0174__ |   1.0000   |   0.8135   | __0.0319__ |   0.2751   |   0.2210   |   0.2812   |   0.1598   | __0.0433__ |
| [percival2014/stem](#percival2014stem)             | __0.0009__ |   0.2487   | __0.0087__ | __0.0186__ |   0.8135   |   1.0000   | __0.0005__ |   0.3540   |   0.2601   |   0.3548   |   0.1693   |   0.0916   |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0001__ | __0.0000__ | __0.0000__ | __0.0319__ | __0.0005__ |   1.0000   | __0.0002__ | __0.0000__ | __0.0011__ | __0.0001__ | __0.0000__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) | __0.0140__ |   0.7128   |   0.0805   |   0.1160   |   0.2751   |   0.3540   | __0.0002__ |   1.0000   |   0.7402   |   0.8284   |   0.5636   |   0.3012   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) | __0.0241__ |   0.9544   |   0.1612   |   0.1981   |   0.2210   |   0.2601   | __0.0000__ |   0.7402   |   1.0000   |   0.9820   |   0.7169   |   0.4715   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0373__ |   0.9338   |   0.1101   |   0.0734   |   0.2812   |   0.3548   | __0.0011__ |   0.8284   |   0.9820   |   1.0000   |   0.6469   |   0.2615   |
| [schreiber2018/fcn](#schreiber2018fcn)             |   0.0687   |   0.7285   |   0.2424   |   0.2723   |   0.1598   |   0.1693   | __0.0001__ |   0.5636   |   0.7169   |   0.6469   |   1.0000   |   0.6504   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.1897   |   0.4132   |   0.4422   |   0.4881   | __0.0433__ |   0.0916   | __0.0000__ |   0.3012   |   0.4715   |   0.2615   |   0.6504   |   1.0000   |

<a name="table10"></a>Table 10: Paired t-test p-values, using reference annotations [1.2](#12) as groundtruth with AOE<sub>1</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/beatles_estimates_aoe1_significance.csv "Download data as CSV") [JSON](data/beatles_estimates_aoe1_significance.json "Download data as JSON") [LATEX](data/beatles_estimates_aoe1_significance.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_aoe1_significance.pickle "Download data as PICKLE") 

| Estimator| boeck2015/tempodetector2016_default | boeck2019/multi_task | boeck2019/multi_task_hjdb | boeck2020/dar | davies2009/mirex_qm_tempotracker | percival2014/stem | schreiber2014/default | schreiber2017/ismir2017 | schreiber2017/mirex2017 | schreiber2018/cnn | schreiber2018/fcn | schreiber2018/ismir2018 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [boeck2015/tempodetector2016_default](#boeck2015tempodetector2016_default) |   1.0000   |   0.6501   |   0.5832   | __0.0001__ | __0.0000__ | __0.0000__ | __0.0000__ |   0.3280   |   0.0873   | __0.0211__ | __0.0095__ |   0.0505   |
| [boeck2019/multi_task](#boeck2019multi_task)       |   0.6501   |   1.0000   |   0.3158   | __0.0200__ | __0.0003__ |   0.0678   | __0.0000__ |   0.7653   |   0.2230   |   0.1012   |   0.4124   |   0.1825   |
| [boeck2019/multi_task_hjdb](#boeck2019multi_task_hjdb) |   0.5832   |   0.3158   |   1.0000   | __0.0291__ | __0.0004__ |   0.0552   | __0.0000__ |   0.8286   |   0.2429   |   0.1154   |   0.4702   |   0.1951   |
| [boeck2020/dar](#boeck2020dar)                     | __0.0001__ | __0.0200__ | __0.0291__ |   1.0000   | __0.0069__ | __0.0000__ | __0.0004__ |   0.0742   |   0.9439   |   0.8427   |   0.0646   |   0.9704   |
| [davies2009/mirex_qm_tempotracker](#davies2009mirex_qm_tempotracker) | __0.0000__ | __0.0003__ | __0.0004__ | __0.0069__ |   1.0000   | __0.0000__ |   0.2353   | __0.0000__ | __0.0143__ | __0.0169__ | __0.0001__ | __0.0416__ |
| [percival2014/stem](#percival2014stem)             | __0.0000__ |   0.0678   |   0.0552   | __0.0000__ | __0.0000__ |   1.0000   | __0.0000__ | __0.0095__ | __0.0080__ | __0.0002__ | __0.0000__ | __0.0027__ |
| [schreiber2014/default](#schreiber2014default)     | __0.0000__ | __0.0000__ | __0.0000__ | __0.0004__ |   0.2353   | __0.0000__ |   1.0000   | __0.0000__ | __0.0003__ | __0.0000__ | __0.0000__ | __0.0015__ |
| [schreiber2017/ismir2017](#schreiber2017ismir2017) |   0.3280   |   0.7653   |   0.8286   |   0.0742   | __0.0000__ | __0.0095__ | __0.0000__ |   1.0000   |   0.1579   |   0.2111   |   0.5790   |   0.2610   |
| [schreiber2017/mirex2017](#schreiber2017mirex2017) |   0.0873   |   0.2230   |   0.2429   |   0.9439   | __0.0143__ | __0.0080__ | __0.0003__ |   0.1579   |   1.0000   |   0.9449   |   0.4439   |   0.9699   |
| [schreiber2018/cnn](#schreiber2018cnn)             | __0.0211__ |   0.1012   |   0.1154   |   0.8427   | __0.0169__ | __0.0002__ | __0.0000__ |   0.2111   |   0.9449   |   1.0000   |   0.3098   |   0.8969   |
| [schreiber2018/fcn](#schreiber2018fcn)             | __0.0095__ |   0.4124   |   0.4702   |   0.0646   | __0.0001__ | __0.0000__ | __0.0000__ |   0.5790   |   0.4439   |   0.3098   |   1.0000   |   0.3783   |
| [schreiber2018/ismir2018](#schreiber2018ismir2018) |   0.0505   |   0.1825   |   0.1951   |   0.9704   | __0.0416__ | __0.0027__ | __0.0015__ |   0.2610   |   0.9699   |   0.8969   |   0.3783   |   1.0000   |

<a name="table11"></a>Table 11: Paired t-test p-values, using reference annotations [1.2](#12) as groundtruth with AOE<sub>2</sub>. H<sub>0</sub>: the true mean difference between paired samples is zero. If p<=ɑ, reject H<sub>0</sub>, i.e. we have a significant difference between estimates from the two algorithms. In the table, p-values<0.05 are set in bold.

[CSV](data/beatles_estimates_aoe2_significance.csv "Download data as CSV") [JSON](data/beatles_estimates_aoe2_significance.json "Download data as JSON") [LATEX](data/beatles_estimates_aoe2_significance.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_aoe2_significance.pickle "Download data as PICKLE") 

### AOE<sub>1</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>1</sub> on c<sub>var</sub>-Subsets for 1.2 based on c<sub>var</sub>-Values from 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_1.2_cv_aoe1.svg">
</figure>

<a name="figure22"></a>Figure 22: Mean AOE<sub>1</sub> compared to version [1.2](#12) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.2](#12).

[CSV](data/beatles_estimates_1.2_1.2_cv_aoe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_1.2_cv_aoe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_1.2_cv_aoe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_1.2_cv_aoe1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_1.2_cv_aoe1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_1.2_cv_aoe1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_1.2_cv_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on c<sub>var</sub>-Subsets

How well does an estimator perform, when only taking tracks into account that have a c<sub>var</sub>-value of less than τ, i.e., have a more or less stable beat?

#### AOE<sub>2</sub> on c<sub>var</sub>-Subsets for 1.2 based on c<sub>var</sub>-Values from 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_1.2_cv_aoe2.svg">
</figure>

<a name="figure23"></a>Figure 23: Mean AOE<sub>2</sub> compared to version [1.2](#12) for tracks with c<sub>var</sub> < τ based on beat annotations from [1.2](#12).

[CSV](data/beatles_estimates_1.2_1.2_cv_aoe2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_1.2_cv_aoe2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_1.2_cv_aoe2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_1.2_cv_aoe2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_1.2_cv_aoe2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_1.2_cv_aoe2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_1.2_cv_aoe2.png "Open Figure") 

### AOE<sub>1</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>1</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>1</sub> on Tempo-Subsets for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_inter_aoe1.svg">
</figure>

<a name="figure24"></a>Figure 24: Mean AOE<sub>1</sub> for estimates compared to version [1.2](#12) for tempo intervals around T.

[CSV](data/beatles_estimates_1.2_inter_aoe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_inter_aoe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_inter_aoe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_inter_aoe1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_inter_aoe1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_inter_aoe1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_inter_aoe1.png "Open Figure") 

### AOE<sub>2</sub> on Tempo-Subsets

How well does an estimator perform, when only taking a subset of the reference annotations into account? The graphs show mean AOE<sub>2</sub> for reference subsets with tempi in [T-10,T+10] BPM. Note that the graphs do not show confidence intervals and that some values may be based on very few estimates.

#### AOE<sub>2</sub> on Tempo-Subsets for 1.2

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_inter_aoe2.svg">
</figure>

<a name="figure25"></a>Figure 25: Mean AOE<sub>2</sub> for estimates compared to version [1.2](#12) for tempo intervals around T.

[CSV](data/beatles_estimates_1.2_inter_aoe2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_inter_aoe2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_inter_aoe2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_inter_aoe2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_inter_aoe2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_inter_aoe2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_inter_aoe2.png "Open Figure") 

### Estimated AOE<sub>1</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>1</sub>-values and a ground truth, what AOE<sub>1</sub> can we expect with confidence?

#### Estimated AOE<sub>1</sub> for Tempo for 1.2

Predictions of GAMs trained on AOE<sub>1</sub> for estimates for reference [1.2](#12).

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_tempo_gam_aoe1.svg">
</figure>

<a name="figure26"></a>Figure 26: AOE<sub>1</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>1</sub> results for [1.2](#12). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/beatles_estimates_1.2_tempo_gam_aoe1.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_tempo_gam_aoe1.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_tempo_gam_aoe1.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_tempo_gam_aoe1.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_tempo_gam_aoe1.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_tempo_gam_aoe1.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_tempo_gam_aoe1.png "Open Figure") 

### Estimated AOE<sub>2</sub> for Tempo

When fitting a generalized additive model (GAM) to AOE<sub>2</sub>-values and a ground truth, what AOE<sub>2</sub> can we expect with confidence?

#### Estimated AOE<sub>2</sub> for Tempo for 1.2

Predictions of GAMs trained on AOE<sub>2</sub> for estimates for reference [1.2](#12).

<figure>
<embed type="image/svg+xml" src="figures/beatles_estimates_1.2_tempo_gam_aoe2.svg">
</figure>

<a name="figure27"></a>Figure 27: AOE<sub>2</sub> predictions of a generalized additive model (GAM) fit to AOE<sub>2</sub> results for [1.2](#12). The 95% confidence interval around the prediction is shaded in gray.

[CSV](data/beatles_estimates_1.2_tempo_gam_aoe2.csv "Download data as CSV") [JSON](data/beatles_estimates_1.2_tempo_gam_aoe2.json "Download data as JSON") [LATEX](data/beatles_estimates_1.2_tempo_gam_aoe2.latex "Download data as LATEX") [PICKLE](data/beatles_estimates_1.2_tempo_gam_aoe2.pickle "Download data as PICKLE") [SVG](figures/beatles_estimates_1.2_tempo_gam_aoe2.svg "Open Figure") [PDF](figures/beatles_estimates_1.2_tempo_gam_aoe2.pdf "Open Figure") [PNG](figures/beatles_estimates_1.2_tempo_gam_aoe2.png "Open Figure") 

-------------------------
Generated by [tempo_eval](https://tempoeval.github.io/tempo_eval/) 0.1.1 on 2022-06-29 18:16. Size L.
