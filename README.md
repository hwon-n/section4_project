# 욕설 탐지 프로젝트
codestates section4 project


## 데이터셋

2runo님의 github에 올려진 curse dataset과 리그 오브 레전드(LoL) 인벤 사이트를 크롤링해서 직접 라벨 설정 후 추가적인 데이터셋으로 사용


## curse_filtering.ipynb

**KoBERT** 모델을 이용해 입력된 문장에 욕설이 포함되어 있는지 확인할 수 있습니다. 
> testModel(model, '문장 입력')
