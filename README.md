# docker-personal PHP 예시

### Installation

<pre>
cd /home/ubuntu
git clone https://github.com/some-peroxide/docker-personal
cd docker-personal
</pre>

###Run
<pre>
#Login For Private Docker Repository
docker login
docker pull some-peroxide/docker-personal
docker run -p 80:80 -v /home/ubuntu/docker-personal/Project:/var/www/html some-peroxide/docker-personal
</pre>
