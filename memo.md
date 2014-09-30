1. config eclipse network:
http://blog.csdn.net/qq635785620/article/details/8191799

2. start shadowsocks server:sslocal -c shadowsocks.json

3. sudo chmod -R 777 /name-of-root-directory-containing-SDK

4. font-face for eclipse:monospace

5. update android sdk
   *. export _JAVA_OPTIONS="-DsockroxyHost=127.0.0.1 -DsocksProxyPort=1080"
   *. cd /home/logan/development/android/android-sdk
   *. ./tools/android list sdk
   *. ./tools/android update sdk --no-ui --filter index_number

