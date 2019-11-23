# Fix "Unknown" or wrong CPU in About This Mac

#### Scenario 1: If your CPU name is `Unknown`...

* Open Terminal
* `bash <(curl -s https://raw.githubusercontent.com/XLNCs/UsefullScripts/master/cpunamefix.sh)`

#### Scenario 2: If your CPU name is the wrong CPU...

* Change it to `Unknown` in your `config.plist`:
```xml
<key>CPU</key>
  <dict>
    ...
    <string>Unknown</string>
    ...
  </dict>
```
* Restart
* Go to Scenario 1
