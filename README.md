# story-install
wget -q -O story.sh https://api.nodes.guru/story.sh && sudo chmod +x story.sh && ./story.sh
cd $HOME/.story
story validator create --stake 1000000000000000000
sudo journalctl -u story -f
sudo journalctl -u story-geth -f
