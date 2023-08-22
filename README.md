# 라즈베리파이 세팅
## 링크
### * [Raspberry Pi OS](#OS)
### * [Install Node](#node)
### * [Install VPN](#vpn)

# Raspberry Pi OS <a id="OS"></a>


### [공식 사이트](https://www.raspberrypi.com/software)에서 라즈베리파이OS 이미저를 다운받아 설치한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/21c851e8-7f11-4718-81c4-c1350f7da653)

### 운영체제 선택버튼을 눌러 원하는 버전을 선택하거나 [공식 아카이브](https://downloads.raspberrypi.org)에서 설치할 이미지를 다운받아 선택한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/8092a9d8-4b9a-4102-b2ba-751794628c74)

### 저장소(SD카드)를 선택하고 쓰기버튼을 누른다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/f5f6a522-0099-4fe8-8daa-d346ba58ac7b)

### 쓰기가 완료된 SD카드는 라즈베리파이에 장착 후 전원을 인가한다.   
### 부팅에 실패한 경우, SD카드를 점검하거나 OS설치과정을 처음부터 다시 시도한다.   
### 부팅에 성공한 경우, Next버튼을 눌러 초기 설정을 진행한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/307e8df3-69c1-4732-8786-9b9da3e9ec16)

### Country와 Language는 초기설정인 UK와 English를 사용하며, Timezone을 Seoul로 설정한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/5c2a27be-8d6c-4bbf-9e2a-7bec90f0d025)

### 기본 계정(PI)의 비밀번호를 설정한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/af7a9dbd-daf9-492b-bd9a-33739402be16)

### WIFI를 연결하거나, 유선 네트워크를 연결하여 인터넷을 연결한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/72d53e18-6286-4ad4-a4eb-eef0739c6182)

### 소프트웨어 업그레이드를 진행한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/dd041e79-9089-44e3-b2f7-5e160b6ea669)

### 소프트웨어 업그레이드를 완료한 후 재부팅을 진행한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/899d787c-23d1-4d83-a2da-fa0c7af36711)

### 아래 명령어를 입력하여 GPIO 사용을 위한 드라이버를 설치한다.   
### 만약 동작하지 않는경우 [공식 홈페이지](http://wiringpi.com)를 참고한다.

````
$ wget https://project-downloads.drogon.net/wiringpi-latest.deb
$ sudo dpkg -i wiringpi-latest.deb
$ sudo rm -rf wiringpi-latest.deb
````

### 아래 명령어를 입력하여 환경 설정을 실행한다.
````
$ sudo raspi-config
````

### 1번(System Options)을 선택하여 진입한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/feda15e1-ce44-4149-aada-0776b304c718)

### S6 Network at Boot 옵션을 선택하여 활성화 하고 설정 화면을 탈출한다.
![image](https://github.com/yukwanwoo/Raspberry_PI_Setting/assets/69711779/95229773-0d95-4efe-a04f-9caf56332710)

## 링크
### * [Raspberry Pi OS](#OS)
### * [Install Node](#node)
### * [Install VPN](#vpn)
