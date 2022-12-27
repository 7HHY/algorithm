# algorithm

## Lv0
### Swift
#### [1. 두 수의 합](https://school.programmers.co.kr/learn/courses/30/lessons/120802)
    import Foundation
    
    func solution(_ num1:Int, _ num2:Int) -> Int {
        return num1 + num2
    }    
함수를 정의할 때 'func' 를 이용한다.  
'solution'은 함수의 이름을 의미하고 화살표를 통해 반환데이터 타입을 정한다.

#### [2. 두 수의 차](https://school.programmers.co.kr/learn/courses/30/lessons/120803)
    import Foundation
    
    func solution(_ num1:Int, _ num2:Int) -> Int {
        return num1 - num2
    }
합 문제와 동일하게 풀었지만 다른 사람들의 풀이를 보니 'guard'라는 것을 사용한 풀이들이 보였다.  
guard란 조건이 false일 때 실행되는 구문이다.  
<pre><code>guard "조건" else </code></pre> 형식으로 사용한다.

#### [3. 두 수의 곱](https://school.programmers.co.kr/learn/courses/30/lessons/120804)
    import Foundation
    
    func solution(_ num1:Int, _ num2:Int) -> Int {
        guard (num1 >= 0 && num1 <= 100) , (num2 >= 0 && num2 <= 100) else {
            return 0
        }
        return  num1 * num2 
    }
    
'guard'도 이용해보았다.  
'guard'는 항상 else를 가지기 때문에 'return', 'breake', 'continue', 'throw'를 이용해서 exit시켜야 한다.

#### [4. 몫 구하기](https://school.programmers.co.kr/learn/courses/30/lessons/120805)
    import Foundation
    
    func solution(_ num1:Int, _ num2:Int) -> Int {
        guard (num1 >= 0 && num1 <= 100), (num2 >= 0 && num2 <= 100) else {
            return 0
        }
        return num1 / num2
    }

#### [5. 두 수의 나눗셈](https://school.programmers.co.kr/learn/courses/30/lessons/120806)

#### [6.숫자 비교하기](https://school.programmers.co.kr/learn/courses/30/lessons/120807)

#### [7. 분수의 덧셈](https://school.programmers.co.kr/learn/courses/30/lessons/120808)

#### [8. 배열 두 배 만들기](https://school.programmers.co.kr/learn/courses/30/lessons/120809)

