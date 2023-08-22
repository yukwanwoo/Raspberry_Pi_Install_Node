# 라즈베리파이 노드 설치
## 링크
### * [Raspberry Pi OS](https://github.com/yukwanwoo/Raspberry_PI_Setting)
### * [Install Node](#node)
### * [Install VPN](https://github.com/yukwanwoo/Raspberry_Pi_Install_VPN)

# Install Node <a id="node"></a>


#### [공식 사이트](https://nodejs.org/dist)에서 사용할 노드 버전별 링크를 확인한다.
#### 64비트는 arm64.tar.xz로 끝나는 파일을 사용하고, 32비트는 arm7l.tar.xz를 사용한다.
![image](https://github.com/yukwanwoo/Raspberry_Pi_Install_Node/assets/69711779/1b47b6a7-00db-491a-b3f4-53b6b17ac9c8)


#### 라즈베리파이의 터미널에서 아래와 같이 입력하여 파일을 다운받고 설치한다.
#### 아래 예시는 16.15.1버전의 32비트 노드를 설치하는 예시이다.
````
$ wget https://nodejs.org/dist/v16.15.1/node-v16.15.1-linux-armv7l.tar.xz
$ tar xvf node-v16.15.1-linux-armv7l.tar.xz
$ cd node-v16.15.1-linux-armv7l
$ sudo cp -R * /usr
$ cd ..
$ sudo rm -rf node-v16.15.1-linux-armv7l
$ sudo rm -rf node-v16.15.1-linux-armv7l.tar.xz
````

## 링크
### * [Raspberry Pi OS](https://github.com/yukwanwoo/Raspberry_PI_Setting)
### * [Install Node](#node)
### * [Install VPN](https://github.com/yukwanwoo/Raspberry_Pi_Install_VPN)
