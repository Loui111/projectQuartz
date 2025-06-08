# Unity 개발 환경 정보 (unity-development-environment.md)

본 문서는 Unity 기반 Windows 게임 개발을 위한 현재 설치된 환경 정보를 요약합니다. AI 및 매니저가 자동 인식/활용할 수 있도록 구조화되어 있습니다.

---

## 1. 운영체제 및 주요 툴
- **운영체제:** macOS
- **프로젝트 목적:** Windows용 2D 퍼즐(그림맞추기) 게임 개발 및 Steam 배포
- **Unity 프로젝트 템플릿:** 2D Universal (기존 2D → 2D Universal로 변경)

## 2. Unity 관련
- **Unity Hub** 설치 완료
- **Unity 에디터** (LTS 버전, Mac용) 설치 완료
    - **Windows Build Support (IL2CPP)** 모듈 포함 (Windows .exe 빌드 가능)
- **Unity 계정:** Personal(무료) 라이선스, 로그인 완료

## 3. 코드 에디터 및 확장
- **코드 에디터:** Visual Studio Code (VSCode)
- **설치된 확장 프로그램:**
    - C# (by Microsoft)
    - Prettier
    - Unity Tools
    - Unity Code Snippets
    - Unity Extension (by Unity Technologies)

- **GitHub 연동 및 인증:**
    - https://github.com/Loui111/projectQuartz.git
    - 이 프로젝트는 SSH 방식(`git@github.com-personal:Loui111/projectQuartz.git`)으로 개인 계정(genesisjk)의 SSH 키를 사용해 연동함.
    - SSH 키 관리 및 설정 방법은 `~/.ssh/config` 파일에 기록되어 있음.

> 참고: .NET SDK는 미설치 상태이며, Unity 개발에는 'C# (by Microsoft)' 확장만으로 충분합니다. 'C# Dev Kit' 확장은 설치하지 않음.

## 4. .NET SDK
- **.NET SDK:** 미설치 (dotnet 명령어 없음)
- Unity 개발에는 영향 없음, 필요시 추후 설치 가능

## 5. 기타
- Unity에서 VSCode를 외부 스크립트 에디터로 지정
- Mac에서 Windows(.exe) 빌드 및 Steam 배포 준비 완료
- **버전 관리:** Git 및 GitHub 사용 (Unity Version Control 미사용)

---

> 이 문서는 AI 및 매니저가 자동 파싱/분석하기에 최적화된 구조로 작성되었습니다. 추가 환경 변경 시 반드시 최신 상태로 갱신해 주세요.
