---
layout: default
---

Welcome!

This website is intended to provide students of neurolinguistics, both novice and experienced alike, with useful resources to explore data of various types. :nerd_face:

Scroll down to find [open datasets](#Datasets) that you can download and explore. These are followed by a small smattering of [practical tutorials](#Tutorials) in neuroscience, programming, and statistics.

# Datasets

The public release of datasets  is a cornerstone of open science. In this particular collection, I include only datasets that could be relevant to an investigation of linguistics-related questions (including auditory processing) and which contain neural data (EEG, MEG, FFR, ECoG, fMRI, etc.). They are in no particular order. All papers are linked to the DOI or ArXiv for ease of reference, but many are also freely available via PubMed Central.

* EEG: [ERP CORE](#erp-core--eeg), [Llanos/Reetzke](#llanos/reetzke-audiobook-listening--eeg), [Broderick](#broderick-natural-listening-datasets--eeg), [Brennan](#brennan-'alice-in-wonderland'-listening--eeg), [Das](#das-auditory-attention--eeg), [Cavanagh](#cavanagh-oddballs--eeg), ['Baby' Rhythms](#'baby-rhythms'-cortical-tracking-in-infants-of-nursery-rhymes--eeg), [MacIntyre](#macIntyre-vocoded-sherlock-story--eeg), [Reetzke](#reetzke-mandarin-tone-learning--eeg-(ffr)), [Baus](#baus-tracking/n400-dataset--eeg)
* MEG: [MEG-MASC](#meg-masc--meg), [Kösem Speed](#kösem-speech-rhythms--meg), [Kösem Vocoded](#kösem-vocoder-training--meg), [Amoruso](#amoruso-social-verbs-dataset--meg)
* fMRI: [LeBel](#lebel-podcast-listening--fmri), [Nastase](#'narratives'-(nastase-natural-listening)--fmri)
* ECoG: [Tang](#tang-pitch-listening--ecog), [Zada](#zada-'podcast'-dataset--ecog)
* sEEG: [VocalMind](#vocalmind-dataset--seeg)
* Combos: [Ershaid](#ershaid-cortical-tracking-in-noise--eeg+pupillometry), [Issa](#issa-measures-of-cortical-tracking-of-speech--ecog/eeg/meg)

### ERP CORE | EEG

The ERP CORE dataset has two experiments of particular interest to neurolinguists: the N400 and the MMN. The N400 will especially appeal to those who want to investigate lexical semantics (in English) while the MMN is an important ERP in auditory processing. Participants are 40 English speakers.

[OSF:N400](https://osf.io/29xpq/) –– [OSF:MMN](https://osf.io/5q4xs/) –– [Website](https://erpinfo.org/erp-core) –– [Paper](https://doi.org/10.1016/j.neuroimage.2020.117465)

### Llanos/Reetzke Audiobook Listening | EEG

A dataset of 15 participants listening to an English audiobook, read by an American male speaker, interlaced with distractor tones. Participants are monolingual English L1 (n=15) and multilingual English L2, Mandarin L1 speakers (n=15).

[Zenodo](https://zenodo.org/record/4721936#.YI%20dHxZBKjb1) –– [Paper](https://doi.org/10.1016/j.neuropsychologia.2021.107883)

### Broderick Natural Listening Datasets | EEG

A collection of datasets that includes naturalistic listening, RSVP reading, and speech in noise experiments. The paper offers details on stimuli, procedures, and participants. All three auditory datasets (natural speech, reverse speech, and cocktail party speech) are also available in CND format from the CNSP.

[Dryad](https://doi.org/10.5061/dryad.070jc) –– [CNSP](https://cnspworkshop.net/resources.html) –– [Paper](https://doi.org/10.1016/j.cub.2018.01.080)

### MEG-MASC | MEG

An MEG dataset in which 27 participants (all but one of whom were English L1) listened to several English stories produced by a text-to-speech synthesizer with three distinct synthetic voices and multiple speech rates.

[GitHub](https://github.com/kingjr/meg-masc) –– [OSF](https://osf.io/ag3kj/) –– [Paper](
https://doi.org/10.48550/arXiv.2208.11488)

### LeBel Podcast Listening | fMRI

Deep data for 8 participants (language background undisclosed) who listen to multiple hours of natural, English-language stories from [The Moth Radio Hour](https://themoth.org/radio-hour) and the NYT Modern Love podcast during fMRI scanning. Extensive annotations for the podcast stimuli.

[GitHub](https://github.com/HuthLab/deep-fMRI-dataset) –– [OpenNeuro](https://openneuro.org/datasets/ds003020/versions/1.1.1) –– [Paper](https://doi.org/10.1038/s41597-023-02437-z)

### 'Narratives' (Nastase Natural Listening) | fMRI

A large dataset (345 participants!) listening to naturalistic audio while in fMRI scanning. Participants include both English L1 and English L2; stimuli are varied but all naturalistic English speech. Extensive annotations are available for the stimulus stories.

[OpenNeuro](https://openneuro.org/datasets/ds002345) –– [GitHub](https://github.com/snastase/narratives) –– [Datalad](https://datasets.datalad.org/?dir=/labs/hasson/narratives) –– [Paper](https://doi.org/10.1038/s41597-021-01033-3)

### Tang Pitch Listening | ECoG

A dataset of ECoG data from the superior temporal gyrus (STG) of 10 participants who listened to single English sentences with varied pitch contour, phonetic content, and synthesized speaker.

[Zenodo](https://doi.org/10.5281/zenodo.826950) –– [Paper](https://doi.org/10.1016/j.bandl.2020.104891)

### Brennan 'Alice in Wonderland' Listening | EEG

An EEG dataset of 49 participants listening to the first chapter of Alice's Adventures in Wonderland read in English. Participant language background was not disclosed. Dataset is also available in CND format from the CNSP.

[UMich Deep Blue](https://deepblue.lib.umich.edu/data/concern/data_sets/bn999738r) –– [CNSP](https://cnspworkshop.net/resources.html) –– [Paper](https://doi.org/10.1371/journal.pone.0207741)

### Das Auditory Attention | EEG

An EEG dataset of 16 participants who simultaneously listened to six-minute snippets of two stories read in Dutch. Competing stories were either presented separately in each ear or in the same stream using a head-related transfer function (HRTF). Participant language background was not disclosed. Dataset is also available in CND format from the CNSP.

[Zenodo](https://zenodo.org/record/3997352#.X0fP1sgza5g) –– [CNSP](https://cnspworkshop.net/resources.html) –– [Paper](https://doi.org/10.1088/1741-2560/13/5/056014)

### Cavanagh Oddballs | EEG

Two EEG datasets using a 3-stimulus oddball paradigm with two clinical populations:
* participants with minor traumatic brain injury (mTBI): sub-acute mTBI, n = 38; chronic sympatomatology, n = 23; healthy controls, n = 24
* Parkinson's (PD) patients: n = 25, plus equal number of well-matched controls

[Data:PD](https://unmm-my.sharepoint.com/personal/jcavanagh_unm_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fjcavanagh%5Funm%5Fedu%2FDocuments%2FPD%20Oddball%20Data&ga=1) –– [Paper:PD](https://doi.org/10.1016/j.clinph.2017.11.023) –– [Data:mTBI](https://unmm-my.sharepoint.com/personal/jcavanagh_unm_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fjcavanagh%5Funm%5Fedu%2FDocuments%2FmTBI%203AOB%20PreProc&ga=1) –– [Paper:mTBI](https://doi.org/10.1016%2Fj.neuropsychologia.2019.107125)

### Ershaid Cortical Tracking in Noise | EEG+Pupillometry

A dataset that includes EEG, pupillometry, self-reports of listening effort, and phonological and reading assessments for 49 Spanish-speaking participants. Stimuli sentences were presented in quiet or embedded in either multitalker babble ("cafeteria") or reverberation noise.

[OSF](https://osf.io/asn2k/) –– [Paper](https://doi.org/10.1016/j.cortex.2023.11.018)

### Issa Measures of Cortical Tracking of Speech | ECoG/EEG/MEG

A compilation of other datasets, using different methodologies and with stimuli in different languages, that the authors use to explore five different methods for extracting the speech envelope.

[OSF](https://osf.io/gtsa5/) –– [Paper](https://doi.org/10.1016/j.neuroimage.2024.120675)

### 'Baby Rhythms' Cortical Tracking in Infants of Nursery Rhymes | EEG

EEG was recorded from a longitudinal cohort of 50 infants (3 sessions) born in the United Kingdom, some exposed to a monolingual home environment and others a bilingual home environment, as the infants listened to eighteen nursery rhymes. Dataset is also available in CND format from the CNSP.

[OSF](https://osf.io/mdnwg/) –– [CNSP](https://cnspworkshop.net/resources.html) –– [Paper](https://doi.org/10.1038/s41467-023-43490-x)

### Kösem Speech Rhythms | MEG

An MEG dataset of 33 Dutch speakers listening to carrier sentences at two speeds (fast: 5.5 Hz; slow: 3 Hz) followed by a stable target window containing a target word that belongs to a minimal pair contrasting in vowel length.

[RadboudU](https://doi.org/10.34973/z05r-n179) –– [Paper](https://doi.org/10.1016/j.cub.2018.07.023)

### Kösem Vocoder Training | MEG

MEG and intelligibility data for 31 Dutch speakers who listened to 2-band and 4-band vocoded speech twice: once in a pre-training phase and then again after they were trained to listen to 4-band vocoded speech (post-training).

[RadboudU](https://doi.org/10.34973/qksk-6x25) –– [Paper](https://10.1016/j.neuroimage.2023.120040)

### MacIntyre Vocoded Sherlock Story | EEG

Data from 38 English speakers (with no experience in Dutch) who heard a Sherlock Holmes story in both languages across three vocoding conditions: unprocessed, 16-band, and 16-band with a decay slope.

[OSF](https://osf.io/czwj9/) –– [Paper](https://doi.org/10.1177/23312165241266316)

### Reetzke Mandarin Tone Learning | EEG (FFR)

Behavioral and neural data from 20 English L1 listeners trained to identify Mandarin lexical tones over the course of 4-13 days until their identification accuracy rivaled 13 Mandarin L1 listeners, then further trained for ten days and tested again eight weeks post-training.

[Mendeley-Behavior](https://data.mendeley.com/datasets/j2z2km4p9y/2) –– [Mendeley-Neural](https://data.mendeley.com/datasets/cvjjs4vdww/2) –– [Paper](https://doi.org/10.1016/j.cub.2018.03.026)

### Zada 'Podcast' Dataset | ECoG

Data from nine patients with cortical electrodes (grid array, linear strip, or depth electrodes) listening to a 30-minute podcast from "This American Life."

[OpenNeuro](https://openneuro.org/datasets/ds005574/versions/1.0.2)  –– [Paper](https://doi.org/10.1038/s41597-025-05462-2) –– [Tutorial](https://hassonlab.github.io/podcast-ecog-tutorials/html/index.html)

### Baus Tracking/N400 Dataset | EEG

Data from 22 English L1 listeners and 22 English L2 (Spanish/Catalan bilingual L1) listeners participating in two study tasks: an English listening task involving cortical tracking of syllabic, phrasal, and sentential elements and an English listening task involving semantic congruity (N400 effect).

[OSF](https://osf.io/e6z3s/) –– [Paper](https://doi.org/10.1162/nol_a_00141)

### VocalMind Dataset | sEEG

Data from a single participant performing three study tasks: overt speech, covert speech, and imagined reading, all in Mandarin Chinese.

[Zenodo](https://zenodo.org/records/14696348) –– [GitHub](https://github.com/tianyu-h42/sEEG-Processing-SpeechDecoding) –– [Paper](https://doi.org/10.1038/s41597-025-04741-2)

### Amoruso Social Verbs Dataset | MEG

Data and analysis code from 14 participants performing a lexical decision task with social verbs, nonsocial verbs, and pseudoverbs.

[OSF](https://osf.io/j6r2t/) –– [Paper](https://doi.org/10.1093/scan/nsae066)

# Tutorials

Many amazing scientists have created useful (and free!) tutorials to do, well, just about anything. This is a collection of tutorials that I have found particularly useful for learning skills that support my neurolinguistic research.

### Programming with Software Carpentry

The most common programming languages for neurolinguistic data analysis are MATLAB and Python. Python and R are widely used in acoustics. R is popular for statistical modeling while Python is considered top-of-class for machine learning. With these three languages, a neurolinguist has a broad foundation on which to explore and analyze data. (Note: R and Python are both free to download and install. For MATLAB, you may have access through your institution. The actual tutorials below are free.)

[R](https://swcarpentry.github.io/r-novice-gapminder/) –– [Python](https://swcarpentry.github.io/python-novice-inflammation/) –– [MATLAB](http://swcarpentry.github.io/matlab-novice-inflammation/)

### Signal Processing with Mike X. Cohen

[Cohen](https://mikexcohen.com/) is the master of time-series data analysis. He has multiple books and Udemy courses, as well as a plethora of freely-available tutorials on YouTube (with accompanying code available on GitHub!).

[YouTube](https://www.youtube.com/@mikexcohen1) –– [GitHub](https://github.com/mikexcohen)

### EEG Preprocessing + Simple ERPs

A series of informal trainings led by [Dr. George Buzzell](https://www.ndclab.com/) using the [MADE](https://github.com/ChildDevLab/MADE-EEG-preprocessing-pipeline) preprocessing pipeline to prepare EEG data for analysis. Use the readmes in 2021 and 2022 (in order) to access video links and materials.

[GitHub](https://github.com/NDCLab/lab-training/tree/main/eeg-analysis)

### Linear Mixed Effects Modeling for Linguistics

Two very straightforward tutorials on the basics of mixed effects modeling by cognitive linguist [Dr. Bodo Winter](https://bodowinter.com/). An excellent place to start for mixed effects modeling.

[Paper + Tutorial](http://arxiv.org/pdf/1308.5499.pdf)

### Neuromatch Computational Neuroscience

A thousand tutorials in one! The Neuromatch team makes their annual, three-week intensive course freely available, with videos and hands-on tutorials using Jupyter notebooks in either Google Colab or Kaggle. Ignore the "Projects" part (which is only for summer participants), and start with W0D0 (Week 0, Day 0).

[Website](https://compneuro.neuromatch.io/tutorials/intro.html)

### Statquest

Dr. Josh Starmer's hilarious, accessible videos can help you work through any statistical confusion.

[YouTube](https://www.youtube.com/@statquest) –– [Website](https://statquest.org/)

### 3Blue1Brown

Sometimes, you just need a visual. Grant Anderson's videos will change how you view linear algebra and calculus forever.

[Website](https://www.3blue1brown.com/#lessons)

### HarvardX Fundamentals of Neuroscience

This is a series of three online courses (free if you select the Audit Track) that offers an excellent introduction to the basics of neuroscience, including the biochemistry of how neurons work, how they function as ensembles, and how they combine to the make the brain.

[Website](https://www.edx.org/xseries/harvardx-fundamentals-of-neuroscience)


* * *

* * *

Got suggestions? Head over to the GitHub repo (red button on the left) and create a new issue!