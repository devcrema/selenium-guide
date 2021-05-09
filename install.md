# install selenium

## install brew
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## install python3
```shell
brew install python3
```

## pip upgrade
```shell
pip3 install --upgrade --force pip
```

## install chrome driver
```shell
brew install --cask chromedriver
```

## set permission
```shell
xattr -d com.apple.quarantine /usr/local/bin/chromedriver
```

## install firefox driver
```shell
brew install geckodriver
```

## instal selenium
```shell
pip install selenium
```

## chrome이 없을 경우
```shell
brew install --cask google-chrome
```

## firefox가 없을 경우
```shell
brew install --cask firefox
```
