# Achmage · Suno Albums

AI(Suno 5.5)로 빚은 앨범 컬렉션. 한 곡이 아니라 **한 장의 앨범 단위**로 컨셉을 잡아 구성합니다.

🎧 **Live (GitHub Pages)** → https://laguna821.github.io/Suno_albums/

---

## Albums

| Vol | 앨범 | 장르 | 트랙 | 페이지 |
|----|------|------|------|--------|
| Vol.1 | **오얏꽃 사계 (李花四季)** | 조선 재즈 (1930s 경성) | 15 | [▶ 듣기](ihwa-sagye/) |

> **오얏꽃 사계** — "사라진 나라를 향한 네 계절". 표면은 사랑의 사계절 연가, 그 속은 잃어버린 나라를 향한 애도. 가사에 정치적 단어를 한 번도 쓰지 않으면서, 같은 말이 사랑과 망국 두 문맥에서 동시에 성립하도록 설계했습니다.

---

## 폴더 구조

```
Suno_albums/
├── index.html              # 갤러리 랜딩 (앨범 목록)
├── README.md
└── ihwa-sagye/             # 앨범 Vol.1
    ├── index.html          # 앨범 플레이어
    ├── audio/01.mp3 … 15.mp3
    └── images/hero.png · cover.png
```

각 앨범은 **독립 폴더**로 관리합니다. GitHub Pages에서 `/<album-slug>/` 경로로 바로 열립니다.

## 새 앨범 추가하기

1. 새 폴더 생성: `<album-slug>/` (예: `next-album/`)
2. 그 안에 `index.html`, `audio/`, `images/` 구성 (`ihwa-sagye/`를 템플릿으로 복사)
3. 루트 `index.html`의 `ALBUMS` 배열에 객체 1개 추가 (slug·title·cover·meta)
4. commit & push → Pages 자동 반영

## GitHub Pages 켜기 (최초 1회)

repo **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `/ (root)`** 저장.
약 1분 뒤 `https://laguna821.github.io/Suno_albums/` 에서 공개됩니다.

---

## Credits

- **Music**: generated with [Suno](https://suno.com) v5.5
- **Composition / album design**: Achmage OS `joseon-jazz-album` skill
- **Produced by Achmage**

© 2026 Achmage
