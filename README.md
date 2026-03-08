## 📂 주요 코드 설명

### Script Hierarchy

폴더 하위에는 여러 개의 스크립트가 존재하여  
**폴더 단위로 구조를 간략히 설명합니다.**

---

### Assets/Scripts


Assets/Scripts
│
├─ Firebase
│ └─ 초기화, 인증 권한 허용, 회원가입 및 로그인 로직
│
├─ Stage
│ │
│ ├─ InnerController
│ │ │
│ │ ├─ Augments
│ │ │ └─ 증강 상자 및 증강 로직 구현
│ │ │ 증강 능력치 (ScriptableObject)
│ │ │
│ │ ├─ Enemies
│ │ │ └─ 몬스터 로직
│ │ │ (NavMesh, Hitbox, Spawner, Pool, HP UI 등)
│ │ │
│ │ ├─ Item
│ │ │ └─ 색상 흡수 아이템 및 드랍 아이템
│ │ │
│ │ ├─ Player
│ │ │ └─ 플레이어 이동 및 스킬 제어
│ │ │ 스킬 컨트롤러, 색상 속성 로직
│ │ │
│ │ ├─ Sounds
│ │ │ └─ BGM 및 SFX 관리
│ │ │
│ │ └─ UI
│ │ └─ 플레이어 및 몬스터 피격 시
│ │ Damage UI 팝업 로직
│ │
│ └─ OuterController
│ └─ 메인 로비 로직
│ 난이도 및 스테이지 패널 프리팹


---

### 추가 주요 스크립트

| Script | 설명 |
|------|------|
| `StageLogPanel.cs` | 모바일 디버깅용 텍스트 로그 패널 |
| `ChatManager.cs` | 스테이지 시작 시 스토리 채팅 |
| `TutorialManager.cs` | 튜토리얼 패널 표시 |
| `FPSDisplay.cs` | 우측 상단 FPS 표시 |
| `SceneLoadingUI.cs` | 씬 로딩 UI |
| `SceneTransitionManager.cs` | 메인 로비 ↔ 스테이지 전환 |
| `StageSceneController.cs` | 씬 내부 UI 컨트롤러 (Setting, Exit 등) |
