Short list where the files are from.

All files are cut so only the first trace appears to save disk space.


SEG Y rev 1 files
=================

http://statcomltd.com/segyview.html
-----------------------------------
    => 2-byte, two's complement integer - big endian, EBCDIC header.

        example.y_first_trace


http://gdr.nrcan.gc.ca/seismtlitho/archive/ag/stacks_e.php
----------------------------------------------------------
    => 4-byte, IBM floating point - big endian, EBCDIC header.

        ld0042_file_00018.sgy_first_trace


Thomas.Forbriger@kit.edu
------------------------
    => 4-byte, two's complement integer - big endian, ASCII header.

        1.sgy_first_trace

LIAG data from Tobias Megies
----------------------------
    => 4-byte, IBM floating point - little endian, ASCII header.

        00001034.sgy_first_trace

Files from Christian Pelties
----------------------------
    => 4-byte, IBM floating point - little endian, EBCDIC header.

        planes.segy_first_trace

Files from Eric Eckert
----------------------------
    => 4-byte, IBM floating point - little endian, ASCII header.
    3 block containing a simple sin wave
    3rd block header contains contains two extra bytes at 137536
    to simulate the kind of corruption that frequently occurs in
    large segy files
    
    corrupt_sin_wave.sgy
    
    => 4-byte, IBM floating point - little endian, ASCII header.
    The non corrupt version of the corrupt.segy. Contains 3 blocks
    with a sin wave.
    
    good_sin_wave.sgy
    
Seismic Unix files
==================

Thomas.Forbriger@kit.edu
------------------------
    => 4-byte IEEE floating point - little endian

        1.su_first_trace
