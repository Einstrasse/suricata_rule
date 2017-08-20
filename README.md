# suricata_rule

### 테스트 환경
- 운영체제: Ubuntu 16.04 LTS 64bit
- rules 디렉토리 경로
```
/usr/local/etc/suricata/rules
```
- 네트워크 인터페이스: ens32

### 탐지 여부에 따른 사이트 분류
1. HTTP 패킷으로 탐지 가능한 사이트들
```
http://hitomi.la
http://kass.org.kp/
http://kcna.kp/
http://ks8282.com/
http://naevr.com/
http://naver6.com
http://rodong.rep.kp/
http://uriminzokkiri.com
http://www.4shared.com
http://www.bamwar25.com/
http://www.faa25.com/
http://www.kimmadam.net/
http://www.minjok.com
http://www.narutoxxx.com
http://www.naver.cm
http://www.ryomyong.com
http://www.sedisk.com
http://www.sk386.com/
http://www.tcosc.net/
http://www.torenzoa.net
http://www.umj262.com/
http://www.uriminzokkiri.com

http://kitribob.wiki/wiki/
http://linoit.com/users/men1212/canvases/19%EA%B8%88%20
http://named.com/game/ladder/v2_index.php
http://snoopspy.com/download
http://test.gilgil.net/streaming/test.mp4
http://www.ilbe.com/ilbe
http://www.winclub88.net/my/4D.html
```
2. DNS 쿼리로 탐지 가능한 사이트들
```
http://onaratv.com/
http://pornpros.com
```
3. HTTPS의 TLS Client Hello msg로 탐지 가능한 사이트들
```
https://graphgame.net/
https://sex.com
https://torrenthaja.com
https://torrentkim10.net
https://webtoon.bamtoki.com/
https://mujige53770.wixsite.com
https://www.mtbucks.com
https://www.phishtank.com/
```
4. 페이지를 특정하여 탐지가 불가능한 사이트들
```
https://www.facebook.com/profile.php?id=100019007882633
https://www.opioids.com/offshorepharmacy/index.html
https://yobit.net/en/dice/
```