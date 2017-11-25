# 애니메이션 실습

이번 실습은 불꽃 애니메이션에 대한 실습입니다. 강의자료로 주어진 예제에서는 불꽃 애니메이션이 뷰 애니메이션의 일종인 트윈 애니메이션으로 구현되어있습니다.

<img src="figures/animation-graphics-lab.png" width=300px>

* 전체 예제 코드: https://github.com/kwanulee/Android/tree/master/examples/AnimationTest

* 애니메이션 정의 파일: https://github.com/kwanulee/Android/blob/master/examples/AnimationTest/app/src/main/res/anim/fire.xml

* 불꽃 이미지 파일:  https://github.com/kwanulee/Android/blob/master/examples/AnimationTest/app/src/main/res/drawable/fireworks_01.jpg

## 1. ValueAnimator 실습 
* 이 불꽃 애니메이션을 프로퍼티 애니메이션의 ValueAnimator를 이용하여 구현하시오..
[힌트]  
참조코드:  
https://github.com/kwanulee/Android/blob/master/examples/AnimationTest/app/src/main/java/com/example/kwanwoo/animationtest/MainActivity.java#L115-142 (로켓의 ValueAnimator이용 방법과 유사함)

## 2. ObjectAnimator 실습 
* 이 불꽃 애니메이션을 프로퍼티 애니메이션의 ObjectAnimator를 이용하여 구현하시오..
[힌트]  
참조코드:  
https://github.com/kwanulee/Android/blob/master/examples/AnimationTest/app/src/main/java/com/example/kwanwoo/animationtest/MainActivity.java#L86-L100  (로켓의 ObjectAnimator이용 방법과 유사함)

## 3. 자유 애니메이션 
* 이 불꽃 애니메이션에 각자 자유롭게 새로운 애니메이션 이펙트를 추가하시오. (뷰 애니메이션, 프로퍼티 애니메이션 어떠한 것을 사용해도 상관없습니다