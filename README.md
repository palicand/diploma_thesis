# Diploma Thesis on FIT CTU

## Official aims of the thesis

The current archive of the LAMOST telescope contains about 4 million of astronomical spectra. The goal of
the thesis is to identify objects with interesting spectral line profiles (namely emission line stars) based on a
small set of examples.

1. Make a survey of semi-supervised training methods and define the optimal strategy of learning, taking
  into consideration massively parallel solutions (e.g., SPARK, GPUs...).
2. Select spectra of known emission-line stars from archives of the Ondřejov 2m telescope.
3. Make a positional cross-match of objects from 2) with LAMOST survey to get a sample for training.
4. If the sample obtained in 3) is insufficient, simulate the expected appearance of spectra from 2) in the
  LAMOST spectrograph to get a training sample.
5. Identify new objects of the same class in the whole LAMOST survey and make visual confirmation.
6. Discuss the success rate and computing performance of your strategy.
  Try to integrate your solution into the system VO-CLOUD.