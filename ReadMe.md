# MFC

#Case 1
 - 'X86' 모듈 컴퓨터 종류가 'x64' 대상 컴퓨터 종류와 충돌합니다
 - 컴파일러와 대상 환경이 안 맞는 경우 나오는 메시지
 - 조치 : 대상 환경과 컴파일러 환경 일치
   - 출처: https://life-with-coding.tistory.com/75 [코딩젤리:티스토리]

#Case 2
 - MSB8041
   - 빌드 관련하여 MFC/ATL 라이브러리 설치 안되어 있는 경우
   - 조치 : 관련된 MFC/ATL 라이브러리 설치
     - 출처 : https://learn.microsoft.com/ko-kr/visualstudio/msbuild/errors/msb8041?view=vs-2022

#Case 3
 - C2668
   - vs2015 이후 오버로딩에 대한 규칙이 엄격 해지면서 발생하는 에러
   - 에러 메시지 : '함수이름':오버로드된 함수에 대한 호출이 모호합니다.
   - 조치 : 명시적 캐스트 추가
      - 관련 내용 : https://westwoodforever.blogspot.com/2017/08/c2668-abs.html
