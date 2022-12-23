# algorithm

## Lv0
### Swift
#### 1. 두 수의 합
    import Foundation
    
    func solution(_ num1:Int, _ num2:Int) -> Int {
        return num1 + num2
    }    
함수를 정의할 때 'func' 를 이용한다.  
'solution'은 함수의 이름을 의미하고 화살표를 통해 반환데이터 타입을 정한다.

#### 2. 두 수의 차
    import Foundation
    
    func solution(_ num1:Int, _ num2:Int) -> Int {
        return num1 - num2
    }
합 문제와 동일하게 풀었지만 다른 사람들의 풀이를 보니 'guard'라는 것을 사용한 풀이들이 보였다.  
guard란 조건이 false일 때 실행되는 구문이다.
    guard "조건" else
    
형식으로 사용한다.

## 카카오
