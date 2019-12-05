

----------
----------
input 받아오기 기본중의 기본이 되도록
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1572009526475_image.png)

![string](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1572009538812_image.png)

----------
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1572009570268_image.png)

![문자 list](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1572009582965_image.png)

----------
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1572009697147_image.png)

![int list](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1572009704816_image.png)

----------
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1572009797402_image.png)

![int 2차원 리스트](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1572009806723_image.png)



----------
자료형
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569343968668_image.png)



- int(3.3)은 실수 3.3을 int 클래스로 된 객체로 만든다는 뜻
- 다른 자료형도 동일

자료형






![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569762270565_image.png)




연산자

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569344069405_image.png)
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569427031364_image.png)
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569427015989_image.png)


input 함수는 입력받은걸 모두 string 으로 받는다.
a=int(a) 이런식으로 완전히 캐스팅 가능.

#input() 함수를 이용하여 받는 형식을 바꾸고싶을땐 형변환클래스를 안에넣어도됩니다.
ex)int 형으로 받고싶을때-> int(input())

----------
print
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569427911883_image.png)


input 에겐 split()이 있고 print에겐 separator가 있다.


https://withcoding.com/64

----------
연산자

Python은 C와 다르게 boolean 자료형 존재
비교연산자는 C그대로 쓰고
비트연산자도 C 그대로 씀
논리연산자는 && || 안됨.('and', 'or' 그대로 쓰셔도 됩니다) &, | 로 가능. 
boolean 자료형이 구현된건 내부적으로 if가 들어있는것 같으니 생각하고 응용.

----------
시퀀스
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569481203685_image.png)


소름돋는 편리함...
그런데 메모리 제한있는 경우라면 불리하지 않을까->현대의 하드웨어에서는 메모리제한을 거의 고려하지않아도 괜찮습니다^^

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569481456135_image.png)



![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569482975493_image.png)


시퀀스 자료형은 모두 다루는 방법이 동일 편리함. 일부예외 range.

list 얘만 값 바꿀수 있음.
range  는 숫자알아서 생성해주는 리스트느낌의 자료형(읽기 전용)

        주의: range(1,10) 하면 1~ 9까지만 생성됨.
        Tip!! range(1,10,2) ==> 1~9 까지 2씩 더해주며 범위내의 숫자를 생성해줍니다. ex)1,3,5,7,9
        Tip!! range(10,0) ==> 10부터 시작해서 0을 제외한 1까지 역순으로 표현해줍니다. ex)10,9,8,…,1

tuple 은 읽기 전용 리스트 느낌의 자료형 (읽기전용) >>>list보다 빠름. 데이터 바꿀필요없으면tuple사용
str  문자열 (읽기전용)

a , b = input().split(‘기준문자열’) 이 list 언팩킹 과정이었음.



![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569483086881_image.png)



![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569483102448_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569483118904_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569483143937_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569483377358_image.png)


시퀀스객체의 요소 개수 반환.

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569483937759_image.png)



시퀀스로 접근.

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569484272946_image.png)


마이너스 인덱스도 있음.





![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569484720890_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569484698812_image.png)





변수 삭제하는것 마냥.

여기까진 시퀀스에대해 알고갈 내용.

----------


슬라이스 기능은 문제풀면서 적용 시퀀스에 대체로 다 적용가능.

슬라이싱연산하면 list 반환함. → 새리스트를 만들어내서 편리함 index는 주의

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569588459675_image.png)


인덱스에는 음수값도 들어갈 수 있다. 뒤에서부터 -1 -2

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569591795708_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569588688203_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569588709466_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569588726404_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569588748591_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569591597357_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569591563924_image.png)

![굉장히 가변적 기능](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569591992245_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569592051011_image.png)


※2차원 리스트를 만들어서 서로 복사해보세요. 그리고 하나를 수정한 결과 나머지 하나도 영향을 주는가 확인해보세요!! 파이썬의 특징이랍니다다!!

파이썬의 특징1
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569760152711_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569760180540_image.png)


→ 일차원 배열은 대입방식으로 하면 변수 하나의 리스트를 두개의 변수가 가리키는 것
→ 요소를 하나하나 복사하면 새로운 리스트 만들어짐











![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569760430632_image.png)









2차원배열은 두가지 방법다 하나의 리스트를 가르키게 하는것..





![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569760458874_image.png)










![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569760729542_image.png)








이건 또 새로운 리스트가 만들어진다.
그냥 받아들이자
이렇게 쓰려면 테스트해보고 써야할듯






![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569760751939_image.png)








이것만 기억!
→ b = a.copy() 이렇게 copy 메서드 사용하면 확실하게 새로운 list 만들수있다.
→ 
→ 반면에 b = a 하면 같은걸 두개의 변수가 가리킴. 








----------
딕셔너리

ㅍ

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569486394294_image.png)


요소에 대한 정보가 포함된 리스트 느낌의 자료형. 느낌만 가지고 나중에 쓰기.

![접근](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569486693166_image.png)

![할당](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569486714525_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569486840003_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569486868766_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569486888930_image.png)

----------
if 문 

파이썬은 들여쓰기 중요.

![젤 마지막 프린트는 else 아님](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569570795330_image.png)
![elif](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569571270529_image.png)
![참고](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569570722614_image.png)



![조건식 아닌값으로.](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569570947424_image.png)
![조건식 아닌값으로.](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569570996357_image.png)

----------
for문
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569571603198_image.png)

![스킬적인 부분](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569571890574_image.png)
![스킬적인 부분](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569571910868_image.png)


사용자에게 받은 input을 쓰는건 C든 파이썬이든 매트랩이든 다 비슷하게 구현.

![C처럼 배열의 길이로 돌릴필요가 없다](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569572104438_image.png)
![다른 시퀀스로 다가능.](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569572153731_image.png)
![이런것도 가능. 문자열도 시퀀스.](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569572188601_image.png)

----------
while 문
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569572362247_image.png)


거의 C랑 동일.
들여쓰기만 잘하면 됨.







- break 랑 continue → C에서 쓰듯이
----------
 <List> 응용 문제풀면서
- 공백 list 만들기 
1. num = []
2. num = list() 리스트 클래스의 생성자 사용. → 이걸로 .copy 대신해도 될듯.
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1572010298982_image.png)








countList 개념 잘 이용하기. ??



![구현없이 쓰다니.](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569683418897_image.png)

완전탐색
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569684418876_image.png)

1. 고려할 수 있는 모든 경우의 수 생성하기
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569689820732_image.png)


print 자리에 다른 코드넣으면 활용도 높을거 같음.





2. 해답 테스트하기
![완전탐색에 자주 쓰일거 같음.](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569689576913_image.png)

Greedy 알고리즘
![나중엔 이해하겠지](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569690070512_image.png)
![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569690148975_image.png)

![](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1569765560502_image.png)



리스트 조작할때 자주쓰는 메서드(method) 공부하자. (메서드는 객체(object)에 속한 function))



map

----------
<tuple> 응용 문제풀면서


----------
<문자열>응용 문제 풀면서


----------
<딕셔너리> 응용 문제풀면서 


----------

표준입출력→커맨트창에서 다루는것
(C에서는 #include <stdio.h> → scanf printf )
파이썬에선 표준입출력함수 다있다. 그래서 좀더 큼 파일이
받아올때 a = intput() 
파일입출력


![20191007 수업때](https://paper-attachments.dropbox.com/s_ECE9D6C84F5D40D46F9C99BDED424F0BA41F546EE9EE2B03BC51A1D9FC128356_1570438614023_image.png)

