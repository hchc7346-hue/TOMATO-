# 🍅 던지기 사격장 (TOMATO)

> **연사 타겟 인터랙티브 웹 게임 (Tomato Target Shooting Game)**  
> HTML5 Canvas, Tailwind CSS, Web Audio API를 활용한 무자산(Zero-Asset) 반응형 타겟 슈팅 샌드박스입니다.

---

## 🎮 게임 특징

- **듀얼 레이어 캔버스 (Dual-layer Canvas)**:
  - 영구 데칼 캔버스 (`#splatCanvas`): 토마토 자국, 달걀 얼룩, 페인트 흔적 영구 보존
  - 다이내믹 파티클 캔버스 (`#fxCanvas`): 60FPS 포물선 투사체 및 튀는 파티클 애니메이션
- **Web Audio API 내장 프로시저럴 사운드**:
  - 외부 오디오 파일 다운로드 없이 브라우저 자체 오실레이터로 발사음 및 찰진 타격음 실시간 합성
- **연사(Rapid-Fire) & 포인터 홀드**:
  - 마우스 클릭/터치 유지 시 난수 지터(Jitter)가 적용된 유기적인 연속 발사
- **스크린 셰이크 & 피격 효과**:
  - 강한 타격 시 화면 흔들림 및 햅틱 효과 연출
- **스퀴지(Squeegee) 화면 닦기**:
  - 화면 청소 버튼 클릭 시 스퀴지가 부드럽게 화면을 쓸어내리며 얼룩 제거
- **커스텀 사진 교체**:
  - 파일 업로드를 통해 내가 원하는 사진/타겟으로 즉시 변경 가능

---

## 🚀 실행 방법

별도의 서버 설치 없이 브라우저에서 바로 실행할 수 있습니다:

```bash
# 브라우저에서 실행
start index.html
```

---

## 🛠️ 기술 스택

- **Frontend**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: Tailwind CSS (CDN), Font Awesome 6
- **Typography**: Google Fonts (Black Han Sans, Jua, Noto Sans KR)
- **Audio**: Web Audio API (Sine/Triangle/Sawtooth Oscillator Synthesizer)
- **Rendering**: HTML5 2D Canvas (Dual-layer Stack)

---

## 📄 라이선스

MIT License
