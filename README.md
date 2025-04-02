# yolov10
# 첫 시간 
![김선호](https://github.com/user-attachments/assets/45cdd34d-b355-43de-b2b9-436fc32bf8bc)
```dash
sdfsdfsdfsdfsdfsfd
```dash

 - CPU (Central Processing Unit)

코어가 적고 일반 컴퓨팅을 위해 특별히 설계되었습니다. CPU는 또한 NAS 의 두뇌로 간주될 수 있으며, 운영 체제와 애플리케이션에 필요한 명령과 프로그램을 실행하는 책임이 있으므로, NAS 시스템과 애플리케이션의 속도는 CPU 성능과 관련이 있습니다.

 - GPU (Graphics Processing Unit)

그리기 작업을 실행하기 위해 전용된 마이크로프로세서인 GPU는 수백 또는 수천 개의 산술 논리 단위(ALU)로 구성되어 있으며, 대량의 계산을 병렬로 처리할 수 있는 능력을 가지고 있으며, 내장 그래픽 칩과 독립형 그래픽 카드로 분류될 수 있습니다.

3D 게임에서 그래픽 렌더링을 위한 공통적인 사용 외에도, GPU는 분석, 딥러닝 , 기계 학습 알고리즘을 실행하는 데 특히 유용하며, 그들의 응용은 확실히 이미지 처리에만 국한되지 않습니다.

- NPU (Neural Network Processing Unit)

  NPU는 인간의 신경 시스템을 모방하는 프로세서를 통해 AI 애플리케이션을 가속화하기 위해 특별히 설계되었습니다. 에너지 효율적이며 장기간 사용에 적합하며, 이미지 생성, 얼굴 인식 등과 같은 지속적인 AI 계산 작업에 이상적입니다.

- TPU (Tensor Processing Unit)

TPU는 기계 학습 작업을 가속화하기 위해 Google이 특별히 개발한 프로세서입니다. GPU와 달리, TPU는 대규모 저정밀 계산을 위해 설계되었습니다. Google의 연구에 따르면, 신경망을 사용한 AI 추론 작업에서 TPU의 성능은 현대의 GPU와 CPU의 15배에서 30배입니다. 그러나, 제한된 제조업체로 인해 수요를 충분히 충족시킬 수 없기 때문에, TPU는 매우 비쌀 수 있습니다.
#####구구단 만들기
```dash
for i in range(1, 10):  # 1부터 9까지 반복
    for j in range(1, 10):  # 1부터 9까지 반복
        print(f"{i} x {j} = {i*j}", end="\t")  # i와 j의 곱을 출력
    print()  # 각 단마다 줄 바꿈
```dash
