# 투기왕 킹콜로서스 — 메가드라이브 한글 패치

일본판 《투기왕 킹콜로서스》의 대사·메뉴·시스템 문구와 이름 입력을 한글화한 비공식 패치입니다.

## 다운로드

[v1.0.0 배포 페이지](https://github.com/kilk96/king-colossus-korean-patch/releases/tag/v1.0.0)에서 **king-colossus-ko-v1.0.0.zip**을 내려받아 주세요. 원본 게임 파일은 포함하지 않습니다. `Source code` 압축 파일은 받지 않으셔도 됩니다.

보유하신 일본판의 헤더 없는 BIN 원본에 xdelta **3.2 이상**으로 적용해 주세요. ZIP에 자세한 적용 안내, 결과 파일 확인값과 글꼴 라이선스가 들어 있습니다.

- 원본 크기: 1,048,576바이트
- 원본 SHA-256: `c318d3e353e51cdcd6633b68dd6f2701d4cabfdcb6d4393ee6a9bfaa97a50194`

SHA-256은 지원하는 원본과 파일 내용이 같은지 확인하는 값입니다. SMD 파일은 직접 사용할 수 없으며, 확장자만 바꾸어도 지원 형식으로 바뀌지 않습니다.

## 한글판 화면

![한글 이름 입력](https://github.com/kilk96/king-colossus-korean-patch/releases/download/v1.0.0/01-name-entry.png)
![한국어 대사](https://github.com/kilk96/king-colossus-korean-patch/releases/download/v1.0.0/02-dialogue.png)
![상태와 장비](https://github.com/kilk96/king-colossus-korean-patch/releases/download/v1.0.0/03-status.png)
![저장 선택](https://github.com/kilk96/king-colossus-korean-patch/releases/download/v1.0.0/04-save-select.png)

## 번역·검증 범위

대사·선택지·메뉴·상태·장비·저장·인명·투기장 관련 문구를 적용했습니다. 이름은 준비된 한글 109종에서 최대 4글자를 선택할 수 있습니다. 타이틀 로고와 `NAME ENTRY`, `CLR/DEL/END`, `HP/MP` 등 원래 영문 표기는 유지합니다.

제작자가 엔딩까지 진행하고 엔딩 버그 수정과 이름 입력을 확인했습니다. 엔딩의 두 분기와 이름 입력·저장·재시작 후 불러오기도 별도로 검증했습니다. 확인한 환경은 BizHawk 2.11.1 / GPGX입니다. 모든 조건별 장면과 실제 기기·다른 에뮬레이터까지 확인하지는 못했습니다.

## 알려진 문제와 저장 안내

- 장비창을 겹쳐 열었다 닫을 때 순간 글자 변형과 간헐적인 입력 지연이 남아 있습니다. 투기장 무기 구매·아이템 사용 중 겹치는 창의 글자 변형 제보는 추가 확인이 필요합니다.
- 일본어 가나 이름으로 저장한 게임은 이름이 다른 글자로 표시될 수 있습니다. 새 게임을 권장하며 기존 저장은 백업해 주세요.
- 구버전 에뮬레이터 순간 저장의 호환은 보장하지 않습니다.

## 문제 제보

사용하신 에뮬레이터, 패치 버전과 문제가 발생한 장면을 알려 주세요. 화면 캡처를 함께 보내 주시면 도움이 됩니다. 원본·패치 적용 완료 게임 파일은 첨부하지 말아 주세요.

원작 게임과 이미지의 권리는 각 권리자에게 있으며 본 패치는 원작사와 관계없는 팬 번역입니다. 달무리 글꼴을 사용했으며 글꼴 라이선스와 변환 안내는 배포 ZIP에 포함했습니다.
