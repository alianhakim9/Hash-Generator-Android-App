# Hash Generator App

Simple application for generate hash from plain text using some algorithm.

# Preview

## Installation
Clone this repository and import into **Android Studio**
```bash
git@github.com:alianhakim8/HashGenerator.git
```

## Configuration
### Keystores:
Create `app/keystore.gradle` with the following info:
```gradle
ext.key_alias='key0'
ext.key_password='HashGeneratorApp'
ext.store_password='HashGeneratorApp'
```
And place both keystores under `app/` directory:
- `HashGenerator_KeyStore.keystore`

## Build variants
Use the Android Studio *Build Variants* button to choose between **production** and **staging** flavors combined with debug and release build types

## Generating signed APK
From Android Studio:
1. ***Build*** menu
2. ***Generate Signed APK...***
3. Fill in the keystore information *(you only need to do this once manually and then let Android Studio remember it)*

## Maintainers
This project is mantained by:
* [Alian Hakim](http://github.com/alianhakim)


## Contributing

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -m 'Add some feature')
4. Run the linter (ruby lint.rb').
5. Push your branch (git push origin my-new-feature)
6. Create a new Pull Request

