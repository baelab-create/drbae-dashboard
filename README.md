# 닥터배 대시보드

본사 전용(구글 로그인) 납품처 분포 지도 + 전체 발송처 목록 + 파트너 배정.

- 데이터: Firestore `private/mapdata` (포장 PC → drbae-map 비공개 저장소 → 워크플로가 게시). 이 저장소에는 HTML만 있고 데이터 파일이 없습니다.
- 목록 필터: 전체 / 본사 직거래 / 파트너별. 각 발송처 배지를 눌러 파트너 거래처에 별칭으로 연결.
- `core.js`는 baelab-create/drbae-ledger의 `shared/core.js` 사본 (매칭·정규화 로직 공유).
