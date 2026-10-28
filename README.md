# AI는 폐렴을 어떻게 보나 — 그리고 어떻게 속았나

흉부 X-ray 폐렴 분류 모델(ResNet18)의 판단 근거를 Grad-CAM으로 시각화하고,
검은 패딩이라는 지름길에 속았던 과정을 3D 스크롤 페이지로 보여주는 프로젝트.

- web/ : 스크롤 페이지 (현재는 합성 이미지 데모)
- notebooks/ : 학습·Grad-CAM 노트북
- data/ : 데이터셋 (GitHub에 올리지 않음)

## Data
Kermany, D., Zhang, K., Goldbaum, M. (2018). Labeled Optical Coherence Tomography (OCT)
and Chest X-Ray Images for Classification. Mendeley Data, V2. doi:10.17632/rscbjbr9sj.2 (CC BY 4.0)
