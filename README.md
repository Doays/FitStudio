# FIT STUDIO

Windows x64 의상 피팅 실행기입니다.

## 다운로드

[최신 릴리스](https://github.com/Doays/FitStudio/releases/latest)에서 **FitStudio.exe**를 받으세요.

## 실행

호환되는 기존 피팅 작업공간과 입력 프로필·몸·옷 데이터가 필요합니다. 실행창에서 작업공간 폴더를 선택하거나 `FITSTUDIO_WORKSPACE` 환경변수에 경로를 지정하세요. Python 3.11 x64 런타임은 실행기에 포함됩니다.

이번 배포는 2026-11-04 피팅 엔진의 공개 이름을 FIT STUDIO로 변경한 빌드입니다. 이후 편집용 프로그램에 추가한 자동 모션 검사는 후속 기능입니다. 계산 결과의 의상 채택 상태는 출력의 `adoption` 필드에서 확인하세요.

## 포함된 시험 내용

기존 가짜 후보 평가 보고서와 시험용 문자열이 포함됩니다. 기본 피팅에서 본체·뒤끈 해시 일치, 별도 보고서 생성, Windows Defender 검사를 확인했습니다.

## 파일 확인

`SHA256SUMS.txt`와 `RELEASE_VERIFICATION.json`을 함께 제공합니다. 디지털 서명 없는 빌드입니다.

공개 이름과 사용자에게 표시되는 문구는 FIT STUDIO를 사용합니다. 입력 데이터의 호환성을 위한 내부 프로필 식별자는 유지됩니다.
