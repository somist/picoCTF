  <p align="center"><img src="../../images/like1000_0.png" ></p>

A simple challenge that can be time consuming unless you decide to write code that will do all the extracting for you. Initial 1000.tar archive contains 999.tar archive which contains 998.tar archive and so on, meaning we have 1000 archives to extract. Hint suggested writing a script so that's exactly what I did. It's just a simple for-loop, where every loop assigns name of the archive to variable $f (decrementing every loop), extracts contents of archive using 'tar xf <filename>' and removes the archive we no longer need. At the end we also delete filler.txt file that was initially extracted from 1000.tar archive and we are left with flag.png:

<p align="center"><img src="../../images/like1000_1.png" ></p>
