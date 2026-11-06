# SuisuiFitter

Windows x64 의상 피팅 실행기 배포 저장소입니다.

## 다운로드

[Releases](https://github.com/Doays/SuisuiFitter/releases)에서 `SuisuiFitter.exe`를 받으세요. `SHA256SUMS.txt`로 파일 해시를 확인할 수 있습니다.

## 정정 배포 r2

최신 릴리스는 가짜 후보 평가 보고서와 시험용 문자열을 포함한 후속 EXE입니다. 최초 릴리스에는 이 후속 내용이 포함되기 전 파일이 게시되어 r2로 정정했습니다.

바이너리에는 `VECTOR / CANDIDATE ASSESSMENT`, `Protein identity`, `Infection rate`, `Lethality`, `biochemical` 문자열이 존재합니다. 이 자료는 가짜 평가 보고서와 비활성 시험용 내용입니다. 기본 피팅의 본체·뒤끈 결과 해시 일치와 보고서 생성, Defender 검사를 r2 파일에서 재확인했습니다.

## 빌드 기준

- 2026-11-04에 보존한 단일 EXE 빌드입니다.
- 핵심 피팅 계산과 수수 뒤끈 계산을 네이티브 모듈에 포함합니다.
- 기존 5개 작업과 정점 배열·결과 해시·판정이 일치한 검증 기록을 확인했습니다.
- 2026-11-05 이후 편집용 프로그램에 추가한 자동 모션·피부 가림 검사는 이후 빌드의 기능입니다.

## 실행 조건

Windows x64와 호환되는 기존 Suisui 작업공간 및 입력 데이터가 필요합니다. Python 런타임은 실행기에 포함되어 있습니다.

기존 작업공간 경로는 `SUISUI_WORKSPACE` 환경변수로 지정합니다. 해당 작업공간에는 배포본이 검증하는 `diagnostics/source_control_connection_20261010_01/garment_fitter_portable_20261021_01/batch_runtime/current_suisui.json`과 호환 프로필·몸·옷 데이터가 필요합니다. 실행기는 로컬 입력의 무결성을 확인합니다.

완료한 계산의 의상 채택 상태는 출력의 `adoption` 필드에서 확인하세요. 이번 배포는 기존 실행 파일의 공개 배포이며, 게임 착용 검증은 별도 단계입니다.

## 배포 확인

릴리스에 파일 SHA-256과 Windows Defender 검사 요약을 제공합니다. 이 실행 파일은 디지털 서명이 없는 빌드입니다. SmartScreen 평판 및 코드 서명 상태는 Defender 악성코드 검사 결과와 별도로 표시될 수 있습니다.

공개 자료는 실행 파일, 사용 안내, 해시와 검사 요약으로 구성됩니다. 개발 소스와 사용자 입력 데이터는 별도로 관리합니다.
