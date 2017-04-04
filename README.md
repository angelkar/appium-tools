# appium-tools
Appium dependencies and tools

## Setup
Run the following commands:

```
npm install
npm run build
```

## Install additional iOS specific dependencies
```
gem install xcpretty
brew install ideviceinstaller
brew install carthage
```
## Error with ios-deploy?
According to this [issue](https://github.com/phonegap/ios-deploy/issues/109) you have to run 
```
sudo npm install --global --unsafe-perm ios-deploy
```
