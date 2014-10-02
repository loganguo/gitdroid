. config eclipse network:
http://blog.csdn.net/qq635785620/article/details/8191799

2. start shadowsocks server:sslocal -c shadowsocks.json

3. sudo chmod -R 777 /name-of-root-directory-containing-SDK

4. font-face for eclipse:monospace

5. update android sdk
   * export _JAVA_OPTIONS="-DsockroxyHost=127.0.0.1 -DsocksProxyPort=1080" (./android sdk)
   * cd /home/logan/development/android/android-sdk 
   * ./tools/android list sdk 
   * ./tools/android update sdk --no-ui --filter index_number
   * reference:http://blog.csdn.net/qq635785620/article/details/8191799
6. update local branch to origin branch
   git pull --rebase
   http://stackoverflow.com/questions/2452226/master-branch-and-origin-master-have-diverged-how-to-undiverge-branches
7. add environment path
   `echo 'export GRADLE_HOME=/Users/jonas/gradle-1.2/' >> ~/.profile`

   `echo 'export PATH=GRADLE_HOME/bin:$PATH' >> ~/.profile`
8. Switching remote URLs from HTTPS to SSH:            https://help.github.com/articles/changing-a-remote-s-url#switching-remote-urls-from-https-to-ssh

