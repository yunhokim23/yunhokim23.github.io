---
title: "ExamFlow"
icon: "fas fa-laptop-code"
order: 2
permalink: /examflow/
---

{% include ef-nav.html %}
<div class="ef-page">
## ExamFlow는 어떤 프로젝트인가요?

학생이 강의자료(PDF·텍스트·녹음·영상)를 올리면 시험 대비를 도와주는 웹서비스를 만들고 있습니다.

## 개발 상태

- **구현 및 로컬 테스트 보고:** 파일에서 텍스트 추출, 청킹, 저장, Hybrid Search 기반 근거 검색
- **확인할 점:** 학생·개발자·관리자 화면의 직접 사용 테스트, 계정별 권한, 실제 배포
- **현재 실험 제한:** PDF 처음 2페이지, 녹음·영상 처음 60초만 처리
- **아직 미완성:** 전체 요약·핵심 요약·예상문제 AI 생성

<div class="ef-note">이미 완성한 기능과 앞으로 개발할 기능을 구분해서 기록합니다.</div>

## 관련 글

{% include ef-post-list.html category="ExamFlow" %}

[개발일지 전체 보기]({{ '/devlog/' | relative_url }})
</div>
