# macos_ansible

## Usage

- Install Xcode from AppStore

  - `sudo xcodebuild -license`
  - `xcode-select --install`

- Install Homebrew

  - `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
  - `brew doctor`
  - `brew update`

- Install ansible

  - `brew install ansible`

- gitclone

  - `brew install git`
  - `git clone git@github.com:yosuke0315/dotfiles.git` (Follow the [Readme.md](https://github.com/yosuke0315/dotfiles/blob/master/README.md))
  - `git clone git@github.com:yosuke0315/macos_ansible.git`

- provisioning

  - `HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts -vv localhost.yml`

- Install DataBase

  - DB version controll is complex, so do manual Installation
  - mysql
  - postgresql
