# ChoreoMaker

pose estimation - openpose : https://github.com/CMU-Perceptual-Computing-Lab/openpose

시연영상(예상결과) 링크 : https://www.youtube.com/watch?v=NC_hW1L0UU0

python
 - run.py : openpose의 코드 일부를 수정해 각 keypoint의 좌표를 csv 파일에 저장
 - pose_numericalization.ipynb : openpose를 통해 얻은 각 관절의 좌표를 통해 각 포즈를 수치화
 
 - video_edit.ipynb : 비디오 파일을 가져와 재생 구간과 재생 속도를 변경
 - music_preprocessing : youtube.dl 등을 통해 음악을 가져와 wav로 변경 및 전처리
 * 기존 코드에서 madmom 도입 및 변경사항으로 코드 변경 중
