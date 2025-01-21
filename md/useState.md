# useState

useState는 배열을 리턴하는데

`0번째` 원소는 : 상태의 값을 읽을 때 쓰는 데이터

`1번째` 원소는: 상태의 값을 변경할때 쓰는 함수

이 코드가 

    const mode=useState("WELCOME");
    const mode=_mode[0];
    const setMode=_mode[1];

=== 같다. 

      const [Mode,setMode]=useState("WELCOME");


 이 코드를 하나하나씩 설명하자면


+ `Mode`는 0번째 값:  읽는값

+ `setMode`는 1번째의 값: 바뀌는 값

+ `"WELCOME"`은 ustState 인자의 초기값