# GrooVAE
* Groove MIDI Dataset을 이용하여 4마디에 해당하는 드럼 샘플을 뽑아내기
* 수행 기간 : 22.07.13 19:00 ~ 22.07.15 19:00
* 진행 과정 : 전처리 > 학습 > 생성
* 논문 정리 : https://www.notion.so/ttpwd/Deep-dive-9bb9e68780e94ff384c283b67acb39b3
------
## 1. 전처리
* encoder를 사용하여 미디(.midi)를 vector(tfrecord)로 변환
 * 데이터 로드
 * 


## 2. 학습


## 3. 생성
* decoder를 사용

## 4. 회고
* 미디 데이터
------
### 참고자료
* 코드: https://github.com/magenta/magenta/tree/master/magenta/models/music_vae
* 논문: https://arxiv.org/pdf/1803.05428.pdf
* 데이터: https://magenta.tensorflow.org/datasets/groove
