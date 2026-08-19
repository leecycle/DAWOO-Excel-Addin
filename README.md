# DAWOO Excel Add-in

![DAWOO Excel Add-in 리본 메뉴](docs/images/dawoo-excel-addin-ribbon-7.1.0.png)

Windows Excel용 DAWOO VBA 추가기능입니다.

## 설치

1. [DAWOO_Excel_Addin 최신버전을 다운로드합니다.
2. ZIP을 완전히 압축 해제합니다.
3. Excel과 VBA 편집기를 모두 종료합니다.
4. INSTALL.exe를 실행합니다.

설치 위치: `C:\DAWOO\Add-In\다우추가기능.xlam`

## 서식

- 사진대지: 새 04 사진대지.xlsx 파일을 다운로드합니다.
- 기본양식: GitHub 기본양식을 열고 시트를 확인한 뒤 체크한 시트만 현재 통합문서로 복사합니다.

## 파일정리

- 안전 정리는 깨진 이름, 사용자 지정 스타일, 불필요한 사용 범위를 자동 백업 후 정리합니다.
- Excel 기본 내장 스타일은 보존합니다.
- 안전 정리의 스타일 삭제 전 백업은 현재 통합문서 폴더의 `BackUp`에 저장합니다.
- 일반 백업은 `%LOCALAPPDATA%\DAWOO\Add-in`에 저장합니다.

## 업데이트

Excel의 추가 기능 탭에서 업데이트 버튼을 눌렀을 때 GitHub Release를 확인합니다. 다운로드 파일은 GitHub SHA-256 검증 후 설치됩니다.
