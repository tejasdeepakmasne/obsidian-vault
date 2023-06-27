codeforces id : tmsunducker

1. problem 4A Watermelon :

submission # : 195123724
```cpp
1.  #include<iostream>

3.  using namespace std;

5.  int main() {
6.      int w;
7.      cin >> w;
8.      if(w != 2 && w%2 == 0) {
9.          cout << "YES";
10.      }
11.      else{
12.          cout << "NO";
13.      }
14.  }
```

submission # : 195123449
```python
1.  w = int(input())

3.  if w==2 :
4.      print("NO")
5.  elif w%2 == 0 :
6.      print("YES")
7.  else :
8.      print("NO")
```

2.  71A Way Too Long Words :

submission # : 195124466
```python
1.  n = int(input())

3.  for num in range(1,n+1) :
4.      word = input()
5.      if len(word) > 10 :
6.          print(f"{word[0]}{len(word)-2}{word[-1]}")
7.      else :
8.          print(word)
```

4. 112A Petya and Strings :

submission # : 195545819

```python
1.  string_1 = input()
2.  string_2 = input()

4.  string_1 = string_1.lower()
5.  string_2 = string_2.lower()

7.  if string_2 > string_1 :
8.      print("-1")
9.  elif string_2 < string_1 :
10.      print("1")
11.  else :
12.      print("0")
```

5. 339A Helpful Maths

submission # : 195551215

```python
1.   problems = input().split("+")

3.   problems.sort()

5.  plus = "+"
6.  sorted_problem = plus.join(problems)

8.   print(sorted_problem)
```
