# pod_commands

```bash
# Showing Recent Messages
# Unable to load contents of file list: '/Users/paige/Desktop/company/Pluviophile/DRDozy_SwiftUI/SleepWave/Pods/Target Support Files/Pods-SleepWave/Pods-SleepWave-frameworks-Real Release-output-files.xcfilelist'
sudo gem update cocoapods --pre
pod update

# Other ways
# delete 'Pods/', 'Podfile.lock', 'yourappname.xcworkspace'
pod deintegrate
pod install
sudo gem install cocoapods-deintegrate cocoapods-clean
pod deintegrate
pod cache clean --all
rm Podfile

# if not working
brew upgrade
gem install ffi --version 1.15.4 --user-install


```
