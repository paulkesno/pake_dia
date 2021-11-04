# pake_dia
d2r-mods

mod 등록 방법
1.  경로에 mods 폴더 생성 
(eg. ~/Diablo II Resurrected/pake/pake.mpq/data/~) 형태가 되어야함

2. 베틀넷의 게임실행 버튼 옆 기어 아이콘을 눌러 게임설정 > 명령줄 인수 추가 후 "" 사이의 내용 입력(빈칸 포함)
" -mod pake -txt"

mod 설명
1. 마커 추가 *
  : 초록색(*)는 룬워드 베이스이며 se가 함께 있는 경우 에테리얼(무형) 재료를 사용
  : 금색(*)는 주워볼만한 매직 아이템이며, 접두사에 3소켓 or 2스킬 or 부분3스킬 / 접미사에 생명력(100) or 20패캐 or 30달려
  : 매직 갑옷의 경우, 접두사에 4소켓, 접미사에 100라이프
  : 빨간색(*)는 노멀, 매직템 모두 주워볼만한 아이템을 의미

2. 세트 및 유니크 아이템의 경우 ★☆ 특수문자를 표기

3. 아이템 옆 () {} []는 노멀,익셉,엘리트를 의미하며 맨앞 숫자는 맥스방어/공격력, e뒤에 숫자는 에테일시 맥스방어/공격력, @뒤의 숫자는 맥스소켓을 의미 
(단, 아이템 숨렙에 따라 맥스 소켓이 달라짐 > 지옥 난이도에서 드랍한 경우 상관x)

4. 귀환스크롤(TP) 식별스크롤(ID) 포션(HP,MP,RP) 로 축약 (최대량 이하는 - 표기)

5. 골드 표시 삭제

6. 룬 이미지 변경 
  : 이미지 변경/삭제를 원하시는경우 해당파일 변경/삭제 진행
    /data/hd/global/ui/items/misc/rune/

7. 룬 드랍 소리 변경 (움룬 이상이며, 디아3 전설템 드랍 소리)
  : 사운드 변경/삭제를 원하시는경우 해당파일 변경/삭제 진행
    /data/hd/global/sfx/item/
  : 해당 경로에 item_rune_hd 음원 추가 시 옴룬 이하 설정 가능

8. 폰트를 스타2 폰트로 변경
  : 폰트 변경을 원하시는 경우 해당 파일을 변경 (이름이 같아야 함)
    /data/hd/ui/fonts/

9. 호라드릭 및 헬프 이미지 변경
  : 변경/삭제를 원하시는 경우 해당 파일을 변경/삭제 진행
    /data/hd/global/ui/panel/horadric_cube/horadriccube_bg.sprite (+horadriccube_bg.lowend.sprite)
    /data/hd/global/ui/panel/ 폴더안에있는 seonhee_hud1.sprite ~ seonhee_hud10.sprite 파일을 모두 지워주세요




