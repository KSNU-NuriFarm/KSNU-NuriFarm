# KSNU-NuriFarm

## **목표 기능**

**1** : 사람이 직접 가지 않아도 작물의 상태를 확인 및 점검

**2** : 온도, 대기습도, 토양습도, 농약 등 작물재배에 필요한 요소를 제어

**3** : 작물을 로봇이 재배 

**4** : 과일의 당분 과육등 다양한 요소를 이용하여 과일의 품질 파악

##요소 평가##

긍정적요소
> - 밭의 구조는 고정
> - 식물의 중심인 줄기는 고정됨
> - 재배되는 작물이 정해져있고 모두 동일함

부정적요소
> - 로봇팔의 기능을 다양화하는 방법
> - 큰 공간의 냉난방을 가능하게하는 방법

## **구조**
![cont](https://github.com/KSNU-NuriFarm/KSNU-NuriFarm/assets/119506516/803dc9ad-cb20-46d7-802d-037e3b7cc410)

**1**. 로드리스 실린더

![silin](https://github.com/KSNU-NuriFarm/KSNU-NuriFarm/assets/119506516/068104ff-9fd0-4f4e-9e61-2295e86af9e6)

**2**. 헤더
헤더는 물이나 씨앗을 담을 수 있는 통과 토양의 수분등을 측정할 수 있는 센서등을 탑제

**3**. 드론(ex.Bugger)
탑제되는 장비는 기본적으로 로봇팔과 카메라, 대기 온습도 센서
카메라는 과일을 촬영하기 위해, 로봇팔은 기본적으로 재배를 위하 가위형태

## **기능 구현**

**1** : 사람이 직접 가지 않아도 작물의 상태를 확인 및 점검
>센서측정위해 드론이 돌아 다니는 동안 촬영한 과일의 사진을 데이터 베이스에 등록후 열람하는 방식

**2** : 온도, 대기습도, 토양습도, 농약 등 작물재배에 필요한 요소를 제어
>토양습도와 농약은 헤더에서 제어
>온도와 대기습도는 드론에서 측정한 데이터를 기반으로 냉.난방기와 연결된 라즈베리파이를 동작시켜 설정 온,습도를 유지

**3** : 작물을 로봇이 재배 

![Korean_Smart_Farms](https://github.com/Sungmyunghoon/smart-farm/assets/112747810/fbefc312-41aa-4c39-a9f9-5423f3635b62)


**4** : 과일의 당분 과육등 다양한 요소를 이용하여 과일의 품질 파악
Segmentation Methods를 사용

![segment1](https://github.com/KSNU-NuriFarm/KSNU-NuriFarm/assets/119506516/eb468d17-c472-4871-8d89-97e87bdff58a)
![segment2](https://github.com/KSNU-NuriFarm/KSNU-NuriFarm/assets/119506516/8ec04e80-a61c-4d97-94fc-76d3075190c0)









