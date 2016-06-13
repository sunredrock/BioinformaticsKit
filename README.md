# BioinformaticsKit
A bioinformatics kit that could be process many file format and complet many trivial function in a simple way. It's portable, standalone, editable.

# Usage
1. uncompressing file

2. cd BioinfomaticsKit-v0.1

3. perl biokit-20160505.pl

        Basic package
                SummaryDB => summary database to one file.
                Position  => given one chromosome position,show reads stairs
                BestBlast => choose the best hit from blast aligning result
                ParallelRun => run scripts by parallel

        Fasta process package
                SequenceLength
                SplitFasta => split fasta file by record or by line
                DnaToRna => convert DNA Sequence to RNA Sequence
                ReverseComplement => reverse complement of a DNA Sequence
                FaStat  => count base statistics and CpGs in fasta files
                Fa2Fq   => Convert fa to fastq format

        Fastq process package
                FastqToFasta
                FilteringV1   => Quality control of NGS data. Less feature
                FilteringV2   => Quality control of NGS data. More feature

        Bam process package
                BamToFasta
                BamToFastq
                BamStat
                BamTargetStat

        Bed region process package
                BedSize

        DNApipeV1  => Best practiced pipeline by Bwa + samtools + GATK analysis pipeline. Only caled SNP and Indel.

# Contact
sunredrock@foxmail.com

