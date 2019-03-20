# account_snapshot_plugin

## Building
```
# clone git repo
mkdir ~/build && cd ~/build
git clone https://github.com/deckb/account_snapshot_plugin

# change directory to eos github repo and run
# if prior to 1.7.0 run:
LOCAL_CMAKE_FLAGS="-DEOSIO_ADDITIONAL_PLUGINS=~/build/account_snapshot_plugin" ./eosio_build.sh
# post 1.7.0 run:
LOCAL_CMAKE_FLAGS="-DEOSIO_ADDITIONAL_PLUGINS=~/build/account_snapshot_plugin" ./scripts/eosio_build.sh
```