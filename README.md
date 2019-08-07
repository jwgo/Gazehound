# Gazehound
<a href="#"><img src="https://live.staticflickr.com/65535/47072998604_a31c1719b8_n.jpg" /></a>

## 소개
Gazehound는 커스터마이징이 자유로운 클라이언트 트래킹 JavaScript 라이브러리입니다.


## 컨셉
Gazehound의 트래킹 정보 전달 방법은 크게 두 가지로 구성되어있습니다.
(구글 애널리틱스의 기본 메커니즘과 유사하게 작동합니다.)

1. Navigator.sendBeacon() 메소드를 이용하여 파라미터들을 전송합니다.
2. 브라우저가 메소드를 지원하지 않는다면, 가로 세로 1px짜리의 이미지를 다운받도록하고 GET 파라미터에 데이터를 추가합니다.


## 데이터
Gazehound가 트래킹하는 브라우저 데이터는 아래와 같습니다.

siteCode, userId, event(being triggered), eventData, documentLocation, referrerLocation, timeStamp(epoch), documentEncodingType, screenResolution, viewPort, browserName, mobileDevice, userAgent, timeZone, campaignSource

