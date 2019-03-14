# CHM2PDF

(c) 2007 Massimo Sandal <devicerandom@gmail.com>

(c) 2007-2008 Chris Karakas <http://www.karakas-online.de> and <chris@karakas-online.de>

A Python script that converts a CHM file into a single PDF file.

Usage:
  `chm2pdf [options] input_filename [output_filename]`

For all option see
  `chm2pdf --help`

### RECOMMENDED READING:
 - <http://www.karakas-online.de/forum/viewtopic.php?t=10275>
 - <http://www.karakas-online.de/forum/viewtopic.php?t=10969>


### Installation:
 1. download the .tar.gz
 2. unzip it: "tar -xzvf chm2pdf-a.b.c.tar.gz"
 3. enter the newly created directory
 4. acquire root privileges
 5. type "python setup.py install"

### Requires:
 - python
 - chmlib. *NOTE:* chmlib **must** be configured with `./configure --enable-examples`
 - pychm
 - htmldoc

#### Optional:
 - BeautifulSoup

All of these should be in your Linux/Unix distribution repository :smiley:
