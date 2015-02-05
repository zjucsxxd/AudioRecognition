Music/Audio Recognition Application written in C++
===============================================

Features:
-----
    * Robust Audio Recognition
    * High efficiency (recognize in less than 0.1 second per song)
    * Memory reduction ( 4G is enough for 10000 songs)
    * The Data Structure now support 2,500,000 songs and each song less than 7 minutes.
    * return the TIME POINT of the cut song in original song.

Dependencies:
-----
    * fftw3:
        If under Debian/Ubuntu, run `apt-get install libfftw3-dev`.

Compile & Run:
-----
    * extract songs to ./bin/ dir.
    * `make` to produce two excutive files in ./bin/ 
    * The songs should be .wav format.
    * The songs should be contained in ./bin/samples/ 
    * You may download the songs.
        link: 
        password:
    * run `cd bin`, `./build` and it'll produce a file called `database`
    * run `./recog ${filename}` to recog the songs that in samples list.

TODO:
-----
   - Docs

DONE:
-----
   - All the codes in Windows.
   - Transfer the codes from windows to linux.
   - Solve the BaiduMusic download tools to update new songs automatically.

At the begining, it's a COMPETITION. My partner and I finshed this project on Windows8 and won the *First Prize* delivered by [National Engineering Laboratory for Speech and Language Informatinon Processing](http://nelslip.ustc.edu.cn/html/yunews/detail_2014_05/30/191.shtml).
Feel free to contact me yjh199511 at gmail
