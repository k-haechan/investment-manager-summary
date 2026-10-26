# 투자자산운용사 핵심요약집

투자자산운용사 시험을 과목 → 단원 → 챕터 순서로 정리하고, 챕터마다 기출 빈출도를 ★★★/★★/★로 표시한 학습용 사이트입니다.

- 사이트: https://k-haechan.github.io/investment-manager-summary/
- 챕터 구분: 금융투자협회 2026 투자자산운용사 기본서 목차 (`chapters.txt`)
- 별점 기준: 공개된 기출 복원·빈출 자료 교차 집계 (사이트의 "별점 기준" 페이지 참고)

## 로컬 실행

```bash
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/mkdocs serve
```

## 배포

`main` 브랜치에 push하면 GitHub Actions(`.github/workflows/deploy.yml`)가 `mkdocs build --strict`로 빌드해 GitHub Pages에 배포합니다.

## 단원 페이지 추가·수정

작성 형식은 `UNIT_TEMPLATE.md`를 따릅니다.
