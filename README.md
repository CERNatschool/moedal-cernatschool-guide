# The CERN@school Programme: A Guide to MoEDAL

This repository contains all of the LaTeX code needed to generate
the [CERN@school programme's guide to the MoEDAL experiment](http://doi.org/10.5281/zenodo.248615).
Please refer to this document for more information about MoEDAL,
the LHC, CERN and the Institute for Research in Schools.

## Getting the images

Thanks to the Creative Commons licensing system,
most of the images required to make this document can be hosted on
the GitHub repository. However, you will need to download two
images from the CERN Document Server (CDS):

* The LHC aerial view - see `assets/images/lhc/README.md`
* The Standard Model of particle physics - see `assets/images/sm/README.md`

for further instructions.


## Generating the document

Once you have the correct images in the relevant directories,
you can generate the PDF of this document using the following command:

```bash
$ source process.sh
```


## Licenses

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>
<br />
Except where otherwise noted, this work is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
Please refer to individual figures, tables, etc. for further information
about licensing and re-use of other content.

All software in this repository is covered by the MIT license (see `LICENSE`)
apart from the TeX `*.sty`, `*.srt`, `*.clo` and `*.cls` files - please refer to the
relevant files themselves for more information regarding these.

## Acknowledgements

This work was kindly supported by the UK Science and Technology Facilities Council (STFC) 
via grant numbers ST/J000256/1 and ST/N00101X/1,
as well as a Special Award from the Royal Commission for the Exhibition of 1851.


## Useful links

* [The document itself (v1.0)](http://doi.org/10.5281/zenodo.248615)
* [The Institute for Research in Schools](http://researchinschools.org)
* [CERN@school on the IRIS website](http://researchinschools.org/CERN)
* [The MoEDAL experiment](http://moedal.web.cern.ch)
* [The CERN@school MoEDAL bibliography](http://doi.org/10.5281/zenodo.193038) (for further reading)
