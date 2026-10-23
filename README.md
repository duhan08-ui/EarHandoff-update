# EarHandoff-update

갤럭시 앱 **이어폰 넘기기**(EarHandoff) 온라인 업데이트 배포용.

- 앱은 `version.json`을 읽어 `versionCode`가 설치된 버전보다 크면 업데이트를 안내합니다.
- 받은 APK의 SHA-256이 `version.json`의 `sha256`과 다르면 설치하지 않습니다.
- APK는 같은 노트북(같은 서명 키)에서 `build_apk.bat`으로 빌드한 것만 올려야 합니다.
