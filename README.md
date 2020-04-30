# imfine

## 초기 권한 설정
imfine은 미세먼지 측정 모듈을 이용해 수집한 데이터를 서버와 통신하여 저장하기 때문에 초기에 권한 설정이 필요하다

<pre>
<code>
chown groupname:username /var/www/html
sudo usermod -a -G dialout imfine
sudo chmod a+rw /dev/ttyUSB0
</code>
</pre>
#but i'm not fine
#It'll be fine
