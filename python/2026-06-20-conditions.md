# 조건문

📅 2026-06-20
🏷️ Python, 조건문

## 오늘 배운 것
✅ if / elif / else 조건문
```
score =95

if score >= 90:
	print("A")
elif score >= 80:
	print("B")
elif score >= 70:
	print("C")
else:
	print("F")
```
✅ and, or, not 논리 연산자
```
speed = 15
fuel = 30

if speed > 10 and fuel > 20:
	print("정상 운항 중")

if speed > 20 or fuel < 10:
	print("경고!")

if not speed > 20:
	print("속도 정상 범위")
```
✅ input()으로 사용자 입력 받기

✅ int()로 문자열을 숫자로 변환
```
days = int(input("전역까지 남은 날:"))

if days >= 20:
	print("아직 멀었다")

elif days >= 10:
	print("거의 다 왔다")

elif days > 0:
	print("이제 곧 전역!")
	
else:
	print("전역!")
```
## 헷갈렸던 점
⚠️ int days → Python은 자료형 안 써도 됨 (days = 29)
→ C# 문법이랑 헷갈림 주의

⚠️ input()은 무조건 문자열로 받아옴
→ 숫자로 쓰려면 int(input())으로 감싸야 함

⚠️ 비교 연산자 오타 (> 를 < 로 씀)
→ 에러 안 나고 그냥 잘못된 결과 나오니까 주의

## 내일 할 것
반복문 (for / while)
