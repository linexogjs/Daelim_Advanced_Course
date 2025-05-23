## 실무프로젝트1 (화요일 수업1) 
### 0408 수업 내용

1.

## 정보시스템구축관리 (수요일 수업1)
### 0409 수업내용

1.

## 창의융합프로젝트 (수요일 수업2)
### 0409 수업내용
1. 해시 함수의 충돌
    - 충돌 (collision)
    - 해시 함수는 임의의 길이의 압력으로부터 짧은 길이의 해시값을 출력
    - 입력은 서로 다르지만 같은 출력을 내는 충돌이 존재
    - 만약 같은 출력(해시 값)을 갖는 다른 메시지를 찾아내기가 쉽다면?
        - (예) 서명자는 자신의 서명에 대해 다른 메시지에 대한 서명이라고 우길 수 있음
2. 해시 함수의 응용 분야(1)
    - 소프트웨어 변경 검출
        - 자신이 입수한 소프트웨어의 변경여부 확인
    - 패스워드를 기초한 암호화
    - 메시지 인증 코드
    - 전자서명
    - 의사난수 생성기
    - 일회용 패스워드
3. 난수 생성기
    - 진정한 난수 생성기 (TRNG)
    - (일반적인) 의사 난수 생성기 (PRNG)
    - 암호학적으로 안전한 의사 난수 생성기 (CSPRNG)
    - 해시함수의 종류
        - SHA 계열
            - SHA-1
            - SHA-2
            - SHA-3
        - MD 계열
            - MD 4
            - MD 5
        - 국내
            - HAS-160
4. 인증시스템이란?
    - 인증을 하고자 하는 주체(Subject)에 대해 식별(Identification)하고,이에 대한 인증(Authentication) 서비스를 제공하는 시스템
5. 사용자 식별과 인증 방식
    - 사용자가 알고 있는 것(Something You Know)을 이용
    - 사용자 자체(Something You Are)를 이용
    - 사용자가 가지고 있는 것(Something You Have)을 이용
6. Somthing You Know
    - 사용자가 알고 있는 정보를 이용해 인증하는 것
    - 가장 기본적이고 전통적인 수단
    - 값싸고 편리
    - 패스워드를 안전하게 관리하는 것이 중요
    
## 프로젝트관리 (목요일 수업1)
### 04010 수업내용
1. 요구사항 분석
    - 요구사항 분석과정에서 수행되는 내용
        1. 요구사항 규명
        2. 타당성 조사
        3. 비용과 일정에 대한 제약 설정
        4. 요구사항 정의 문서화
    1. 요구사항 규명
        - 사용자의 관점에서 시스템의 요구사항을 모으는 것
        - 요구사항 분석은 업무 분석으로 불려짐
        - 요구사항 분석은 고객의 요구와 필요가 나오게 된 원인, 배경, 환경 등에 대한 분석을 포함
        - 시스템에 대한 필요가 나오게 된 고객의 내부 환경과 외적 요인을 파악 (환경분석)
            - 내적요인 : 안룍 규모 축소, 기술력을 향상, 생산 증대, 서비스 향상.
            - 외적 요인 : 경쟁, 법규나 제도의 변화, 시장 여건의 변화 등.
    2. 타당성 조사
        - 프로젝트는 주어진 시간과 예산 안에서 시스템을 개발해야 하기 때문에, 가능한 한 빠른 시간 내에 타당성을 평가하는 것이 요구됨
        - 타당성 조사
            - 프로젝트 계획 단계에서 이루어지는 것이 바람직
            - 분석단계에서도 이루어지는 것이 일반적
            - 시스템 개발에 요구되는 시간, 비용, 인력 등의 자원은 시스템의 타당성에 직접적인 영햐잉 있으므로, 자원의 투자와 그 이익을 조사(손익계산)하고 위험에 대한 분석을 수행
            - 경제적 타당성, 기술적 타당성, 법적 타당성, 대체 방안 등에 집중됨
    3. 비용과 일정에 대한 제약 설정
        - 요구사항을 분석하는 분석가(시스템 애널리스트 혹은 시스템 엔지니어)는 응용분야 (예:자판기)에 대한 해박한 지식이 요구되고, 개발비용, 개발일정, 시스템 성능 등에 대한 정확한 예측을 하고있어야 함
        - 포르젝트의 성공적인 수행을 위해서는 프로젝트관리가 매우 중요
    4. 요구사항 정의 문서화
        - 사용자의 요구사항과 시스템의 기능들에 대한 문서화 진행
        - 중요한 산출물 : 요구사항 명세서-> 기능 명세서 혹은 목표 문소라고도 함
        - 분석가가 만든느 경우가 대부분
        - 프로젝트와 관계된 모든 사람이 읽고 이해하기 쉽도록 쓰여져야 함
        - 고객과 개발 회사 간의 약속문서 (제 2의 계약서)
        - 추후에 발생하는 문제와 변화에 대한 책임이 명확히 규명
        - 시스템에 연관된 당사자들이(사용가, 분석가, 설계자, 프로그래머 및 테스터)이 동의/서명하고, 그 다음 단계로 넘어가는 것이 바람직
    5. 요구사항의 정확한 규명
        - 사용자의 관점에서 사용자가 제공받기를 원하는 것이 무엇인지 분명하고 명확하게 밝혀준다는 점에서 매우 중요
        - 요구사항을 정의하고 규명하는데 많은 시간과 노력이 우선 투자 -> 진행 과정에서 발생할 수 있는 막대한 양이 비효율적 시간과 노력 절약
        - 고품질의 소프트웨어를 만들어 내려면 시스템 개발에 앞서 요구사항 분석이 분명하고 명확하게 정의되어야 함
        - 요구사항 분석 단계의 주요 초점은 어떻게가 아니라 무엇
        - 무슨 기능을 수행해야 하는지에 초점을 맞추어 목표를 기술하여, 어떻게 그 기능이 수행될 것인지는 기술하지 않음
    6. what vs how-to
        - 시스템 : 파리 잡는 시스템
            - what: 파리를 잡는다
            - how to : 끈끈이 풀로 잡는다. 파리채로 잡는다. 파리 약으로 잡는다.
        - 시스템 : 정렬하는 시스템
            - what : 학생의 이름을 가나다 순으로 정렬한다.
            - how to : Bubble 정렬을 사용하여 정렬한다.
            - Quick 정렬을 사용하여 정렬한다.
        - 헌법과 법률
            - 헌법과 법률은 개인과 기업 등 사회의 공동체에게 요구하는 사항
            - 기본법 정신은 헌법에 명시되어 있으며 그 외 구체적인 것은 법률에 의거하여 판단
            - 즉, 헌법은 법률을 위한 초기 단계이며 헌법 그 자체만 가지고는 재판하기 어렵다.
    7. 제안서
        - 개발 계획 수립 과정에서 만들어지는 개발 계획서의 일부
        - 시스템의 필요사항을 명시하는 것읗로 문제 해결을 위한 답을 제시하는 것은 아님
        - 상당히 구체적으로 기술되는 경우도 있으나, 일반적으로 문제 이해의 시작점
        - 프로젝트를 계획하거나 계약할 당시 추상적인 시스템의 목적을 기록
        - 구체적인 요구사항이 모두 나열되어 어려우며 완벽하지 못 함
        - 시스템 개발 과정에서 헌법에 해당한다고 볼 수 있음
        - 공식적인 계약은 제안서에 의해 이루어지고, 이때 개발 비용과 기간 등이 계약서에 명시됨
        - 요구사항 분석을 위한 초기 단계의 문서
        - 시스템을 시험하기가 어렵고, 검증할 수 있을 정고로 구체적이지 못한 경우가 대부분
    8. 요구사항 명세서
        - 시스템의 요구사항을 검증할 수 있는 구체적인 법률이 필요한데, 이를 시스템의 요구사항 명세서
        - 사용자가 기대하는 시스템 요구사항을 작성한 문서
        - 주로 사용자 인터페이스, 하드웨어 플랫폼 등 기술적인 명서 사항을 작성한다.
        - 시스템의 기능적 요구사항을 적은 기능적 요구사항 명세서로도 사용되기도 함
    9. 요구사항 분석의 중요성
        - 요구사항 분석은 앞으로 만들 시스템의 목표를 확립하는 중요한 과정
        - 요구사항 명세서는 이 프로젝트에 연관된 사람들 사이 계약서
        - 우수한 품질의 시스템은 개발 목표가 확실하고 책임의 소재가 명확할 때 얻어질 수 있음
        - 목표가 구체적이고 명확할 수록 좋은 품질의 제품을 체계적으로 만들 수 있음
    10. 소프트웨어 개발 설정
        - 제안서에 의해 계약이 이루어지고 난 후 그대로 개발에 들어가는 경우가 많음
        - 개발이 실패로 끝나는 경우 그 이유를 조사하여 보면 업무 분석이 잘못되었다는 대답이 대부분
        - 사용자의 관점과 엔지니어의 관점 혼재
        - 시스템을 분석하고 디자인할 수 있는 전문가의 부족
    