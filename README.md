# 컴시간 · Galaxy Watch 9

원본 `wear-debug.apk`를 기준으로 Wear OS APK를 복원/수정하고 GitHub Actions에서 빌드하는 프로젝트입니다.

## 입력
`input/wear-debug.apk`

## 빌드
GitHub Actions의 **Build Wear APK** 워크플로를 실행합니다.

현재 단계:
1. 원본 APK 디컴파일
2. 디컴파일 결과를 artifact로 보존
3. UI 패치 적용
4. APK 재빌드/서명
5. 최종 APK artifact 생성

원본 APK는 디컴파일 특성상 최초 1회 저장소에 직접 넣어야 합니다.
