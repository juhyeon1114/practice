# Docker 실전 연습 예제입니다.
### Installation
<pre>
cd /home
git clone https://github.com/juhyeon1114/practice
cd practice
</pre>
### Run
<pre>
# Login For Private Docker Repository
docker login
docker pull juhyeon1114/practice
docker run -p 80:80 -v /home/practice/project:/var/www/html juhyeon1114/practice
</pre>
