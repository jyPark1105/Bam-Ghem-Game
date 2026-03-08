**주요 코드 설명**

<aside>
<img src="/icons/server_lightgray.svg" alt="/icons/server_lightgray.svg" width="40px" />

**Script hierarchy**

**폴더 하위에는 여러 개의 스크립트가 존재하여 폴더만 간략히 소개하겠습니다.**

**굵은 글씨는 모두 ‘폴더’입니다.**

**Assets/Scripts**
│
├─ **Firebase : 초기화, 인증 권한 허용, 회원가입 및 로그인 로직**
├─ **Stage**
│  │
│  ├─ **InnerController : 스테이지 내부 로직**
│  │  │
│  │  ├─ **Augments : 증강 상자 및 증강 로직 구현, 증강 능력치 구현(Scriptable Object)**
│  │  ├─ **Enemies : 몬스터 로직(NavMesh, Hitbox, Spawner, Pool, HP_UI 등)**
│  │  ├─ **Item : 색상 흡수 아이템 및 드랍 아이템**
│  │  ├─ **Player : 움직임 및 스킬 동작 제어, 스킬 컨트롤러, 색상 속성 로직**
│  │  ├─ **Sounds : 배경음(BGM) 및 효과음(SFX)** 
│  │  └─ **UI : 플레이어 및 몬스터 피격 시 Damage UI 팝업 로직**
│  │
│  ├─ **OuterController : 메인 로비 로직 → 난이도 및 스테이지 패널 프리펩**

… 추가로 존재하는 **주요 스크립트**

1. `StageLogPanel.cs` : 모바일 디버깅 시 사용한 텍스트 로깅 패널
2. `ChatManager.cs` : 스테이지 시작 시 스토리 채팅
3. `TutorialManager.cs` : 튜토리얼 패널 띄우기(튜토리얼 동작 X)
4. `FPSDisplay.cs` : 우측 상단 FPS 표시
5. `SceneLoadingUI.cs` : 로딩 시 씬 전환
6. `SceneTransitionManager.cs`  : 메인 로비 ↔ 스테이지 내부 전환 담당
7. `StageSceneController.cs` : 씬 내부 UI 컨트롤러(Setting, Exit 등)
</aside>
