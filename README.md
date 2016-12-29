# macos_ansible

Reference is [t-wada's Blog](http://t-wada.hatenablog.jp/entry/mac-provisioning-by-ansible)

## Usage

- Install Xcode from AppStore
  - ```sudo xcodebuild -license```
  - ```xcode-select --install```
- install Homebrew
  - ```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```
  - ```brew doctor```
  - ```brew update```
- Install ansible
  - ```brew install ansible```
- gitclone
  - ```brew install git```
  - ```git clone git@github.com:yosuke0315/macos_ansible.git```
- provisioning
  - ```HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts -vv localhost.yml```
- Install DataBase
  - DB version controll is complex, so do manual Installation
  - mysql
  - postgresql
