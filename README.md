# 🎄 크리스마스 트리 꾸미기 (Christmas Tree Decorating Game)

> 하늘에서 쏟아지는 3D 오너먼트 참(Charm)을 바구니로 받아 나만의 크리스마스 트리를 완성하는 3D 웹 인터랙티브 게임입니다.

---

## 🎮 게임 플레이 방법 (Controls)

- **앞뒤 걷기**: `↑` / `↓` (화살표 위/아래)
- **좌우 이동**: `←` / `→` (화살표 좌/우)
- **하늘 올려다보기**: `W` (또는 한글 `ㅈ`)
- **아래 보기**: `S` (또는 한글 `ㄴ`)
- **게임 목표**: 하늘에서 함박눈과 함께 떨어지는 7가지 3D 오너먼트 아래로 이동하여 바구니로 **5개** 수집
- **트리 꾸미기**: 5개를 모으면 크리스마스 트리 모드로 전환되어, 마우스로 360° 트리를 회전하며 내가 모은 3D 오너먼트를 직접 트리에 장식할 수 있습니다.

---

## 🚀 GitHub Pages 배포 안내

이 저장소는 GitHub Pages를 통해 별도 설치 없이 웹 브라우저에서 바로 실행할 수 있도록 최적화되어 있습니다.

### GitHub Pages 활성화 방법:
1. GitHub 저장소 상단의 **Settings** 메뉴로 이동합니다.
2. 좌측 메뉴에서 **Pages**를 클릭합니다.
3. **Build and deployment > Branch** 항목에서 `main` 브랜치 및 `/ (root)` 폴더를 선택하고 **Save**를 누릅니다.
4. 약 1~2분 후 상단에 생성되는 웹 링크(`https://<아이디>.github.io/<저장소이름>/`)로 접속하면 누구나 바로 게임을 플레이할 수 있습니다.

---

## 🛠 기술 스택 (Tech Stack)
- **Three.js** (3D Rendering Engine)
- **GLTFLoader** (3D GLB Model Loader)
- **OrbitControls** (360° Camera Controller)
- **Web Audio API** (자체 합성 8-bit 스타일 크리스마스 캐롤 BGM & 종소리 SFX)
- **HTML5 Canvas / Vanilla JavaScript**
