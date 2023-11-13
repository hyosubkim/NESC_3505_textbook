# Introduction to EEG/ERP Data

EEG, or **electroencephalography**, is a technique that records electrical activity from the brain. Typically, it is recorded non-invasively, from electrodes placed on the scalp, although it can also be recorded from electrodes placed directly on the surface of the brain (typically for clinical neurological purposes). EEG typically involves the use of between 1–250 electrodes; even at the upper end of that range, clearly there are far fewer electrodes than the estimated 80 billion or so neurons in the brain. As well, the skull is a poor conductor of electricity. This means that what we record with EEG is inevitably the aggregated activity of large numbers of neurons working together.

The image below shows an example of an EEG system. The person is wearing an EEG cap with electrodes plugged into it. The wires from the electrodes lead to the amplifier, which transmits the data to a computer for storage. The screen on the left presents stimuli to the person, while the screen on the right shows the EEG data in real time. Image courtesy [Brain Vision LLC](https://brainvision.com/).


```{image} images/EEG_system.jpg
:alt: An EEG system
:width: 400px
:align: center
```

EEG can be a bit challenging for people to get their heads around at first, because there are some non-intuitive features of the data. One of the most important considerations is that EEG is not a good technique for localizing where activity occurs in the brain. Because the electrodes are placed on the outside of the scalp, and because the brain and its encasing cerebrospinal fluid are very good electrical conductors, a signal that originates in one location in the brain will propagate throughout the brain. In other words, in principle any signal inside the brain should be detectable by an electrode placed anywhere on the outside of the brain. Add to this consideration of the fact that, inevitably, many brain areas will be active simultaneously (or in rapid but overlapping succession), and it becomes clear that any signal recorded outside the scalp is a mixture of the signals from all active parts of the brain — at least, those that generate a strong and coherent enough signal to pass through the poorly-conducting skull. For this reason, **source localization** with EEG is described as an **inverse problem** (finding the sources on the inside, given the data from the outside, of the head). Mathematically, the inverse problem is **ill-posed**, meaning that there are essentially an infinite number of possible solutions. This is not to say source localization is always impossible. Indeed, it can work quite well, especially for signals like early sensory responses, where the location of the neural generators of the signal are focal and well-known (e.g., primary visual or auditory cortex). However, the best and most widely-employed uses of EEG focus on the signals as they are recorded on the scalp. Decades of research have provided a substantial evidence base relating particular EEG signals to particular cognitive functions or tasks, and so a primary use of EEG is to identify if, and/or how strongly, one or more of these signals occurs during a task (and/or how the signals differ between task conditions). We'll elaborate on these points in the sections that follow.

The image below shows a 5 s sample of continuous, raw EEG data. Each horizontal trace is the data from one electrode (channel). The large deflections, particularly evident in channel Fp2, are artifacts caused by eye blinks. The coloured vertical lines, which have labels at the top, represent specific events of experimental interest (e.g., stimulus onsets or participant responses).


```{image} images/eeg_raw_continuous.jpg
:alt: Sample EEG data
:width: 400px
:align: center
```

One important distinction between EEG and other types of data we have worked with so far is that EEG is recorded as a **continuous**, time-varying signal. This means the data are a **time series**. Although some of the single unit data we have seen before was stored in a time series (i.e., regularly-spaced data points over time), the signal was not continuous but rather discrete. That is, in single unit data, each time point could only be 0 (no spike) or 1 (spike). In contrast, EEG is recorded as electrical potential (voltage), which varies continuously (e.g., voltage could be 0, or 0.0001, or 10.352, or -82.43, etc.). EEG data also typically include a spatial dimension, because the electrodes are placed across the scalp and different electrodes will detect different signals depending on their location.
