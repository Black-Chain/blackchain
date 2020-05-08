Necessary dependencies for deamon blackchaind:
================================

sudo apt-get install libboost-all-dev -y && sudo ln -s libboost_iostreams.so.1.65.1 libboost_iostreams.so.1.60.0
sudo apt-get install libdb5.3++-dev -y
sudo apt-get install -y miniupnpc libminiupnpc-dev -y

./blackchaind -deamon


