# buckshoot
 
## 1. 프로젝트 이름 및 제작 기간

벅샷룰렛 - 텍스트 기반 턴제 게임

제작기간 12-23 ~ 12-28 

게임설명: 플레이어하고 신 두명에서 가운데에 샷건을 들고 서로 쏴서 상대를 죽이면 된다.

## 2. 게임개요 

게임을 시작할때 플레이어의 계약서 싸인을위해 이름을 입력받는다

그 후 앞에있는 샷건과 플레이어의 체력을 확인할수 있는 체력 확인기계

서로 쏠 샷건 가운데에 한자루 아이템을 둘 수 있는 칸 8칸 등등 있다

최종적으로 어떠한 수단을 써서 신을 이기면된다

## 3.기능목록 

. 게임시작종료 

. 사용자 입력 처리 (번호선택)

. 상태 출력 (플레이어 체력, 스코어, 위치 등)

. 턴마다 선택 시스템(아이템 쓸껀지 총을 나한테 쏠지 상대한테 쏠지)

. 아이템기능(수갑, 담배, 톱, 맥주, 돋보기, 전환기, 핸드폰, 주사기, 알약)

. 상대방 체력을 전부 깎았을경우 승리 플레이어의 체력이 다 달았을경우 패배


## 4 게임흐름

. 게임 시작 화면 출력.

. 플레이어 정보 입력.

. 샷건 탄약 갯수 확인 (공포탄, 실탄)

. 랜덤 아이템 흭득 (최대 8개)

. 아이템을 쓸지 샷건으로 상대를쏠지 나를쏠지 선택

. 공포탄을 나한테 쏠경우 한턴 추가 (반대일경우 상대턴으로)

. 상대에게나 나한테 실탄을 쏠경우 상대턴

. 목표 달성 시 승리 화면 출력.

. 실패 조건 만족 시 패배 화면 출력.

## 5. 사용 데이터 구조

list<> 샷건의 공포탄 실탄여부를 저장 

LinkedList<> 가지고있는 아이템저장 

## 6. 클래스 설계

Player : 플레이어 체력 , 플레이어의 이름, 플레이어 선택지

God : 인공지능(무언갈 구별하는기능), 아이템 사용할지 여부, God 체력

ShotGun: 실탄, 공포탄, 총데미지 

Item : 수갑, 담배, 톱, 맥주, 돋보기, 전환기, 핸드폰, 주사기, 알약

Animation : 각종 애니메이션을 모아두기위한 클래스

BattleSystem: 상대방이 아이템을 맞았는지 여부 체크 (예시 : 수갑)

## 7. 추가구현 아이디어 

. 난이도 선택 기능

. 미친 아이템 모드(아이템을 수치 확률적으로 조정)

## 8. 프로젝트 마감 일정

. 클래스 설계 및 기초 구현.

. 기본 게임 로직 완성.

. 각각 클레스 구현

. 기능 테스트.

. 최종 제출 및 발표 준비.
