```
SPDX-License-Identifier: MIT
```

예외: `assets/` 폴더 아래의 폰트 및 인게임 에셋은 각각 스포카와 넥슨의 저작물입니다.

# Maplestory Timer-NG

메이플스토리 인게임 화면 캡쳐, 파싱 및 시간 측정 프레임워크입니다.

original project : https://github.com/cr0sh/maple-timer-ng

# Disclaimer (홈페이지 발췌)

- 이 프로그램 및 사이트는 넥슨 코리아와 무관합니다.
- 이 프로그램은 넥슨의 정식 인가를 받지 않았습니다.
- **이 프로그램을 사용하여 생기는 모든 불이익은 사용자 본인에게 있습니다.**
- 해당 프로그램의 사용 가능 여부에 대해 자체적으로 [운영 정책](https://maplestory.nexon.com/Common/Footer/OperationPolicy)
과 [이용 약관](https://member.nexon.com/policy/stipulation.aspx)을 검토한 결과, _아직까지는_ 해당 프로그램이 제재 대상이 아닌
것으로 결론내렸습니다. 이는 고객센터에서 회신한 답변의 내용에도 포함되어 있습니다.
    - 2021.04.17 기준 운영정책 발췌:

        [4.3] 비정상적인 게임 이용 : 불법프로그램 제작/유포
        
        불법프로그램을 제작, 유출 , 판매하거나 이를 시도한 경우
        
        * 불법프로그램 예시
            ① 사냥/거래/채팅/특정 값 입력 등 같은 행동을 자동으로 반복해주는 프로그램, 기기 또는 장치
            ② 클라이언트를 동시에 여러 개 실행시키는 멀티로더 등의 프로그램, 기기 또는 장치
            ③ 게임이 서버와 주고 받는 네트워크 패킷을 저장/감청/수정하는 프로그램, 기기 또는 장치
            ④ 게임의 정상적인 운영을 방해할 목적으로 제작된 것으로 회사가 제공 또는 승인하지 않은 컴퓨터 프로그램, 기기 또는 장치 
    - 2021.04.17 기준 이용 약관 발췌:

        제5장 제24조 (서비스이용제한 및 계약해지)
        
        ③ 회사는 회원이 다음 각 호에 해당하는 경우, 제11조 제2항의 방법 또는 기타 유효한 수단을 통해 해당 회원에게 통지하고 각 게임별 운영정책에 의거하여 해당 사유가 해소될 때까지 회원의 서비스 이용을 중지 또는 제한하는 등 합당한 조치를 취할 수 있습니다. 단, 각 게임별 운영정책에 규정되지 않는 사항에 대해서는 사전 경고 후 본 약관에 의거하여 합당한 조치를 취할 수 있습니다.
        
            1. 넥슨 회원 가입 시 등록한 개인정보의 일부가 허위이거나 타인의 개인정보를 도용한 경우
            2. 사이트 및 게임 내에서 타인에게 불쾌감을 주는 행위를 할 경우
            3. 원활한 게임 진행 및 운영을 방해하는 경우
            4. 회사가 허락하지 않은 프로그램의 사용 및 배포, 시스템의 버그이용, 해킹 또는 기타 시스템을 훼손시키려는 행위를 할 경우
            5. ID 및 비밀번호의 유출로 인하여 제3자에 의한 부정 사용 등이 발생한 경우
            6. 본 약관 및 회사의 타 약관에 의해 ID 사용이 중지 또는 제한된 경우
            7. 본 약관 제22조 제2항의 제1, 4, 7, 11, 17, 18, 20호를 제외한 각 호 사항을 위반한 경우
- 제작자가 메이플스토리 고객센터에 문의한 결과 답변은 다음과 같습니다. (원문에서 강조 표시 삽입됨)

        메이플스토리를 이용하는 과정에 화면을 인식하는 프로그램 
        또는 메이플스토리에 영향을 미칠 수 있는 프로그램을 
        함께 구동하는것은 권장하지 않습니다. 
        
        메이플스토리는 단독 실행을 부탁드리며, 
        ***현재는 정상적으로 이용하실 수 있지만***, 
        추후 문제가 있는 프로그램으로 지정되는 경우 불이익이 발생할 수 있습니다.

## Features

- 일격필살 / 보스슬레이어 코어 시간 측정
- (엔버용) 스포트라이트 / 옵드 시간 측정

## Credits

- Part of `winscr` module comes from [screenshot-rs](https://github.com/robmikh/screenshot-rs).
