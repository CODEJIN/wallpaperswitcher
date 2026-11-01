# WallpaperSwitcher

[한국어](#한국어) · [English](#english)

---

## 한국어

연결된 Wi-Fi에 따라, 그리고 폴더블 기기라면 접힘/펼침 상태에 따라 홈 화면과 잠금화면 배경을 자동으로 바꿔주는 Android 앱입니다.

- **Wi-Fi마다 프로필**: 집, 회사처럼 Wi-Fi마다 프로필을 만들고, 홈 화면·잠금화면에 쓸 사진 폴더를 정합니다. 등록하지 않은 Wi-Fi이거나 연결이 없을 때는 "연결 안 됨" 프로필의 폴더를 씁니다.
- **자동 순환**: 정해둔 간격(기본 30분)마다 폴더 안의 사진으로 바뀝니다. 무작위·순차 중에서 고를 수 있습니다.
- **폴더블 지원**: 접었을 때와 펼쳤을 때 서로 다른 폴더와 표시 방식을 쓸 수 있습니다.
- **완전 오프라인**: 서버, 광고, 분석 도구가 없고 모든 설정은 기기 안에만 저장됩니다.

### 설치

1. [Releases](https://github.com/CODEJIN/wallpaperswitcher/releases/latest)에서 `WallpaperSwitcher-v*.apk`를 내려받습니다.
2. 파일을 열면 "출처를 알 수 없는 앱" 설치 허용을 묻습니다. 허용하고 설치합니다.
   - **삼성 갤럭시**: "자동 차단(Auto Blocker)"이 켜져 있으면 설치가 막힙니다. **설정 → 보안 및 개인정보 보호 → 자동 차단**을 잠시 끄고 설치한 뒤 다시 켜세요.
3. 앱을 처음 열면 안내에 따라 필요한 권한을 허용하고, "연결 안 됨" 프로필에 기본으로 쓸 사진 폴더를 고르세요.

**요구사항**: Android 12 이상

업데이트는 자동으로 되지 않습니다. 새 버전이 나오면 Releases에서 내려받아 그대로 설치하면 설정이 유지된 채 업데이트됩니다.

### 권한을 쓰는 이유

| 권한 | 이유 |
|---|---|
| 위치 (정확한 위치, 항상 허용) | Android는 연결된 Wi-Fi 이름(SSID)을 읽을 때 위치 권한을 요구합니다. 앱을 닫아둔 동안에도 Wi-Fi가 바뀌면 배경화면을 바꾸려면 "항상 허용"이 필요합니다. 실제 위치(좌표)는 사용하거나 저장하지 않습니다. |
| 정확한 알람 | Wi-Fi나 폴딩 상태가 바뀐 걸 빨리 알아차리기 위해 씁니다. |
| 배터리 최적화 예외 (선택) | 절전 기능 때문에 자동 전환이 멈추지 않게 합니다. |

자세한 내용은 [개인정보처리방침](https://codejin.github.io/wallpaperswitcher-privacy-policy/)을 참고하세요.

### 확인

APK는 아래 인증서로 서명돼 있습니다. 다른 곳에서 받은 파일이라면 이 값과 같은지 확인하세요.

```
서명 인증서 SHA-256: F4:BA:74:3B:5B:BB:60:F2:BD:59:B2:47:D4:62:C6:65:EF:D1:E3:80:B5:00:65:51:D0:72:6A:61:DD:18:13:A9
```

### 문의

버그나 제안은 [Issues](https://github.com/CODEJIN/wallpaperswitcher/issues)에 남겨주시거나 codejin2@gmail.com으로 보내주세요.

---

## English

An Android app that automatically changes your home and lock screen wallpaper based on the Wi-Fi network you're connected to — and, on foldables, whether the device is folded or unfolded.

- **A profile per Wi-Fi network**: Create profiles (e.g. Home, Office) and pick photo folders for the home and lock screens. On unsaved networks or with no connection, the "Not connected" profile's folders are used.
- **Automatic rotation**: Wallpapers rotate through the photos in those folders on a schedule you set (default 30 minutes), randomly or in order.
- **Foldable support**: Use different folders and display settings for the folded and unfolded screens.
- **Fully offline**: No servers, ads, or analytics. All settings stay on your device.

### Install

1. Download `WallpaperSwitcher-v*.apk` from [Releases](https://github.com/CODEJIN/wallpaperswitcher/releases/latest).
2. Open the file and allow installing from unknown sources when prompted.
   - **Samsung Galaxy**: Auto Blocker blocks the install. Temporarily turn it off under **Settings → Security and privacy → Auto Blocker**, install, then turn it back on.
3. On first launch, follow the guide to grant permissions and choose a default photo folder for the "Not connected" profile.

**Requires** Android 12 or later.

There are no automatic updates. To update, download the new APK from Releases and install it over the old one; your settings are kept.

### Why the permissions

| Permission | Why |
|---|---|
| Location (precise, allow all the time) | Android requires location permission to read the connected Wi-Fi's name (SSID). "Allow all the time" lets the wallpaper change when your Wi-Fi changes while the app is closed. Your actual location (coordinates) is never used or stored. |
| Exact alarms | Lets the app notice Wi-Fi and fold changes quickly. |
| Battery optimization exemption (optional) | Keeps battery saving from stopping automatic switching. |

See the [privacy policy](https://codejin.github.io/wallpaperswitcher-privacy-policy/) for details.

### Verify

The APK is signed with this certificate. If you got the file elsewhere, check that it matches.

```
Signing certificate SHA-256: F4:BA:74:3B:5B:BB:60:F2:BD:59:B2:47:D4:62:C6:65:EF:D1:E3:80:B5:00:65:51:D0:72:6A:61:DD:18:13:A9
```

### Contact

Report bugs or suggestions in [Issues](https://github.com/CODEJIN/wallpaperswitcher/issues) or email codejin2@gmail.com.
