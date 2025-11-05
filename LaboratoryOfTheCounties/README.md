## The Laboratory of the Counties Social Causality Contest

The objective is to optimally compress the ecological social data described below.

See "[Cell Trajectory Inference Based On Single Cell Stacked Auto Encoders](https://dl.acm.org/doi/10.1145/3757749.3757796)" for only one of the ways that developmental dynamics can be latent in data even without an explicit time axis.

The file to be compressed, `LaboratoryOfTheCountiesUncompressed.csv`, contains all the
numeric data from [USA Counties Data File
Downloads](https://www.census.gov/library/publications/2011/compendia/usa-counties-2011.html)
provided by CenStats of the US Census as of June 4, 2017. Data is being added on an ongoing basis as new sources are acquired.  For example, data from Patchwork Nation is currently being cleaned and will be added.  See the 'patchworknation' subdirectory.
The file, `Ref.zip`, contains the reference information (metadata) for
`LaboratoryOfTheCountiesUncompressed.csv`.

The rules for this, the first in
a series of Hume's Guillotine contests, are modeled after [the rules
of the Huter Prize for Lossless Compression of Human
Knowledge](http://prize.hutter1.net/hrules.htm):

-   Publish a program (self-extracting archive)
    `LaboratoryOfTheCountiesCompressed`.
-   If run, it produces a file that is identical to the most recent version of 
    `LaboratoryOfTheCountiesUncompressed.csv`.
-   Programs must be Linux (x86 32bit or 64bit) executables.
-   Programs must run without input from other sources (files, network,
    dictionaries, etc.) on Linux without additional
    installations.
     Use of standard libraries as for file I/O are allowed.
-   Use of less than 4GB RAM and 50GB HD for temporary files. No GPU usage. Programs must run in less than 20 hours real
    time on [our test machine](https://browser.geekbench.com/user/280257)).

### Relaxations

-   The decompressed `LaboratoryOfTheCounties.csv` need match only the
    number of significant digits in the original values.  This will be
    determined by taking the decompressed values and rounding them to the
    number of significant digits in the original values.
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

