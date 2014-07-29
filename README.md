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

#### Updated the README

#### Cleaned the output

Original output:

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

#### Installation 

I use macports, so my preferred bin storage is `/opt/local/bin/`, choose yours: if it is in $PATH is ok.

Clone the repo:

    > git clone https://github.com/kidpixo/dict.cc.py.git

Make sure it is executable by you

    > ls -l 
    -rwxr-xr-x  1 USER  GROUP  2.9K Jul 29 13:07 dict.cc.py

if not, make it executable
    chmod u+x dict.cc.py

soft-link the executable to some place in your `$PATH`

    sudo ln -s ~/Downloads/dict.cc.py/dict.cc.py /opt/local/bin/dictcc

After that, usage is simply

    > dictcc en it attraverso

## License

Public domain.