# 한경식

👋 안녕하세요, Unreal Engine 기반 게임 개발자 한경식입니다.

---

## 🎮 Individual Projects

### 🌸 Blossom Of Shadow (개인 프로젝트)
> Unreal Engine 기반 3D 액션 RPG (1인 개발)

🔗 GitHub: https://github.com/GyungSikHan/BlossomOfShadow  
🔗 Demo Video: https://youtu.be/sI_5kmsh7MY  
🔗 Portfolio: https://drive.google.com/file/d/1LRnWCWV3obmQORMKDY8yV8YeIxzddGuA/view  

- **엔진**: Unreal Engine 5.4  
- **기술**: C++, Blueprint  

**핵심 구현**
- Behavior Tree + EQS 기반 AI 전투 시스템
- 콤보 기반 전투 시스템 (AnimNotify 활용)
- Weapon / Skill 구조 설계 (확장성 고려)

**포인트**
- 시스템 단위 설계를 통한 확장성 확보
- AI 상태 전환 및 거리 기반 전투 전략 구현

---

## 🎮 Team Projects
🔫 SYMBIO (팀 프로젝트 / 4인)
> Unreal Engine 기반 1인칭 FPS 전투 게임

🔗 GitHub: https://github.com/GyungSikHan/1st-Team14-CH3-Project

🔗 Demo Video: [https://youtu.be/](https://youtu.be/tJcozATuAgQ?si=-gHiBJwwpUamFQjY)

🔗 Portfolio: https://drive.google.com/file/d/1wuGg5KNYLVXD0ZXs_h4th62TAfnBNP6L/view

- **엔진**: Unreal Engine 5.5
- **기술**: C++, Blueprint, Git

**핵심 구현**
- Weapon Base + Component 구조 설계
  - WeaponComponent / StatusComponent 등 컴포넌트 기반 구조로 기능을 분리하고, ACWeapon 베이스 클래스를 통해 장착·조준·발사·재장전 로직을 통합 관리하도록 설계
- 발사 및 데미지 처리 파이프라인 구현
  - LineTrace / Projectile 기반 충돌 처리 후 HitData → TakeDamage 흐름으로 연결되는 FPS 전투 시스템 구현
- Aim / Recoil / 카메라 연출 구현
  - Timeline + Curve 기반 FOV 보간을 통해 조준(Aim) 시스템을 구현하고 반동(Recoil), 카메라 쉐이크 등 FPS 전투 연출을 구현
**포인트**
- 컴포넌트 기반 설계를 통해 캐릭터 기능을 모듈화하여 유지보수성과 확장성 확보
- Weapon Base Class 설계를 통해 다양한 무기 시스템을 공통 구조로 통합
- 애니메이션 몽타주와 상태(State) 충돌 문제를 Delegate 기반 상태 복구 로직으로 해결
