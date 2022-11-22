# yolov7_remake

Yolov7을 사용하다가 불편한 부분이 있으면 수정하는 레퍼지토리입니다.

(This is a repository to fix inconveniences while using yolov7.)

-------------------------
### 업데이트 정보(Updata information)
11.20.Sun. => crop function

11.22.Tue. => detection empty(배경 색상으로 변경)

------------------------
### 주요 기능
##### 크롭 기능(crop function)
* 사용하기 위해서는 반드시 save-txt 기능을 실행해야합니다.(To use it, you must use save-txt.)

    `python crop_detect.py --weights yolov7-e6e.pt --source ./img.png --save-txt`

* run > detect > expN > crop folder에 저장됩니다. (Stored in the folder -> run > detect > expN > crop)

* 저장되는 순서는 앞에 번호, 뒤에 파일명입니다. (The first part of the saved image name is the number and the second part is the original image name.)

     `ex. 0_img.png, 1_img.png, ...`

##### 검출 날리기 기능(detection empty function)
* 사용하기 위해서는 반드시 save-txt 기능을 실행해야합니다.

* run > detect > expN folder에 저장됩니다.

