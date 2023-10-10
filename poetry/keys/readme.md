passwd: 870129
name: liushengjiu
company: MF
city: shanghai
country: CN

## cmd
keytool -genkey -alias testalias -keyalg RSA -keysize 2048 -validity 36500 -keystore test.keystore
keytool -list -v -keystore test.keystore

## for upload
keytool -export -rfc -keystore test.keystore -alias testalias -file poem.pem