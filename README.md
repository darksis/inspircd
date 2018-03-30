# inspircd
inspircd build by Sender with all modules run in FreeBsd systems home and ports
the commands By Sender
mkdir inspircd_build
cd inspircd_build
fetch -o build.sh http://termbin.com/2g1mf
fetch -o fetch.sh  http://termbin.com/3gpw
fetch -o extract.sh  http://termbin.com/sxa2
chmod +x build.sh
chmod +x fetch.sh
chmod +x extract.sh
mkdir distfiles
fetch -o distfiles/inspircd-2.0.24.tar.gz https://github.com/inspircd/inspircd/archive/v2.0.24.tar.gz
./fetch.sh
./extract.sh
./build.sh
