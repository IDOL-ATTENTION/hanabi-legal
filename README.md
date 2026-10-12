# 하나비 법적 고지

Play 스토어 등록정보와 앱이 가리키는 공개 문서를 둔다.

이 저장소가 정본이다. 개발 서버가 아니라 GitHub Pages 에 두는 이유는 하나다 --
Play 심사와 이용자가 언제든 열 수 있어야 하는데, 개발 서버는 꺼지는 물건이다.

| 문서 | 주소 |
|---|---|
| 이용약관(2026-10-01 공고, 앱에서 동의한 때부터 적용) | https://idol-attention.github.io/hanabi-legal/terms.html |
| 개인정보처리방침(지금 시행 중, 2026-09-30판 + 10-01 정정 안내) | https://idol-attention.github.io/hanabi-legal/privacy.html |
| 개정 처리방침(2026-10-01 공고, 10-31 시행) | https://idol-attention.github.io/hanabi-legal/privacy-20261031.html |
| 공지(약관 변경·점검·종료 알림, 서버와 따로 둠) | https://idol-attention.github.io/hanabi-legal/notice.html |
| 계정 삭제 요청(Play 데이터 보안 양식의 삭제 URL) | https://idol-attention.github.io/hanabi-legal/delete-account.html |
| 이전 방침(2026-08-07 시행) | https://idol-attention.github.io/hanabi-legal/privacy-20260807.html |

내용을 고치면 이 저장소에 커밋한다. 앱이 수집하는 항목이나 데이터를 보내는 곳이
달라지면 문서의 시행일도 함께 고친다.

처리방침: 지금 시행 중인 판은 privacy.html(2026-09-30 시행, 10-01 정정 안내 추가). 개정판 privacy-20261031.html 은 10-01 공고·10-31 시행(처리 목적이 늘어 기존 판 12장의 「불리한 변경 30일 전」 약속을 따름). 운영자·보호책임자 곽용진(개인 운영, 팀 이름 아이돌 어텐션, Play 개발자 계정 주인), 문의 aqtg674111@gmail.com. URL 은 그대로 둔다.

10-31 에 할 일: privacy.html 을 privacy-20260930.html 로 옮기고(맨 위 개정 예고·정정 안내는 남김), privacy-20261031.html 내용을 privacy.html 로 복사한 뒤 맨 위 「10월 31일부터 적용」 안내를 걷고(추가 공고 링크 한 문장은 남김) 14장 이전 판 링크를 privacy-20260930.html 로 고친다. notice.html·terms.html 의 링크도 확인한다.

처리방침을 바꿀 때: 이전 판을 `privacy-YYYYMMDD.html` 로 남기고 적용 기간을 적는다(2026 개인정보 처리방침 작성지침 24번). 중대한 변경은 notice.html 에 대조표로 알린다(같은 지침). 시행 7일 전(불리하면 30일 전) 공고와 이메일 개별 통지는 처리방침 14장의 자체 약속이다.

다시 공고({추가공고일} 예정): 10-01 공고한 privacy-20261031.html 을 크랙(뤼튼 통합 처리방침 2026-09-28판)의 제1조~제13조 형식으로 다시 짜고, 서버 전체 Vultr 이전·양하정 위탁 종료·Deep Infra·Aivis·ElevenLabs(예비 음성)·Apple 로그인·턴제·구매 기록 5년 보존·쉬기 2시간을 더했다. 10-01 공고판 원문은 privacy-20261031-notice1001.html 로 남긴다(적용되지 않은 판). 게시할 때 자리표시 세 개를 채운다: `{추가공고일}`(게시일), `{추가공고앵커}`(공지 앵커, 예: 2026-10-2x-privacy), `{다시공고30일}`(게시일부터 30일이 되는 날 — ElevenLabs 를 켤 수 있는 첫날이자 옛 7일·30일·이메일 약속이 끝나는 날). 게시 조건: 양하정 위탁 계약 서명, 이메일 한 통(9-30판 약속).

서버 이전·업체 전환이 실제로 일어나거나 되돌릴 때마다: 공지 페이지에 날짜를 먼저 알리고, privacy-20261031.html(10-31 뒤에는 privacy.html) 제9조 「적용 상태」 줄과 notice.html 다시 공고의 「지금 상태」 줄을 고친다. ElevenLabs 는 {다시공고30일} 뒤, 업체가 API 요청을 모델 개선에 쓰지 않는다고 확인한 뒤에만 켠다.
