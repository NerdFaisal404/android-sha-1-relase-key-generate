# android-sha-1-relase-key-generate

C:\Program Files\Java\jdk1.8.0_144\bin>keytool -exportcert -alias taxi_customer -keystore "F:\Taxi app fiver\Taxi app customer info\taxi_customer.jks" -list -v

# android-sha-1-Debug-key-generate
C:\Program Files\Java\jdk1.8.0_181\bin>keytool -exportcert -alias androiddebugkey -keystore "C:\Users\Android-Dev\.android\debug.keystore" | "C:\OpenSSL\bin\openssl" sha1 -binary |"C:\OpenSSL\bin\openssl" base64
