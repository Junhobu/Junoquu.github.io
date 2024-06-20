# 07_튜플, 딕셔너리, 세트, 문자열

---

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled.png)

```python
n_list=[80,20,20,30,60,30]

result=sorted(set(n_list))
print(result)
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%201.png)

```python
my_dict={x:x**2 for x in range(1,11)}
print(my_dict)
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%202.png)

```python
d={'Apple':1, 'Banana':2, 'Grape':3}

for key,value in d.items():
    print(f'{key} -> {value}')
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%203.png)

```python
d={1:10,2:20,3:30,4:40,5:50,6:60}

n=int(input('키를 입력하시오 : '))
if n in d:
    print(f'키 {n}은 딕셔너리에 있습니다.')
else:
    print(f'키 {n}은 딕셔너리에 없습니다.')
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%204.png)

```python
myDict = {'옷':100,'컴퓨터':2000,'모니터':320}
result = 0

for value in myDict.values():
    result += value
    
print(result)
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%205.png)

```python
colors = ['red', 'green', 'blue']
values = ['#FF0000', '#008000', '#0000FF']
mydict = dict(zip(colors,values))

print(mydict)
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%206.png)

```python
date_dict={}

while True:
    date=input('날짜를 입력하시오 : ')
    if date.lower() == 'q':
        break
    
    plan=input('일정을 입력하시오 : ')

    if date not in date_dict:
        date_dict[date]=[]
    date_dict[date].append(plan)

    print(date_dict)
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%207.png)

```python
Month=['January','February','March','April','May','June',
       'July','August','September','October','November','December']

while True:
    num=input('달의 번호 : ')

    if num.lower()=='q':
        break
    
    print(f'달의 번호 : {Month[int(num)-1]}')
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%208.png)

```python
first_string=set(input('첫 번째 문자열 : '))
second_string=set(input('두 번째 문자열 : '))
intersection_string=list(first_string&second_string)
result=' '.join(intersection_string)
print(f'모두 포함된 글자 : {result}')
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%209.png)

```python
first_set=set(input('첫 번째 세트 : ').split())
second_set=set(input('두 번째 세트 : ').split())
intersection_set=sorted(list(first_set-second_set)+list(second_set-first_set))
result=' '.join(intersection_set)
print(f'모두 포함된 글자 : {result}')
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%2010.png)

```python
problems = {'파이썬' : '최근에 가장 떠오르는 프로그래밍 언어',
            '변수' : '데이터를 저장하는 메모리 공간',
            '함수' : '작업을 수행하는 문장들의 집합에 이름을 붙인 것',
            '리스트' : '서로 관련이 없는 항목들의 모임'}

problem='최근에 가장 떠오르는 프로그래밍 언어'
print('다음은 어떤 단어에 대한 설명일까요?')
print(problem)
print('(1)파이썬 (2)변수 (3)함수 (4)리스트')

string=input()

if string in problems.keys() and problem == problems[string]:
    print('정답입니다!')
else:
    print('오답입니다.')
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%2011.png)

```python
string=input('문자열을 입력하시오 : ')
ban=input('금칙어를 입력하시오 : ').split()

for i in ban:
    string=string.replace(i,'*'*len(i))
print(string)
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%2012.png)

```python
string_dict={}
string=input()

letters=sum(1 for x in string if x.isalpha())
digits=sum(1 for x in string if x.isdigit())

string_dict['LETTERS']=letters
string_dict['DIGITS']=digits
print(f'"{string}" -> {string_dict}')
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%2013.png)

```python
m,d,y=input().split('/')
result=y+m+d
print(result)
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%2014.png)

```python
studentList={'Park':'Korea',
             'Sam':'USA',
             'Sakura':'Japen'}
for k,v in studentList.items():
    print(f"Hi! i'm {k}, and i'm from {v}.")
```

![Untitled](07_%E1%84%90%E1%85%B2%E1%84%91%E1%85%B3%E1%86%AF,%20%E1%84%83%E1%85%B5%E1%86%A8%E1%84%89%E1%85%A7%E1%84%82%E1%85%A5%E1%84%85%E1%85%B5,%20%E1%84%89%E1%85%A6%E1%84%90%E1%85%B3,%20%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%A7%E1%86%AF%20b8beac30f9b5488495c1fd68356b1cbb/Untitled%2015.png)

```python
import random as ran

encrypt='abcdelghijklmnopqrstuvwxyz01234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?'
result=''.join(ran.sample(encrypt,8))
print(result)
```