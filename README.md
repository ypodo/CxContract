# CxContract
VMware contract system

## Create Ruby Rails dev enviorment
sudo apt update
sudo apt install git vim curl -y    
gpg --keyserver hkp://pool.sks-keyservers.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
\curl -sSL https://get.rvm.io | bash -s stable --gems=rails,puma
21  \curl -sSL https://get.rvm.io | bash -s stable --rails
mkdir CxContract
cd CxContract/
rail new app   
source /home/yuris/.rvm/scripts/rvm   
sudo apt install nodejs   
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn
gem install ruby-debug-ide
bundle install
rails webpacker:install

# rails webpacker:install
