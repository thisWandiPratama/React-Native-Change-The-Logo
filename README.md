# changeTheLogo
Change The Logo App React Native | Mengganti Logo Aplikasi React Native

## Make Project React Native | Membuat Project React Native 
```
react-native init changeTheLogo
```
## Run the android application | Menjalankan  aplikasi android
```
react-native run-android
```
## Run the Ios application | Menjalankan aplikasi Ios
```
react-native run-ios
```
## react-native-icon 

Is a tool that serves to multiply an app's logo in various sizes automatically. | Merupakan Alat yang berfungsi untuk memperbanyak sebuah logo app dalam berbagai ukuran secara otomatis.
```
https://www.npmjs.com/package/react-native-icon
```

### Install with | Instal dengan:
```
npm install react-native-icon
```
### You will need imagemagick installed | Anda perlu menginstal imagemagick:
```
brew install imagemagick          # For Linux OSX | Untuk linux OSX
sudo apt-get install imagemagick  # For Linux Debian/Ubuntu/etc | Untuk Linux Debian/Ubuntu/dll
sudo yum install imagemagick      # CentOS/etc | Untuk Linux CentOS/dll
```
### Usage | Pemakaian 
Add an icon named icon.png to your project root. Then run | Tambahkan ikon bernama icon.png ke root project react native Anda. Lalu Jalankan Perintah Berikut:
#### For Android
```
./node_modules/.bin/react-native-icon
```
#### For Ios
```
./ios/<ProjectName>/Images.xcassets/AppIcon.appiconset
```
If an Android project is present, then the icon will be copied at all required sizes to | Jika ada proyek Android, maka ikon akan disalin di semua ukuran yang diperlukan untuk:
```
./android/app/src/main/res
```
