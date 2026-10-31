# 하나비 법적 고지

Play 스토어 등록정보와 앱이 가리키는 공개 문서를 둔다.

이 저장소가 정본이다. 개발 서버가 아니라 GitHub Pages 에 두는 이유는 하나다 --
Play 심사와 이용자가 언제든 열 수 있어야 하는데, 개발 서버는 꺼지는 물건이다.

| 문서 | 주소 |
|---|---|
| 이용약관(2026-10-01 공고, 앱에서 동의한 때부터 적용) | https://idol-attention.github.io/hanabi-legal/terms.html |
| 개인정보처리방침(지금 시행 중, 2026-10-31 시행판) | https://idol-attention.github.io/hanabi-legal/privacy.html |
| 같은 판(10-01 공고·10-12 다시 공고 때 주소, 내용은 privacy.html 과 같게 둔다) | https://idol-attention.github.io/hanabi-legal/privacy-20261031.html |
| 이전 방침(2026-09-30 시행, 10-30 까지 적용) | https://idol-attention.github.io/hanabi-legal/privacy-20260930.html |
| 공지(약관 변경·점검·종료 알림, 서버와 따로 둠) | https://idol-attention.github.io/hanabi-legal/notice.html |
| 계정 삭제 요청(Play 데이터 보안 양식의 삭제 URL) | https://idol-attention.github.io/hanabi-legal/delete-account.html |
| 이전 방침(2026-08-07 시행) | https://idol-attention.github.io/hanabi-legal/privacy-20260807.html |

내용을 고치면 이 저장소에 커밋한다. 앱이 수집하는 항목이나 데이터를 보내는 곳이
달라지면 문서의 시행일도 함께 고친다.

처리방침: 지금 시행 중인 판은 privacy.html(2026-10-31 시행, 10-01 공고·10-12 다시 공고). privacy-20261031.html 은 같은 내용의 옛 주소라 privacy.html 을 고치면 같이 복사한다. 이전 판 privacy-20260930.html 은 9-30~10-30 적용. 운영자 아이돌 어텐션(대표·보호책임자 곽용진, 개인사업자 473-03-04113, 2026-10-20 등록, 간이과세자, Play 개발자 계정 주인), 문의 aqtg674111@gmail.com. URL 은 그대로 둔다.

10-31 교체(끝남): privacy.html 을 privacy-20260930.html 로 옮기고(맨 위 개정 예고·정정 안내는 남김), privacy-20261031.html 내용을 privacy.html 로 복사한 뒤 맨 위 「10월 31일부터 적용」 안내를 걷고(추가 공고 링크 한 문장은 남김) 14장 이전 판 링크를 privacy-20260930.html 로 고친다. notice.html·terms.html 의 링크도 확인한다. 함께 한 일: 제7조 서버 이전 문장을 실제 날짜(10-28)로 고치고, 공지의 옛 「지금 시행 중인」 링크 3곳을 privacy-20260930.html 로 돌렸다.

처리방침을 바꿀 때: 이전 판을 `privacy-YYYYMMDD.html` 로 남기고 적용 기간을 적는다(2026 개인정보 처리방침 작성지침 24번). 중대한 변경은 notice.html 에 대조표로 알린다(같은 지침). 시행 7일 전(불리하면 30일 전) 공고와 이메일 개별 통지는 처리방침 14장의 자체 약속이다.

다시 공고(2026-10-12 게시): 10-01 공고한 privacy-20261031.html 을 크랙(뤼튼 통합 처리방침 2026-09-28판)의 제1조~제13조 형식으로 다시 짜고, 서버 전체 Vultr 이전·양하정 위탁 종료·Deep Infra·Aivis·ElevenLabs(예비 음성)·Apple 로그인·턴제·구매 기록 5년 보존·쉬기 2시간을 더했다. 10-01 공고판 원문은 privacy-20261031-notice1001.html 로 남긴다(적용되지 않은 판). 공지 앵커 `2026-10-12-privacy`. 변경 조항은 크랙처럼 「지체 없이 홈페이지 고지」(공고 당일 적용 가능, 10-12 용진). 게시와 함께 기존 이용자에게 이메일 한 통(9-30판 약속).

서버 이전·업체 전환이 실제로 일어나거나 되돌릴 때마다: 공지 페이지에 날짜를 먼저 알리고, privacy-20261031.html(10-31 뒤에는 privacy.html) 제9조 「적용 상태」 줄과 notice.html 다시 공고의 「지금 상태」 줄을 고친다. ElevenLabs 를 켤 때는 업체 계정의 데이터 사용 설정을 끈다.

사업자 정보(2026-10-25 개정): terms.html 「운영자 정보」와 index.html 에 같은 표가 있다. 둘 다 고친다. 전화번호 010-3008-3661(2026-10-25 용진). 호스팅서비스 줄은 서버를 Vultr 로 옮긴 날 「그 전에는 …」 문장을 걷는다. 통신판매업 신고는 간이과세자 면제(공정위 고시 제2조 제1항 제2호) — 일반과세자로 바뀌면 신고하고 번호를 적는다. 약관을 바꾸면 서버 `TERMS_VERSION`(account_api 설정, 기본 "2026-10-01")을 개정일로 올려야 앱이 다시 동의를 받는다.
