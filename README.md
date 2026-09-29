# 개발자 웹사이트 (GitHub Pages)

용도는 AdMob `app-ads.txt`를 도메인 루트에 두는 것이다. 방침·약관·계정 삭제 안내는 노션에 둔다(2026-09-29 결정).

공개 저장소 `Thunder-punch/Thunder-punch.github.io`에 이 폴더 내용을 그대로 올려 `https://thunder-punch.github.io/`로 게시한다. 이 폴더가 원본이다.

| 파일 | 주소 | 용도 |
|------|------|------|
| `index.html` | `/` | Play Console 개발자 웹사이트. 앱 목록과 연락처 |
| `app-ads.txt` | `/app-ads.txt` | AdMob 판매자 인증. 게시자 ID는 Project36과 같은 AdMob 계정(`pub-7701426527744576`) |
| `oilbook/index.html` | `/oilbook/` | 앱 소개, 개인정보처리방침·이용약관(노션) 링크, 지원 이메일 |

새 앱을 내면 `<앱>/index.html`을 추가하고 루트 `index.html` 목록에 한 줄 넣는다. `app-ads.txt`는 계정당 한 줄이라 앱이 늘어도 그대로다.

Play Console 앱 등록정보의 "웹사이트"에 `https://thunder-punch.github.io/`를 넣어야 AdMob이 `app-ads.txt`를 찾는다. 확인은 AdMob > 앱 > app-ads.txt 탭에서 한다(반영까지 최대 하루 이상 걸릴 수 있다).
