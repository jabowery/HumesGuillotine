## The Laboratory of the Counties Social Causality Contest

The objective is to optimally compress the ecological social data described below.

The file to be compressed, `LaboratoryOfTheCountiesUncompressed.csv`, contains all the
numeric data from [USA Counties Data File
Downloads](https://www.census.gov/support/USACdataDownloads.html)
provided by CenStats of the US Census as of June 4, 2017. The file, `Ref.zip`,
contains the reference information (metadata) for
`LaboratoryOfTheCountiesUncompressed.csv`.

The rules for this, the first in
a series of Ockham's Guillotine contests, are modeled after [the rules
of the Huter Prize for Lossless Compression of Human
Knowledge](http://prize.hutter1.net/hrules.htm):

-   Publish a program (self-extracting archive)
    `LaboratoryOfTheCountiesCompressed`.
-   If run, it produces a file that is identical to
    `LaboratoryOfTheCountiesUncompressed.csv`.
-   Programs must be Linux (x86 32bit or 64bit) executables.
-   Programs must run without input from other sources (files, network,
    dictionaries, etc.) on Linux without additional
    installations.
     Use of standard libraries as for file I/O are allowed.
-   Use of less than 4GB RAM and 10GB HD for temporary files. No GPU usage. Programs must run in less than 20 hours real
    time on [our test
    machine](https://browser.primatelabs.com/geekbench4/search), where
    *T* is its [Geekbench4](http://geekbench.com/geekbench4/) score.
    Current machine (as of 2017, which may change without notice) is a
    Dell Latitude E6510 Intel Core i7-620M 2667 MHz with 64bit Linux
    with [*T*=2441 (1 core) and *T*=4336 (2
    cores)](https://browser.primatelabs.com/v4/cpu/145066).

### Relaxations

-   In lieu of a self-extracting archive, a decompressor program
    `decompLotC` plus a compressed file
    `LaboratoryOfTheCountiesCompressed.bhm` may be published, where
    `decompLotC` produces `LaboratoryOfTheCountiesUncompressed.csv` from
    `LaboratoryOfTheCountiesCompressed.bhm`. In this case, the total
    size is :=
    length(`decompLotC`)+length(`LaboratoryOfTheCountiesCompressed.bhm`).
-   In lieu of `LaboratoryOfTheCountiesCompressed`, a compressor
    `compLotC` may be published, together with the size of
    `LaboratoryOfTheCountiesCompressed` (and any options used to create
    it), which creates `LaboratoryOfTheCountiesCompressed` from
    `LaboratoryOfTheCountiesUncompressed.csv`.
-   Resource restrictions for the (de)compressor are the same as for the
    self-extracting archive.
-   The used filenames (except LaboratoryOfTheCountiesUncompressed.csv)
    are just for illustration.

### Participation

Anyone may participate at this contest by emailing the following
information to jabowery@gmail.com:

-   Name of program(s), version, and used options.
-   Size of compressed `LaboratoryOfTheCountiesUncompressed.csv`, i.e.
    of `LaboratoryOfTheCountiesCompressed` or
    `decompLotC`+`LaboratoryOfTheCountiesCompressed.bhm`.
-   Approximate (de)compression time and memory used.
-   Description of the test machine (processor, memory, operating
    system).
-   Links where files can be downloaded:
     Executables and documented source code of (de)compressor and all
    other relevant files.
-   Usage/compilation instructions.

Any additional information, even if not complete, especially on the
inner workings of the (de)compressor, is highly appreciated.

### Award

The prize is recognition that you have the best unified model of US society.  If there are those who wish to award prizes for incremental improvements in this model, they may make announcements of such at [the Ockham's Guillotine Google Group](https://groups.google.com/forum/#!forum/ockhams-guillotine).
