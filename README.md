# 공대생 개발일지 (GitHub Pages)

**블로그:** https://yunhokim23.github.io/

## 메뉴와 주소

- [홈](https://yunhokim23.github.io/)
- [개발일지](https://yunhokim23.github.io/devlog/)
- [ExamFlow](https://yunhokim23.github.io/examflow/)
- [RAG 실험](https://yunhokim23.github.io/rag-lab/)
- [오류 해결](https://yunhokim23.github.io/troubleshooting/)
- [회고](https://yunhokim23.github.io/retrospective/)
- [프로필](https://yunhokim23.github.io/about/)

각 메뉴는 독립적인 GitHub Pages 주소를 가집니다. 글은 `/posts/영문-슬러그/`에서 열립니다.

## 새 글 올리기

`_posts/YYYY-MM-DD-english-slug.md` 파일을 만들고 다음 서식을 사용합니다.

```yaml
---
title: "개발일지 제목"
date: 2026-11-11 12:00:00 +0900
description: "한 줄 소개"
categories: ["개발일지", "RAG"]
tags: ["검색", "임베딩"]
comments: false
---
```

본문은 Markdown으로 작성합니다. `main` 브랜치의 GitHub Actions 빌드가 성공하면 게시됩니다.

## 수정 위치

- `index.html`: 첫 화면
- `_tabs/`: 메뉴별 독립 페이지
- `_posts/`: 날짜별 게시글
- `_includes/ef-nav.html`: 상단 이동 메뉴
- `_includes/ef-post-list.html`: 글 목록
- `assets/css/ef.css`: 추후 교체할 수 있는 디자인 스타일
- `_config.yml`: 블로그 제목·언어·주소

ExamFlow는 별도 비공개 저장소입니다. **비공개 개발일지·수업 자료·API 키·강의 원문은 공개 블로그로 자동 복사하지 않습니다.** 지금 게시된 글은 공개용으로 간단히 정리한 내용입니다.
