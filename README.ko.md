# eza-cmd

[English README](README.md)

Windows에서 eza 프로그램을 더 편리하게 사용할 수 있도록 도와주는 배치(cmd) 스크립트 모음입니다. 이 스크립트들은 명령줄에서 eza와 관련된 기능을 쉽게 활용할 수 있도록 설계되었습니다. 제공: JayTwoLab

## eza 설치

이 스크립트들을 사용하려면 [eza](https://github.com/eza-community/eza) 프로그램이 설치되어 있어야 합니다.

### eza 다운로드
- 공식 GitHub 릴리즈: [https://github.com/eza-community/eza/releases](https://github.com/eza-community/eza/releases)

### 패키지 매니저로 설치
- **Scoop**:
  ```
  scoop install eza
  ```
- **winget**:
  ```
  winget install --id eza-community.eza
  ```
- **Chocolatey**:
  ```
  choco install eza
  ```

eza 설치 후 시스템 PATH에 등록되어 있는지 확인하세요.

## 포함된 스크립트
- **ela.cmd**
- **elh.cmd**
- **ell.cmd**
- **els.cmd**
- **elt.cmd**

각 스크립트는 서로 다른 기능을 제공합니다. 자세한 사용법은 각 스크립트 내 주석을 참고하세요.

## 사용 방법
1. 이 저장소를 클론하거나 다운로드합니다.
2. 원하는 `.cmd` 파일을 시스템의 `PATH` 환경 변수에 포함된 폴더에 복사하거나, 저장소 폴더에서 직접 실행할 수 있습니다.
3. 명령 프롬프트 또는 PowerShell 창을 열고, 아래와 같이 스크립트 이름을 입력하여 실행합니다.
   ```
   ela
   elh
   ell
   els
   elt
   ```

## 라이선스
이 프로젝트는 저장소에 포함된 LICENSE 파일의 내용을 따릅니다.

## 작성자
JayTwoLab
