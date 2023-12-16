---
weight: 2
date: ""
title: "Timing"
image: "timing.png"
alt: "Timing of Nina and Camden's recordings versus Mariah Carrey"
color: "#0a1922"
---
The timing checks how behind/ahead/on-tempo the singer is.
It works by finding wavelengths of the original song and the karaoke cover of the person singing.
Then it takes an x correlation on the two signals to find lag. This is done using the function xcorr, which takes two signals, and finds the similarity between the two, then repeatedly shifts one of the signals until the highest correlation is found. This is then index for max(coeff).
Then shift the original signal by that amount and move on to noise removal.