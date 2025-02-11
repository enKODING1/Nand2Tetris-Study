# Nand2Tetris
<밑바닥부터 만드는 컴퓨터 시스템> with [@enkoding1](https://github.com/enkoding1)
- The Elements of Computing Systems

# 목차
- [x] 1. 불 논리
- [x] 2. 불 연산
- [x] 3. 순차 논리
- [x] 4. 기계어
- [x] 5. 컴퓨터 아키텍처
- [x] 6. 어셈블러
- [x] 7. 가상머신: 스택 산술
- [x] 8. 가상머신: 프로그램 제어
- [x] 9. 고수준 언어
- [x] 10. 컴파일러: 구문 분석
- [x] 11. 컴파일러: 코드 생성
- [x] 12. 운영체제

# Reference 
- [Nand2Tetris](https://www.nand2tetris.org/)
- [밑바닥부터 만드는 컴퓨팅 시스템](https://blog.insightbook.co.kr/2019/03/29/%EB%B0%91%EB%B0%94%EB%8B%A5%EB%B6%80%ED%84%B0-%EB%A7%8C%EB%93%9C%EB%8A%94-%EC%BB%B4%ED%93%A8%ED%8C%85-%EC%8B%9C%EC%8A%A4%ED%85%9C/)

# 1장 불 논리
> 2022.10.10

<img src="https://user-images.githubusercontent.com/41976906/202856400-66601f3f-82f5-4969-a9a7-f7fa2bdd57eb.jpeg" width="50%">

- [x] Xor
- [x] Not16
- [x] Mux
- [x] DMux
- [x] Mux16
- [x] Mux4Way16

# 2장 불 연산
> 2022.10.22

<img src="https://user-images.githubusercontent.com/41976906/202856459-3b682a87-3848-4a36-9c24-2fa0a1a5174b.jpeg" width="50%">
<img src="https://user-images.githubusercontent.com/41976906/197333807-ecf28df9-4d9f-44e8-80a6-d81690660da3.PNG" width="70%">

- [x] HalfAdder
- [x] FullAdder
- [x] Inc16(증분기)
- [x] ALU (6 opcodes)

# 3장 순차 논리
> 2022.10.29

<img src="https://user-images.githubusercontent.com/41976906/202856489-28ba1b68-e617-4a0b-8224-381ccebe01a4.jpeg" width="50%">

- [x] 1 Bit register
- [x] 16 Bit register
- [x] RAM8 (16 bit register * 8)
- [x] PC(Program Counter)

# 4장 기계어
> 2022.11.05 


<img src="https://user-images.githubusercontent.com/41976906/200116986-42a556be-9719-4f65-af7d-71a9e142e505.PNG" width="80%">



- [x] Mult.asm (곱셈 프로그램)
- [x] Fill.asm (I/O 조작 프로그램)

# 5장 컴퓨터 아키텍처
> 2022.11.20
 
<img src="https://user-images.githubusercontent.com/41976906/202898411-a470c44d-8d74-43b9-b0c6-65d0f3c4fd02.jpg" width="50%">

- [x] Memory 
- [x] 16-bit 6-opcode CPU
- [x] Computer Chip

# 6장 어셈블러
> 2022.12.04

<img src="https://user-images.githubusercontent.com/65354945/205482487-b98c182b-20c4-4131-b0c7-705ffac8ea3d.PNG" width="70%"><img src="https://user-images.githubusercontent.com/65354945/205482904-62d4a41b-f70e-49fb-b518-b52dd4b9b143.png" width="30%">


- [x] Assembler (python)
  - [x] Add.asm
  - [x] Max.asm
  
# 7장 가상머신: 스택 산술
> 2022.12.28

reference. [xctom/Nand2Tetris](https://github.com/xctom/Nand2Tetris/tree/master/projects/07)

<img src="https://user-images.githubusercontent.com/65354945/209752310-362c71b9-e286-4eeb-b8cf-5128e88e5bb6.PNG" width="70%">

- [x] VM-Translator (python)
  - [x] SimpleAdd.vm
  - [x] StackTest.vm
  - [x] BasicTest.vm
  - [x] PointerTest.vm
  - [x] StaticTest.vm
  
  
  
# 8장 가상머신: 프로그램 제어
> 2023.01.07

- [x] VM-Translator (python)
  - [x] ProgramFlow/BasicLoop
  - [x] ProgramFlow/FibonacciSeries
  - [x] FunctionCalls/SimpleFunction
  - [x] FunctionCalls/FibonacciElement
  - [x] FunctionCalls/StaticsTest

# 9장 고수준 언어
> 2023.01.07

<img src="https://user-images.githubusercontent.com/65354945/211140628-5e9dd2b7-090b-43d6-9d06-71d4faa0a18d.PNG" width="70%">
<img src="https://user-images.githubusercontent.com/65354945/211140626-5e63a834-1b77-42cf-bd90-f43d42243379.PNG" width="70%">

# 10장 컴파일러: 구문 분석
> 2023.01.14

<img src="https://user-images.githubusercontent.com/65354945/212470112-a8536fb1-9ea8-4a15-9eac-d50ca40f7c10.png" width="70%">

- [x] JackAnalyzer

# 11. 컴파일러: 코드 생성
> 2023.02.04

<img src="https://user-images.githubusercontent.com/41976906/216754076-969aeef2-91dc-4fc4-a7a6-a07abbdeadd2.png" width="70%">

- [x] Seven
- [x] ConvertToBin
- [x] Square
- [ ] Average
- [ ] Pong
- [ ] Complex Array

# 12. 운영체제
> 2023.02.11

- [x] Array.jack
- [x] Math.jack
- [x] Memory.jack
- [x] Sys.jack
- [ ] Keyboard.jack
- [ ] Screen.jack
- [ ] Output.jack
- [ ] String.jack
