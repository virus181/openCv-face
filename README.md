Этот проект был выполнен с помощью «Open Source Computer Vision Library», OpenCV. Тут мы сосредоточимся на Raspberry Pi (так, Raspbian как OS) и Python, но я также проверил код на My Mac, и он также отлично работает. OpenCV был разработан для эффектного вычисления и работы в реальном времени. Таким образом, он идеально подходит для распознавания лиц в реальном времени с помощью камеры.
Источник на установку https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/


Чтобы создать полный проект по распознаванию лиц, мы должны работать на 3 очень разных этапах:

Обнаружение лиц и сбор данных
Обучение распознавателя
Распознавание лица
На приведенной ниже блок-схеме показаны этапы:

# OpenCV-Face-Recognition
Real-time face recognition project with OpenCV and Python
<br><br>

<br>
<p><img src="https://github.com/Mjrovai/OpenCV-Face-Recognition/blob/master/FaceRecogBlock.png?raw=true"></p>
