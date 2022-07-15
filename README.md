# GrooVAE
* Groove MIDI Dataset을 이용하여 4마디에 해당하는 드럼 샘플을 뽑아내기
* 수행 기간 : 22.07.13 19:00 ~ 22.07.15 19:00
* 진행 과정 : 전처리 > 학습 > 생성
* 논문 정리 : https://www.notion.so/ttpwd/Deep-dive-9bb9e68780e94ff384c283b67acb39b3
------
## 1. 전처리
* encoder를 사용하여 미디(.midi)를 vector(tfrecord)로 변환

### (1) 직접 전처리
 * 데이터 로드
 * tfrecord로 저장

### (2) magenta의 전처리된 코드를 불러오기
* https://github.com/magenta/magenta/blob/main/magenta/models/music_vae/data.py
* https://github.com/magenta/magenta/blob/main/magenta/models/music_vae/preprocess_tfrecord.py
 
## 2. 학습
### (1) pretrained-model을 사용 (.py)
* 참고 https://colab.research.google.com/github/magenta/magenta-demos/blob/master/colab-notebooks/MusicVAE.ipynb

### (2) GrooveConverter 클래스 
* 참고 https://github.com/magenta/magenta/blob/main/magenta/models/music_vae/data.py


## 3. 생성
* decoder를 사용

## 4. 샘플 확인

## 5. 회고
* 미디 데이터, 비트/마디 개념
------
### 참고자료
* 코드: https://github.com/magenta/magenta/tree/master/magenta/models/music_vae
* 논문: https://arxiv.org/pdf/1803.05428.pdf
* 데이터: https://magenta.tensorflow.org/datasets/groove
