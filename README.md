# 📚 이자함
> 이펙티브 자바를 완독하기 위해 선수지식을 함께 공부하는 스터디

**:book: Effective Java 3/E Contents**
1. [객체 생성과 파괴](#1-객체-생성과-파괴)
2. [모든 객체의 공통 메서드](#2-모든-객체의-공통-메서드)
3. [클래스와 인터페이스](#3-클래스와-인터페이스)
4. [제네릭]
5. [열거 타입과 애너테이션]
6. [람다와 스트림]
7. [메서드]
8. [일반적인 프로그래밍 원칙]
9. [예외]
10. [동시성]
11. [직렬화]

---

## 1. 객체 생성과 파괴
* [아이템 1. 생성자 대신 정적 팩터리 메서드를 고려하라](/contents/Item_1.md)
* [아이템 2. 생성자에 매개변수가 많다면 빌더를 고려하라](/contents/Item_2.md)
* [아이템 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라](/contents/Item_3.md)
* [아이템 4. 인스턴스화를 막으려거든 private 생성자를 사용하라](/contents/Item_4.md)
* [아이템 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라](/contents/Item_5.md)
* [아이템 6. 불필요한 객체 생성을 피하라](/contents/Item_6.md)
* 아이템 7. 다 쓴 객체 참조를 해제하라
* 아이템 8. finalizer와 cleaner 사용을 피하라
* 아이템 9. try-finally보다는 try-with-resources를 사용하라

## 2. 모든 객체의 공통 메서드
* 아이템 10. equals는 일반 규약을 지켜 재정의 하라
* 아이템 11. euqals를 재정의하려거든 hashCode도 재정의 하라
* 아이템 12. toString을 항상 재정의하라
* 아이템 13. clone 재정의는 주의해서 진행하라
* 아이템 14. Comparable을 구현할지 고려하라

## 3. 클래스와 인터페이스
* 아이템 15. 클래스와 멤버의 접근 권한을 최소화하라
* 아이템 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라
* 아이템 17. 변경 가능성을 최소화하라
* 아이템 18. 상속보다는 컴포지션을 사용하라
* 아이템 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라
* 아이템 20. 추상 클래스보다는 인터페이스를 우선하라
* 아이템 21. 인터페이스는 구현하는 쪽을 생각해 설계하라
* 아이템 22. 인터페이스는 타입을 정의하는 용도로만 사용하라
* 아이템 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라
* 아이템 24. 멤버 클래스는 되도록 static으로 만들라
* 아이템 25. 톱레벨 클래스는 한 파일에 하나만 담아라
