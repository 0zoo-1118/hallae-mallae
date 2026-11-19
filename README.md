# 할래말래 (hallae-mallae) — 우당탕탕 대운동회

친구들끼리 각자 폰/PC로 접속해서 노는 웹 파티게임 모음입니다.

- 🕵️ **마피아 · 라이어**
- 🔔 **할리갈리** (3D / 2D)
- 🏃 **종까지 달려!**

## 플레이
GitHub Pages 배포 후 아래 주소로 접속합니다.

```
https://<GitHub아이디>.github.io/hallae-mallae/
```

방을 만든 사람이 방 코드를 공유하면, 다른 사람이 코드로 입장합니다.

## 참고
- 설치·빌드 없이 `index.html` 한 파일로 동작합니다.
- 외부 라이브러리: three.js (r128), PeerJS 1.5.5 — CDN으로 불러옵니다.
- **마피아·라이어**는 기기 간 온라인 플레이를 하려면 `index.html` 안의 `FIREBASE_CONFIG`에 Firebase(Realtime Database) 설정을 넣어야 합니다. 비어 있으면 같은 브라우저 탭끼리만 되는 데모 모드로 동작합니다.
