### REQUIREMENT PACKAGES:
<code>sudo apt update</code>
<br/>
<code>sudo apt install apt-transport-https ca-certificates curl software-properties-common</code>
<br/>

![satu](img/docker/1.jpg)

### GPG REPO:
<code>curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg</code>

![dua](img/docker/2.jpg)

### APT REPO SOURCES:
<code>echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null</code>

![tiga](img/docker/3.jpg)

### UPDATE INTERNAL REPO SYSTEM
<code>sudo apt update</code>

![empat](img/docker/4.jpg)

### verify repo from docker:
<code>apt-cache policy docker-ce</code>

![lima](img/docker/5.jpg)

### INSTALL:
<code>sudo apt install docker-ce</code>

![enam](img/docker/6.jpg)

### CHECK STATUS:
<code>sudo systemctl status docker</code>

![tujuh](img/docker/7.jpg)

### ROOTLESS:
<code>sudo usermod -aG docker ${USER}</code>

### Check Rootless:
<code>groups</code>

### check docker access:
<code>docker info</code>

![delapan](img/docker/8.jpg)