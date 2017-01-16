# PerlPrimer

PerlPrimer is a free, open-source GUI application written in Perl that designs primers for standard PCR, bisulphite PCR, real-time PCR (QPCR) and sequencing. It aims to automate and simplify the process of primer design.

PerlPrimer's current features include the following:

* Calculation of possible primer-dimers
* Retrieval of genomic or cdna sequences from Ensembl (including both sequences automatically for QPCR)
* Ability to BLAST search primers using the NCBI server or a local server
* Results can be saved or optionally exported in a tab-delimited format that is compatible with most spreadsheet applications.
* ORF and CpG island detection algorithms
* Ability to add cloning sequences to primers, automatically adjusted to be in-frame
* QPCR primer design without manual intron-exon boundary entry 

PerlPrimer calculates primer melting temperature using J. SantaLucia's extensive nearest-neighbour thermodynamic parameters. To adjust for the salt conditions of the PCR, PerlPrimer uses the empirical formula derived by von Ahsen, et al. (2001) and allows the user to specify the concentration of Mg2+, dNTPs and primers, or use standard PCR conditions. The result is a highly accurate prediction of primer melting temperature, giving rise to a maximum yeild of product when amplified.

PerlPrimer is written in Perl and Perl/Tk. In addition, for QPCR functionality PerlPrimer uses the open-source Spidey executable from NCBI, and restriction enzyme data from the REBASE project is used when adding cloning sites. The program is designed to be cross-platform compatible and has been developed and tested on both Microsoft Windows and GNU/Linux-based operating systems. Users have also reported success using the program under Mac OS X.

Please cite the reference below if this program is useful.

    Marshall OJ. PerlPrimer: cross-platform, graphical primer design for standard, bisulphite and real-time PCR. Bioinformatics 2004 20(15):2471-2472 [Pubmed]


