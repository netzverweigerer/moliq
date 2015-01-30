# moliq
moliq: mopidy liquidsoap extension, forked from gist: dz0ny / mopidy.liq

1. Install liquidsoap from your distribution repo: apt-get install liquidsoap
2. Save moliq
3. Open terminal and write liquidsoap then drag and drop moliq script to terminal and press ENTER
4. Open mopidy config file and change output line to output = shout2send mount=input ip=127.0.0.1 port=8800 password=changeme
5. Restart mopidy and open in any player URL "http://{IP address assigned to device}:8800/mopidy"


