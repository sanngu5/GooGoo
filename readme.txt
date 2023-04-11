iOS앱이라서 애플 앱스토어를 거치지 않고 설치하려면 디버깅용으로만 설치가 가능하므로 과정이 번거롭습니다.

1. 실행 환경 (나의 환경)
	1-1. macOS Big Sur
	1-2. Apache Cordova
	1-3. xCode Simulator 또는 iOS 디바이스

2. 실행 방법
	2-1. 웹에서 Node.JS 설치
	2-2. 터미널에서 npm install -g cordova
	2-3. 터미널에서 googoo 폴더로 이동
	2-4. 터미널에서 cordova emulate --target="{디바이스 이름}" 
	(cordova run ios --list로 사용 가능한 디바이스 조회 가능)