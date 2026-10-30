# 실습과제 #1 : 영화 보드 완성판
- 이름 / 학번 : 2651032 / 배찬희
- 사이트 주소 : https://bowmouse.github.io/web-hw1/
- 사용한 API 1 : https://image.tmdb.org/t/p/w342/xul24PvmhG1smXsAcOPCeeuKLUN.jpg 미션 파서블 2021
               https://image.tmdb.org/t/p/w342/6vDaYhZypJzd8r0NnSY2JPIX6Y5.jpg 미션 임파서블 1996
              https://image.tmdb.org/t/p/w342/lZeIe0FsT4jKsVvJxg90ygHsmf2.jpg 미션 1986
              https://image.tmdb.org/t/p/w342/s2426EIW0arpjN0R0qErJfXQxZD.jpg 미션 임파서블: 로그네이션 2015
                https://image.tmdb.org/t/p/w342/iNJsojTGQoOWL9f9U23jsibONVu.jpg 미션 임파서블: 파이널 레코닝 2025
               https://image.tmdb.org/t/p/w342/2ceVO8N44bAllaevPl2CKyFejCv.jpg 미션: 구출작전 2025
                https://image.tmdb.org/t/p/w342/rgXoleAFRubQxoH4d1JeUAHHeMJ.jpg 라스트 미션 2018
               https://image.tmdb.org/t/p/w342/gHQTg7KgC7VPMcy6f6zfJc8fu34.jpg 미션 2024
                https://image.tmdb.org/t/p/w342/u8gdbmvbypmVmoCJyPkBiJyvAvv.jpg 미션 임파서블: 폴아웃 2018
               https://image.tmdb.org/t/p/w342/ai5gzHA5uWT0krEXrMfepdmJ6Qg.jpg 트랜스포터: 라스트 미션 2008
- 사용한 API 2 : KOBIS 일별 박스오피스 (기준일 2026-10-25) 
## 구현 항목 체크
- [✓] 1. CSS 변수
- [✓] 2. 섹션 2개
- [✓] 3.카드 10장의 포스터
- [✓] 4. 박스오피스 배지
- [✓] 5. 6주차 효과 유지
- [✓] 6. 보드 격자
- [✓] 7. 헤더
- [✓] 8. 히어로
- [✓] 9. 상세 페이지
- [✓] 10. 캡처 3장
- [✓] 11. 푸터(두 쪽 모두)
- [✓] 12. 검증과 README
- [✓] 반응형 이미지(moving_image)
- [✓] 다크모드(dark_mod)
- [✓] 로딩 스켈레톤(loading_skeleton)
## 어려웠던 점 3가지와 해결
1. 미디어 쿼리: 실습 과제 안내문을 다독하고 학우와 의논하여 고심 끝에 문제 해결을 시도했고, 성공했습니다.
2. detail페이지: 실습 과제 안내문과 실습 수업 내용을 회상하여 고심한 끝에 문제를 해결했습니다. 
3. 로딩 스켈레톤 UI: 수업내용과 실습 과제 안내문을 읽으며 고심해도 해결되지 않아 ai에게 질문했고, 문제를 해결했습니다.
## 참고한 자료 (교재 절, MDN 페이지 제목, 검색어)
실습 과제 안내문, 실습 수업 자료, AI사용(root 사용 예, var() 의 개념, 로딩 스켈레톤의 의의)
## 생성형 AI 사용 내역 (없으면 "없음")
- 질문 요지 :로딩 스켈레톤의 위치, 의의 및 사용 예
- 답변 요약 :1. 스켈레톤 UI의 위치: 콘텐츠 컨테이너 내부, 상태 전환 제어
            2. 스켈레톤 UI의 의의: 체감 대기 시간 단축, 레이아웃 안정성 유지 (CLS 방지)
            3. 대표적인 사용 예: 동영상 및 미디어 플랫폼, 소셜 미디어 피드, 이커머스 및 정보 보드
            4. 기초 문법
- 채택 여부 :답변을 채택하여 다양한 방식으로 고심한 끝에 극적으로 문제를 해결했습니다.