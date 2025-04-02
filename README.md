# yolov10
# 첫 시간 
![김선호](https://github.com/user-attachments/assets/a762d60d-182d-493e-91ac-1102f284fe59)



#####구구단 만들기
```dash
for i in range(1, 10):  # 1부터 9까지 반복
    for j in range(1, 10):  # 1부터 9까지 반복
        print(f"{i} x {j} = {i*j}", end="\t")  # i와 j의 곱을 출력
    print()  # 각 단마다 줄 바꿈
```dash
```dash
# 원하는 구구단을 입력받는 코드
dan = int(input("출력하고 싶은 구구단의 단을 입력하세요 (1-9): "))

# 구구단 출력 코드
print(f"{dan}단 구구단 출력:")
for i in range(1, 10):  # 1부터 9까지 반복
    print(f"{dan} x {i} = {dan * i}")
```dash
