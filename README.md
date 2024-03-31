# Linux_PJT

<h4> • C언어를 통한 Shell과 SSD 구현💾 </h4>


<h6>SSD 제품을 테스트 할 수 있는 Test Shell 을 제작 <br>
1. SSD 를 가상으로 프로그래밍으로 구현한다. <br>
2. Test Shell 프로그램을 제작하여 SSD 동작을 테스트 할 수 있다. <br>
3. 다양한 Test Script를 제작한다. <br>

<br>

• Read 명령어와 Write 명령어만 존재 <br>
• LBA 단위는 4 Byte (실제로는 4KB 이지만, 만들 최소 저장공간 사이즈는 4 Byte) <br>
• LBA 0 ~ 99 까지 100 칸을 저장할 수 있다. <br>
• 총 400 Byte를 저장 할 수 있는 가상 SSD 를 구현 <br>
• 저장할 수 있는 값은 0x00000000 ~ 0xFFFFFFFF 이다. <br>
• 입력 받은 매개변수가 유효성 검사 수행 <br>
• 파라미터의 Format이 정확해야 함. <br>
• A ~ F, 0 ~ 9 까지 숫자 범위만 허용 <br>
• 없는 명령어를 수행하는 경우 "INVALID COMMAND" 을 출력 (Segment Fault 방지) <br>
</h6>

<h5> Shell 명령어 예시</h5>

<H6>
  • Read [LBA] : LBA에 저장되어 있는 것을 읽는다. <br>
  • Write [LBA] [Value] : LBA에 해당 Value를 저장한다. <br>
  • Fullwrite [Value] : 모든 LBA에 해당 Value를 저장한다. <br>
  • Fullread : 모든 LBA를 읽는다<br>
  • help : 명령어에 대한 설명을 출력한다. <br>
  • exit : shell을 종료한다. <br>
</H6>

 
