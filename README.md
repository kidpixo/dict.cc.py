# dict.cc.py

Unofficial command line client for dict.cc. 

It supports all languages dict.cc uses, use the dict.cc language tokens (e.g. EN for English, DE for German, FR for French or SV for Swedish).

## Usage

    > $ python dict.cc.py en sv beer
    > dict.cc.py:
    > EN to SV: beer 
    > öl.....................beer
    > ölglas.................beer glass
    > veteöl.................wheat beer

Or add it to your path:

    > $ chmod +x dict.cc.py
    > $ sudo cp dict.cc.py /usr/bin/
    > $ dict.cc.py human body
    > (Same results as above)

## This Version Mods

Updated the README and cleaned the output from 

    dict.cc.py:

    EN to IT: attraverso

    attraverso..............................across
    attraverso..............................over
    attraverso..............................through
    [ limited result set  ].................[ limitierte Ergebnisliste ]
    [ more at www.dict.cc ].................[ mehr unter www.dict.cc   ]
    [ in your web browser ].................[ in Deinem Web-Browser    ]

to 

    EN to IT: attraverso
       attraverso.......across
       attraverso.......over
       attraverso.......through

## License

Public domain.