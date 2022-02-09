## 람다함수(익명함수)

![image](https://user-images.githubusercontent.com/74582262/153137045-bd1cc141-1e6b-4b8c-8a65-d3b88d19af77.png)
출처: https://wikidocs.net/22804

람다함수는 결과부분을 `return` 키워드 없이 자동으로 `return` 해준다.

익명함수라는 이름처럼 `lambda` 함수는 함수의 이름을 지정하지 않는다.

```python
# lambda 매개변수 : 표현식
>>> lambda x : x + 1

>>> (lambda x : x+1)(3)
4
```

하지만 함수에 이름이 없고, 저장된 변수가 없기 때문에 다시 사용할 수 없다.

물론, 람다함수도 객체이기 때문에 정의와 동시에 변수에 담을 수 있다.
```python
f = (lambda x,y : x+y)
f(10, 20) # 30
```
