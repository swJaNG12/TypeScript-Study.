# 스터디 4주차

> 이 내용은 조현영(제로초)님이 쓰신 <span style="color: yellow">타입스크립트 교과서</span>로 스터디를 한 내용을 바탕으로 작성되었습니다.
> <br /> > <a target="_blank" href="https://www.yes24.com/Product/Goods/121208343" >타입스크립트 교과서(종이책: yes24)</a> <br /> > <a target="_blank" href="https://www.yes24.com/Product/Goods/121811365" >타입스크립트 교과서(ebook: yes24)</a> <br /> > <a target="_blank" href="https://github.com/gilbutITbook/080369" >길벗출판사 GitHub</a> <br /> > <a target="_blank" href="https://www.zerocho.com/books" >저자 블로그</a> <br /> > <a target="_blank" href="https://github.com/ZeroCho" >저자 GitHub</a>

<br>

## 4주차 스터디 목차

---

- [2.14 제네릭으로 타입을 함수처럼 사용하자](#214-제네릭으로-타입을-함수처럼-사용하자)
  - [2.14.1 제네릭에 제약 걸기](#2141-제네릭에-제약-걸기)
- [2.15 조건문과 비슷한 컨디셔널 타입이 있다](#215-조건문과-비슷한-컨디셔널-타입이-있다)
  - [2.15.1 컨디셔널 타입 분배법칙](#2151-컨디셔널-타입-분배법칙)
  - [배열로 제네릭을 감싸면 분배법칙이 일어나지 않게 막을 수 있습니다](#배열로-제네릭을-감싸면-분배법칙이-일어나지-않게-막을-수-있습니다)
- [2.16 함수와 메서드를 타이핑하자](#216-함수와-메서드를-타이핑하자)
  - [함수에서 매개변수 나머지 문법](#힘수에서-매개변수-나머지--문법)
  - [함수에서 매개변수 전개 문법](#함수에서-매개변수-전개--문법)
  - [매개변수 구조분해 할당 시 주의할 점](#매개변수-구조분해-할당-시-주의할-점)
  - [함수 this 타이핑](#함수-this-타이핑)
  - [메서드 this 타이핑](#메서드-this-타이핑)
  - [오버로딩](#오버로딩)
    - [함수 오버로딩](#함수-오버로딩)
    - [인터페이스 오버로딩](#인터페이스-오버로딩)
    - [타입 별칭 오버로딩](#타입-별칭-오버로딩)
- [2.17 같은 이름의 함수를 여러 번 선언할 수 있다](#217-같은-이름의-함수를-여러-번-선언할-수-있다)

<br>