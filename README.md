# Blades of Time (블레이즈 오브 타임) - 100% 완전 한국어 패치 v1.0

[![Release](https://img.shields.io/badge/Release-v1.0-blue.svg)](https://github.com/)
[![Platform](https://img.shields.io/badge/Platform-Steam%20PC-brightgreen.svg)](https://store.steampowered.com/app/208640/Blades_of_Time/)
[![Translation](https://img.shields.io/badge/Translation-100%25-orange.svg)]()
[![Typography](https://img.shields.io/badge/Typography-1:1%20Pixel--Perfect-purple.svg)]()

> **Gaijin Entertainment / Konami**에서 개발한 액션 어드벤처 게임 **《블레이즈 오브 타임 (Blades of Time)》**의 스팀(Steam) PC 버전 100% 한국어 패치입니다.

---

## 📌 패치 핵심 특징

1. **100% 완전 번역 (21개 CSV, 4,479행 전수)**
   - 메인 스토리 대사, 인게임 컷씬 자막, 어빌리티/스킬 설명, 컬렉션, 베스티어리(몬스터 도감), 로딩 팁, 튜토리얼 조작키 안내, 메인 메뉴 및 시스템 설정 UI 전수 한국어화.
2. **1:1 Pixel-Perfect 고정 규격 폰트 (48개 서브폰트 테이블 일치)**
   - 8개 해상도(480p ~ 1200p) 및 6개 서브폰트(총 48개 테이블) 전체에 1:1 고정 쿼드(Quad) 메트릭스를 적용하여 글자 찌그러짐(Stretch)과 줄높이 춤춤 현상(0px Baseline Drift)을 영구 해결했습니다.
3. **안티-클리핑(Anti-Clipping) 타이포그래피**
   - 받침(종성)이 있는 글자(`출`, `침`, `반`, `물`, `상`, `력`, `한` 등)의 최하단 획이 잘리지 않도록 안전 여백($\ge 1.0\text{px} \sim 5.0\text{px}$)을 확보했습니다.
4. **결함 문자 0건 보장 (Zero Asterisk `*`)**
   - 다고르(Dagor) 엔진의 글리프 조회 메커니즘을 100% 에뮬레이션하여 인게임에서 글자가 깨지거나 `*`로 출력되는 현상을 전수 색출 및 차단했습니다.
5. **음성 언어 선택 지원**
   - 옵션의 음성 언어 설정에서 `일본어` 및 `영어` 음성을 완벽하게 표시하고 선택할 수 있습니다.

---

## 📥 다운로드 및 파일 구성

- **GUI 원클릭 설치기**: **`BladesOfTime_Korean_Installer.exe`** (폴더 자동 탐색 + 폴더 선택창 지원 + 자동 백업/복구 내장 단일 실행 파일)
- **정식 릴리스 전체 압축 파일**: **`Blades_of_Time_Korean_Patch_v1.0.zip`**
  *(GitHub Releases 탭에서 다운로드하실 수 있습니다.)*

---

## 💻 설치 방법

### 방법 1: GUI 원클릭 자동 설치기 이용 (가장 권장하는 방법)
1. **`BladesOfTime_Korean_Installer.exe`**를 실행합니다.
2. 프로그램이 스팀 게임 설치 폴더(`Blades of Time`)를 자동으로 감지합니다.
   - 만약 다른 드라이브나 사용자 지정 라이브러리에 설치되어 있다면 **[폴더 찾기...]** 버튼을 눌러 게임 폴더(`bladesoftime.exe`가 있는 위치)를 직접 지정할 수 있습니다.
3. **[한글 패치 설치 (Install)]** 버튼을 클릭합니다.
   - 기존 원본 파일이 게임 폴더 내 `backup_original` 폴더에 자동으로 백업된 후 패치가 적용됩니다.
4. 패치 설치 완료 후 **[게임 실행]** 버튼을 눌러 바로 플레이할 수 있습니다.
   *(언제든지 **[원본 복구 (Restore)]** 버튼을 누르면 순정 원본 상태로 1초 만에 되돌릴 수 있습니다.)*

### 방법 2: 수동 덮어쓰기
1. Steam 라이브러리에서 **[Blades of Time]** 우클릭 $\rightarrow$ **[관리]** $\rightarrow$ **[로컬 파일 탐색]**을 클릭하여 게임 설치 폴더를 엽니다.
   - 기본 경로 예시: `C:\Program Files (x86)\Steam\steamapps\common\Blades of Time`
2. 다운로드한 `Blades_of_Time_Korean_Patch_v1.0.zip` 파일의 압축을 풉니다.
3. 압축 해제된 모든 파일 및 폴더(`bot.vromfs.bin` 및 `ui` 폴더)를 **게임 설치 폴더에 그대로 복사(덮어쓰기)**합니다.

```
📁 Blades of Time (게임 설치 폴더)
 ├── 📄 bot.vromfs.bin           <-- 패치 파일 (덮어쓰기)
 ├── ⚙️ install_korean_patch.bat <-- 원클릭 자동 설치기 (선택)
 ├── ⚙️ uninstall_korean_patch.bat <-- 원클릭 순정 복구기 (선택)
 └── 📁 ui
      ├── 📄 fonts_jap.480.bin   <-- 패치 폰트 (덮어쓰기)
      ├── 📄 fonts_jap.600.bin
      ├── 📄 fonts_jap.720.bin
      ├── 📄 fonts_jap.768.bin
      ├── 📄 fonts_jap.1024.bin
      ├── fonts_jap.1050.bin
      ├── 📄 fonts_jap.1080.bin
      └── 📄 fonts_jap.1200.bin
```

---

## 🎮 인게임 설정 확인

1. 게임을 실행합니다.
2. 메인 메뉴에서 **[옵션]** $\rightarrow$ **[음성 언어]**에서 원하시는 음성(`일본어` 또는 `영어`)을 선택합니다.
   XXXXX*(기본 텍스트는 일본어 베이스 폰트를 치환하여 출력되므로 별도 조작 없이 100% 한국어로 자동 출력됩니다.)*XXXXXX
스팀에서 게임 언어설정을 일본어로 하셔야합니다.

---

## 🔄 패치 삭제 및 순정 복구 (Uninstallation)

- **자동 복구기를 이용할 경우**: 게임 폴더 내의 **`uninstall_korean_patch.bat`**을 실행하면 백업본으로 즉시 원복됩니다.
- **Steam 무결성 검사를 이용할 경우**:
  1. Steam 라이브러리에서 **[Blades of Time]** 우클릭 $\rightarrow$ **[속성]** 선택.
  2. **[설치된 파일]** 탭 $\rightarrow$ **[게임 파일 무결성 검사]**를 클릭하시면 원본 파일이 자동 재다운로드됩니다.

---

## 📂 파일 무결성 해시 (SHA256SUMS)

```
470b24410454ece5689e55e57b61d0b8412874763f447ebb223865fe37308734  Blades_of_Time_Korean_Patch_v1.0.zip
65b0866d92f7481ba882fe1a8a2d480d151950e32f7a0b3f572a1a011ea8974a  bot.vromfs.bin
32a6012564c7e6c433365b991da7147775a6111f10bc4ca44d0b13cf14a1c5d4  ui/fonts_jap.1200.bin
3cae0d6174a8d46179379899f1fa44ec1fdd09289569bca937ff7ee38ffba81c  ui/fonts_jap.1080.bin
b5ca2459fb0a99672eb7d825dd5dd8ff1b988fdbdc7e909a36a7a5840391ee03  ui/fonts_jap.1050.bin
b94474591f86f7b15d97e88ca8c86ffb717e3f8903c7ea3c8fbba033327cb704  ui/fonts_jap.1024.bin
6015771966beae444585ecf00a5d2e0b51061f22312d8a0c24ea0445d351efbe  ui/fonts_jap.768.bin
9632884be5f3074092b7ce1f4277732a3fc2641f3914a5ef8c8fae322301c23f  ui/fonts_jap.720.bin
ed5200b343834da4e14f9d45e4868e27867fa7a26f8f17548b17b2fefc7fb87b  ui/fonts_jap.600.bin
3275a1656ec56877893962d3a372132e1d74653dd7085750fe86a079f2ea3053  ui/fonts_jap.480.bin
```

---

## ⚠️ 라이선스 및 주의사항

- 본 패치는 비공식 유저 한국어 패치이며, 모든 게임 자산의 권리는 Gaijin Entertainment 및 Konami에 있습니다.
- 비상업적 무료 배포 목적으로만 사용이 가능하며, 패치 파일의 상업적 판매 및 유료 재배포를 일체 금합니다.

