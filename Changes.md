# Changes being added

## v1.4
- Updated the annoation steps to [Pharokka](https://github.com/gbouras13/pharokka), [Phold](https://github.com/gbouras13/phold) and then [Phynteny](https://github.com/susiegriggo/Phynteny)
- Also updated the summary file to confirm the presence/absence of specific genes from the annotation outputs
- Updated Readme

## Upto v1.3.4
Sphae can be run on illumina reads and nanopore reads
- Quality control - [trimnami](https://github.com/beardymcjohnface/Trimnami)
- Assembly - [Megahit](https://github.com/voutcn/megahit) for Illumina reads and [Flye](https://github.com/fenderglass/Flye) + [Medaka](https://github.com/nanoporetech/medaka) for Nanopore reads
  Post assembly the reads are run through [CheckV](https://bitbucket.org/berkeleylab/CheckV/src), [viraverify](https://github.com/ablab/viralVerify) and looking into graph connection to confirm the genome is assembled 
- Annotation - [Pharokka](https://github.com/gbouras13/pharokka) followed by [Phynteny](https://github.com/susiegriggo/Phynteny)
- Generate a summary report file