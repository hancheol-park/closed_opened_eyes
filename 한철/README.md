# closed_opened_eyes

데이터 전처리 

https://github.com/kairess/eye_blink_detector를 참고함


데이터 트레이닝

데이터전처리에서 만든 blink_data2.npy를 기본cnn모델에 넣어서 훈련시킴


모델썸머리

![K-001](https://user-images.githubusercontent.com/70885961/100229637-e5e41880-2f67-11eb-8af4-403230408b22.png)

트레인시킨 결과물

![KakaoTalk_20201125_183904168](https://user-images.githubusercontent.com/70885961/100229829-2d6aa480-2f68-11eb-8764-d2e65625c846.png)

모델 테스트

![테스트](https://user-images.githubusercontent.com/70885961/100312379-87fe1200-2ff5-11eb-9db7-2878aa012797.png)
눈을 떳을때 0.9

![테스트2](https://user-images.githubusercontent.com/70885961/100312391-8df3f300-2ff5-11eb-95c8-d2328441ea31.png)
눈을 감았을 때 0

모델 테스트시 http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2 에서 

shape_predictor_68_face_landmarks.dat를 받고 압축을 풀어서 test파일과 같은 위치에 주세요.

https://github.com/kairess/eye_blink_detector를 참고함
