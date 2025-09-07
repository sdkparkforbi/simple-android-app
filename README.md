# 🚀 Simple Android App with GitHub Codespaces

GitHub Codespaces를 사용하여 개발한 간단한 안드로이드 앱입니다.

## ✨ 기능

- 📊 **클릭 카운터**: 버튼을 클릭할 때마다 횟수가 증가합니다
- ⏰ **시간 표시**: 현재 시간을 실시간으로 표시합니다
- 🎨 **색깔 변경**: 텍스트 색상을 동적으로 변경합니다
- 📱 **토스트 메시지**: 사용자 피드백을 제공합니다

## 🛠️ 기술 스택

- **언어**: Kotlin
- **개발 환경**: GitHub Codespaces
- **빌드 시스템**: Gradle
- **UI**: Android XML Layouts
- **최소 SDK**: API 24 (Android 7.0)

## 🚀 시작하기

### 1. Codespaces에서 실행

1. 이 저장소에서 `Code` → `Codespaces` → `Create codespace` 클릭
2. 환경이 자동으로 설정될 때까지 대기
3. 터미널에서 다음 명령어 실행:

```bash
# 빌드 권한 설정
chmod +x gradlew

# 앱 빌드
./gradlew assembleDebug
```

### 2. APK 파일 생성

빌드 완료 후 APK 파일 위치:
```
app/build/outputs/apk/debug/app-debug.apk
```

### 3. 앱 테스트

- **실제 기기**: APK 파일을 다운로드하여 설치
- **온라인 에뮬레이터**: [Appetize.io](https://appetize.io)에 APK 업로드

## 📱 스크린샷

앱 실행 시 다음과 같은 화면을 볼 수 있습니다:

- 메인 화면: 클릭 카운터, 시간 표시, 색깔 변경 버튼
- 카드 스타일 UI with Material Design
- 반응형 Toast 메시지

## 🔧 개발 환경 설정

### 자동 설정 (권장)
`.devcontainer/devcontainer.json` 파일이 자동으로 다음을 설정합니다:
- Java 11 개발 환경
- Android SDK 및 Build Tools
- VS Code Extensions (Kotlin, Gradle)

### 수동 설정
필요한 도구들:
- Java JDK 11+
- Android SDK (API 33)
- Gradle 8.1+

## 📂 프로젝트 구조

```
simple-android-app/
├── .devcontainer/          # Codespaces 설정
├── app/                    # 앱 소스 코드
│   ├── src/main/
│   │   ├── java/           # Kotlin 소스 파일
│   │   ├── res/           # 리소스 (레이아웃, 문자열 등)
│   │   └── AndroidManifest.xml
│   └── build.gradle       # 앱 빌드 설정
├── gradle/                # Gradle Wrapper
├── build.gradle          # 프로젝트 빌드 설정
└── settings.gradle       # 프로젝트 설정
```

## 🎓 학습 포인트

이 프로젝트를 통해 배울 수 있는 것들:

### Android 개발 기초
- Activity 생명주기
- View 바인딩 (findViewById)
- 이벤트 처리 (OnClickListener)
- Toast 메시지 표시

### Kotlin 문법
- 변수 선언 (var, val)
- 함수 정의
- 문자열 템플릿
- 배열 사용

### Git/GitHub
- 버전 관리
- Codespaces 활용
- 협업 워크플로우

## 🚀 확장 아이디어

### 기능 추가
- [ ] 데이터 저장 (SharedPreferences)
- [ ] 리스트뷰 추가
- [ ] 네트워크 통신
- [ ] 카메라 기능
- [ ] 위치 서비스

### UI 개선
- [ ] Fragment 사용
- [ ] Navigation Component
- [ ] Material Design 3
- [ ] 다크 테마 지원
- [ ] 애니메이션 효과

## 📝 라이선스

이 프로젝트는 MIT 라이선스 하에 제공됩니다.

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 연락처

질문이나 제안사항이 있으시면 이슈를 생성해주세요!

---

⭐ 도움이 되었다면 별표를 눌러주세요!
