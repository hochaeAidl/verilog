# Verilog
HDL, Hardware Description Language,을 이야기 하면 VHDL과 Verilog HDL(이하 verilog)을 이야기 하게 된다.

여기서 Hardware(이하 HW)는 작게는 digital logic circuit에서 시작해서 SoC까지 포함하게 된다. 즉, IC를 설계하는데 회로를 그리는 것이 아니라 프로그래밍 언어와 같이 기술하고 이를 합성(synthesis)하여 구현하는 것이다.

Verilog의 역사를 간단히 살펴 보면,

- 1984년 Gateway Design Automation이 처음 소개
- 1989년 Cadence가 Verilog-XL simulator를 Gateway로 부터 구매
- 1990년 Cadence가 Verilog 공개 version 배포
    - Open Verilog International(OVI) 결성: 표준 관리
- 1993년 OVI v-2.0 배포
- 1995년 IEEE standard 1364로 등록됨
- 2001년 IEEE 1364-2001
- 2002년 IEEE 1364.1
- 2005년 IEEE 1364-2005
- 2009년 IEEE 1800-2009: IEEE에서 system verilog와 합침   

Verilog를 공부한다면, IEEE 1364-2005를 기준으로 시작하면 된다.

참고: Vivado 2018.3의 verilog는 2002 version을 기본으로 지원하고 있다. 2005 verion은 2001 version의 오류 수정과 analog 회로 설계부분이 추가된 것으로 기본 logic 설계에서는 2005 version을 참고하여 공부하여도 무방하다. 개인적으로 2005 version을 선호하는 것은 처음서 부터 보기 시작해서인지 좀더 잘 정리되어 있다는 느낌이 있다. 아마 익숙해서 일 것이다.


---
## Standrds
- ## [IEEE-1364-2005](https://www.eg.bucknell.edu/~csci320/2016-fall/wp-content/uploads/2015/08/verilog-std-1364-2005.pdf)
- ## [IEEE-1364-2001](https://inst.eecs.berkeley.edu/~cs150/fa06/Labs/verilog-ieee.pdf)
- ## [IEEE-1364.1-2002](http://www.iuma.ulpgc.es/~nunez/clases-FdC/verilog/Verilog-IEEE-1364.pdf)

## Tools
- ## [vivado](tools/xilinx/vivado.md)

