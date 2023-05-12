#!/bin/bash

cd EPG && wget -N https://github.com/XMLTV/xmltv/raw/master/grab/pt_meo/tv_grab_pt_meo && perl tv_grab_pt_meo --config-file meo-pt.conf --output epg-meo-pt.xml && gzip -v9 -c epg-meo-pt.xml > epg-meo-pt.xml.gz

exit 0
