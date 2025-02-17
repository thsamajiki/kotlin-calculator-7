# kotlin-calculator-precourse 

# 구현할 기능 목록

입력한 문자열에서 숫자들을 추출하여 더하는 계산기를 구현한다.

1. 문자열 입력받기
    - 구분자와 양수로 구성된 문자열을 입력 받는다.

2. 기본 구분자(쉼표, 콜론) 가져오기
    - 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우, 구분자를 기준으로 분리한 각 숫자의 합을 반환한다.

3. 커스텀 구분자 가져오기
    - 문자열 앞부분의 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 사용한다.
    - 예를 들면 "//;\n1;2;3"과 같이 값을 입력할 경우, 커스텀 구분자는 세미콜론(;)이며, 결과값은 6이 반환되어야 한다.
    - 그렇게 추출된 숫자들을 더한다.

4. 사용자가 잘못된 값을 입력할 경우 처리하기
    - `IllegalArgumentException`을 발생시킨 후 애플리케이션은 종료되어야 한다.

5. 출력
    - 추출한 숫자들을 모두 더해서 출력한다.