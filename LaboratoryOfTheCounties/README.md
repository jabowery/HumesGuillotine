The Laboratory of the Counties Social Causality Contest


The file to be compressed, LaboratoryOfTheCountiesUncompressed.csv, contains all the numeric data from <a href="https://www.census.gov/support/USACdataDownloads.html">USA Counties Data File Downloads</a> provided by the US Census as of June 4, 2017.
The file, Ref.zip, contains the reference information (metadata) for LaboratoryOfTheCountiesUncompressed.csv

The rules of this, the first in a series of Ockham's Guillotine contests, are modeled after <a href="http://prize.hutter1.net/hrules.htm">the rules of the Huter Prize for Lossless Compression of Human Knowledge</a> with the <u>underline</u>-indicated modifications: 


    <UL>

      <LI>Publish a program (self-extracting archive) <TT>LaboratoryOfTheCountiesCompressed</TT> of

        size <I>S</I>. </LI>

      <LI>If run, it produces a file that is identical to <TT>LaboratoryOfTheCountiesUncompressed.csv</TT>. </LI>

      <LI>Programs must be Linux (x86 32bit or 64bit) executables. </LI>

      <LI>Programs must run without input from other sources (files, network,

        dictionaries, etc.) under Windows or Linux without additional

        installations.<br> Use of standard libraries as for file I/O are allowed.

      </LI>

      <LI> Use of of less than <u>4</u>GB RAM and 10GB HD for temporary files is still required. No GPU usage.

             Programs must run in less than <u>20</u> hours real time on <a href="https://browser.primatelabs.com/geekbench4/search">our test machine</a>,

             where <i>T</i> is its <a href="http://geekbench.com/geekbench4/">Geekbench4</a> score.

             Current machine (as of 2017, which may change without notice) is a Dell Latitude E6510 Intel Core i7-620M 2667 MHz with 64bit Linux

             with <a href="https://browser.primatelabs.com/v4/cpu/145066"><i>T</i>=2441 (1 core)  and <i>T</i>=4336 (2 cores)</a>.

    </UL>



<!-- ============================== -->

<A NAME="relax"><H3>Relaxations</H3></A>

<!-- ============================== -->



    <UL>

      <LI>In lieu of a self-extracting archive, a decompressor program <TT>decompLotC</TT>

        plus a compressed file <TT>LaboratoryOfTheCountiesCompressed.bhm</TT> may be published, where

<!-- Given command line option <tt>opt</tt>, -->

        <TT>decompLotC</TT> produces <TT>LaboratoryOfTheCountiesUncompressed.csv</TT> from <TT>LaboratoryOfTheCountiesCompressed.bhm</TT>.

        In this case, the total size is <I>S</I> := length(<TT>decompLotC</TT>)+length(<TT>LaboratoryOfTheCountiesCompressed.bhm</TT>).

      </LI>

      <LI>In lieu of <TT>LaboratoryOfTheCountiesCompressed</TT>, a compressor <TT>compLotC</TT> may

        be published, together with the size of <TT>LaboratoryOfTheCountiesCompressed</TT> (and any

        options used to create it), which creates <TT>LaboratoryOfTheCountiesCompressed</TT> from <TT>LaboratoryOfTheCountiesUncompressed.csv</TT>.

      </LI>

      <LI>Resource restrictions for the (de)compressor are the same as for the

        self-extracting archive. </LI>

      <LI>The used filenames (except LaboratoryOfTheCountiesUncompressed.csv) are just for illustration. </LI>

    </UL>



<!-- ============================== -->

<A NAME="part"><H3>Participation</H3></A>

<!-- ============================== -->



    Anyone may participate at this contest by emailing the following

    information to jabowery signforat gee male daught kahm:

    <UL>

      <LI>Name of program(s), version, and used options. </LI>

      <LI>Size of compressed <TT>LaboratoryOfTheCountiesUncompressed.csv</TT>, i.e. of <TT>LaboratoryOfTheCountiesCompressed</TT>

        or <TT>decompLotC</TT>+<TT>LaboratoryOfTheCountiesCompressed.bhm</TT>. </LI>

      <LI>Approximate (de)compression time and memory used. </LI>

      <LI>Description of the test machine (processor, memory, operating system). </LI>

      <LI>Links where files can be downloaded:<br>

             Executables and documented source code of (de)compressor and all other relevant files.</LI>

      <LI>Usage/compilation instructions.</LI>

    </UL>



    Any additional information, even if not complete, especially on the

    inner workings of the (de)compressor, is highly appreciated. <A NAME="award"></A>


