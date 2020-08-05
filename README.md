# waterline_detection

예를들어 투명한 컵 안에 들어 있는 액체의 수위가 어느정도인지 파악할 수 있는 기능을 만들어보고 싶다.

이 기능에 Iot 기술을 접목시킨다면 비가 어느정도 기준점만큼 오게 되면 자동으로 액션을 취할 수 있게 만들 수 있다. 

현재는 opencv를 이용한 방법을 찾고 있다.


opencv를 활용한 방법을 찾아보다보니 카메라에 찍힌 화면의 색깔을 구분하고 찾아주는 코드를 찾게 되었다. 

참고한 블로그 -> https://webnautes.tistory.com/1246 
//
참고한 깃허브 -> https://github.com/webnautes/nudapeu/blob/master/opencv-python-006.py

opencv 를 이용해 Roi 부분에서 height 변수가 측정해야 했던 물의 높이이다. 
