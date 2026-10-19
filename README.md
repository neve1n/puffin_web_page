# Puffin

청각장애인 초보 바리스타를 위한 밀크 스티밍 학습 보조 도구 소개 사이트.

https://neve1n.github.io/puffin_web_page/

## 로컬 실행

```sh
python3 -m http.server 4173
```

정적 HTML, CSS, JavaScript로 구성되어 별도 빌드가 필요하지 않습니다. GitHub Pages는 `main` 브랜치의 루트(`/`)에서 배포합니다.

- `index.html`: 소개, 팀, FAQ
- `styles.css`: 반응형 디자인
- `app.js`: 시각 피드백 콘셉트 데모
- `assets/`: 공식 소개 이미지와 로고

데모는 실제 마이크 입력이나 소리 분석을 하지 않습니다. 학습 효과와 감각 전달 방식은 검증 중입니다.
