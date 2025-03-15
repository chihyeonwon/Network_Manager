## 25년 네트워크 복습

![image](https://github.com/chihyeonwon/Network_Manager/assets/58906858/298bf83b-5f7c-4190-9c06-af4817178a5a)
![image](https://github.com/chihyeonwon/Network_Manager/assets/58906858/35509893-7fc8-49da-99e6-2e4e94137da1)
[햄릿슈](https://www.youtube.com/channel/UCLIxBOJaBju4Ap8QoGuQYbw)
![image](https://github.com/chihyeonwon/Network_Manager/assets/58906858/4a8bf1e5-d563-416c-a813-e6d1ad4d5ebf)
## 24.08.25 서울
시간과 자원만 있으면 할 수 있고 될 수 있다.

1. 다이렉트케이블 & 크로스케이블 제작 (6.5점) 1문항    
2. 에뮬레이터 (8문항, 각 5.5점)   
3. 단답형문제 (6문항, 각 5.5점)    
4. Router문제 (3문항, 각 5.5점)   

## 20.8.25 66
```
IPv4 클래스 중 멀티캐스트 용도로 사용되는 것 : D 클래스

ARP와 RARP는 네트워크 계층에서 동작하며 인터넷 주소와 물리적 하드웨어 주소를 변환하는 데 관여한다.

SNMP : UDP를 사용, 사용자가 네트워크 문제점을 발견하기 전에 시스템 관리 프로그램이 문제점을 발견할 수 있다.

최대 홉이 15를 넘지 못하는 프로토콜 : RIP , RIP는 1번부터 16번까지 이동할 때 가능한 최대 홉수는 15이다.

IP가 제대로 도메인에 등록되어 있는지를 확인하는 명령어 : nslookup

LTE, 3GPP, WI - MAX 계열 몇 세대 통신 ? : 4세대

Linux 디렉터리 구성 중 /usr : 시스템이 구동되기 위해 필요한 명령어, 또는 매뉴얼의 집합

컴퓨터가 부팅될 수 있도록 Linux 운영체제의 핵이 되는 커널을 주 기억 장소로 상주시키는데 사용되는 부트 로더: GRUB

패스워드는 /etc/shadow에 저장되어 있다. /etc/password의 두번째필드는 패스워드 값(이 패스워드가 /etc/shadow에 있다는 것을 알림)

shudown의 명령 취소는 Ctrl + C 또는 shutdown -c

Linux에서 DNA의 SOA (가장 큰 권한을 받은 호스트를 확인) 레코드에 대한 설명이 아닌 것
: ttl 값이 길면 dns의 부하가 늘어나는 것이 아닌 minimum ttl 값이 길면 부하가 늘어남

Window Server 2016에 설치된 dns 에서 지원하는 레코드 형식 중 실제 도메인 이름과 연결되는 가상 도메인 이름의 레코드 형식은?
-> CNAME

A : 도메인 -> IP (DNS 정방향) PTR : IP -> 도메인 (DNS 역방향)

이벤트 뷰어의 Windows 로그 항목 : 응용프로그램, 보안, Setup, 시스템
-> 사용자 권한 X

Windows Server 2016 의 기본적으로 생성되는 3개의 로컬 사용자 계정 : Administrator, DefaultAccount, Guest

롤링 클러스터 업그레이드 : Hyper-V 또는 여타 서버 작업을 중지하지 않고도 업그레이드를 진행할 수 있는 기능

전송 매체에서 10Base-T가 의미하는 것 , 전송속도 : 10kbps , Base(베이스밴드), T(Twisted) 꼬임선
```


## 21.5.30 80
```
IGMP : 인터넷 그룹 관리 프로토콜로 컴퓨터가 멀티캐스트 그룹을 인근의 라우터들에게 알리는 수단을 제공하는 인터넷 프로토콜

TRACERT : Linux에서 IP 패킷이 목적지에 도착하기 위해 방문하는 게이트웨이의 순서 정보를 제공하는 명령어

ARP : IP 주소를 물리주소로 변경해주는 프로토콜이다.

ICMP의 Message Type 중 5번은 Redirect, 0번과 8번은 Echo Reply, Echo Request 이다.

WAN : WAN은 망형 토플로지로 구성된 노드들로 이루어진 커뮤니케이션 네트워크이다.

/proc : 시스템 운영 중 파일의 크기가 변하는 파일들을 위한 공간이다.

NTFS와 ReFS : ReFS는 FAT3 방식과 호환성은 좋지 않다. 하지만 앞으로 하드웨어 사양이 높아지고, 안전과 보안에 대한 중요성이 부각됨에 따라
대중적으로 활용될 것이다.

이벤트 뷰어에서 구독을 통해 시스템 이벤트 로그를 수집할 수는 있으나, 이메일을 통해 전달받지는 않고 시스템 내에서 확인할 수 있다.

이더넷 스위치가 이더넷 프레임의 목적지 주소를 메모리의 MAC 주소와 맞추어 중계 처리한다.

허브 : OSI 계층의 물리 계층에서 여러 대의 PC를 서로 연결할 때 전기적인 신호를 재생하여 신호 분배의 기능을 담당하는 네트워크 연결 장비
```

## 22.8.21 74
```
NAT를 사용할 경우 사설 IP 주소로 사용 가능한 범위 내에서 클래스 구분 없이 자유롭게 선택할 수 있다.

ICMP 메시지가 사용되는 경우 : 라우터나 호스트 간의 제어 또는 오류정보를 주고받을 경우, 호스트나 라우터가 IP 헤더의 문법 오류를 발견한 경우
라우터가 데이터를 전달할 수 없는 경우

TCP를 사용하는 프로토콜을 사용하는 것 : FTP, Telnet, SMTP
UDP를 사용하는 것 : TFTP(Trivial File Transfer Protocol)

회사 내부에 구축되어 있는 SAN (스토리지 에이리어 네트워크)의 성능이 저하되고 있어 조사업무를 진행
네트워크 대역폭 문제임을 알게 되었다. -> 광케이블

버스 토브로지의 설명 : 회선의 양 끝에 터미네이터를 두어 시그널의 반사를 방지한다.

화상회의를 하기 위한 용도인 프로토콜 SIP (Session Initiation Protocol) : 멀티미디어 서비스용 신호 프로토콜 Volp, SIP를 통해 세션을 설정한 후
실제 데이터 전달은 RTP를 활용한다.

다중화 시 전송할 데이터가 없더라도 타임 슬릇이 할당되어 대역폭의 낭비를 가져오는 다중화 방식
TDM (Time Division Multiplexer)

웹 서버 관리자에서 문서의 저장 및 열람이 가능하다면 문서의 취약점을 이용해 악의적인 목적을 가지고 있는 사람들에게 탈취 및 웹서버의 공격이 이루어진다.
iis 서비스에 설정해야될것 : HTTP 응답 헤더, SSL 설정, 인증

데이터를 안전하게 보호하는 일을 하기 위해 BitLocker를 사용하려고 한다. BitLocker를 사용하기위해 메인보드와 BIOS에서 지원해야 하는 기능
TPM (Trust Platform module)

Windows server 이벤트 뷰어에서 로그온, 파일, 관리자가 사용한 감사 이벤트 등을  포함해서 모든 감사된 이벤트를 보여주는 로그는 ? 보안로그

linux에서 현재 사용 디렉터리 위치에 상관없이 자신의 Home Directory로 이동하는 명령은? -> cd~

linux에서 ifconfig 명령어를 설치하여 네트워크 인터페이스 카드를 가동시키고자 한다. 명령어에 대한 사용이 올바른 것?

ifconfig eth0 192.168.2.4 up <- ifconfig 네트워크 인터페이스 이름 up (up은 인터페이스 동작, down은 동작을 멈추는 것)

raid 구성에서 미러링모드 구성이라고도 하며, 디스크에 있는 모든 데이터는 동시에 다른 디스크에도 백업되어 하나의 디스크가 손상되어도 다른 디스크의
데이터를 사용할 수 있게 한 RAID 구성은?

-> RAID 1( Mirroring 모드)
```

## 23.8.20 76
```
라우터의 경로 결정 시 라우팅 테이블을 참조하여 패킷을 전달하는 과정
-> Longest match rule(롱기스트 매치 룰)

OSI 7 Layer에서 참조 모델에서 사용되는 Protocol 중 tcp와 udp port를 함께 사용하는 프로토콜
-> DNS

HTTP 상태 코드에 대한 설명

100 : 정보 제공, 메소드 지시대로 요청을 성공적으로 수행
200 : 성공, 요청 계속 또는 사용 프로토콜 변경 지시
300 : 리다이렉션, 요청 수행 완료를 위해서 추가적인 작업 필요
400 : 클라이언트 오류
500 : 서버 오류

인터넷 전용회선의 대역폭을 효율적으로 제어하지 못하여 업무 마비까지 이르게 되는 현상
-> QoS를 도입하여 회사의 ip 및 프로토콜이 장비를 반드시 통과하게 만들어서 대역폭을 이벤트에 맞게 조정

FTP의 두 가지 모드

Active mode : 능동적으로 클라이언트에 접속하는 방식
Passive mode : 서버가 수동적으로 기다리고, 클라이언트가 지정된 포트로 접속하는 방식

init 6 -> 리눅스 재부팅

shudown -h now : 즉시 시스템 종료
poweroff : 시스템 종료 후 전원 off
halt : 시스템 종료

resolv.conf : nameserver 라인에 dns 서버 주소가 지정되어 있음
ping을 이용하여 외부 네트워크 상태 여부 확인 후 dns 서버 주소가 잘못되어 있을 것이라고 판단
cat/etc/resolv.conf 파일을 확인하고 수정

linux 시스템에서 사용되고 있는 메모리 양과 사용 가능한 메모리양 공유 메모리와 가상 메모리에 대한 정보를 볼 수 있는 명령어
-> free

Linux의 명령어 해석기 : Shell
Kernel : 컴퓨터 운영체제의 핵심 부분, 하드웨어와 소프트웨어 간의 통신을 담당
Utility Program : 유틸리티 프로그램은 시스템 유지 관리 및 운영을 위한 보조 프로그램
Hierarchical File System : 파일 시스템의 구조를 설명하는 개념

Linux 서버를 관리하면서 특정 조건에 맞는 파일 및 디렉터리를 검색하기 위해 find 명령어를 사용하려고 한다

find -name : 지정한 파일이름에 해당하는 파일이나 디렉터리를 찾는다.
find -type : 지정한 파일 죵류에 해당하는 디렉터리 유형을 찾는다.
find -perm : 지정한 파일의 권한만을 고려
find -exec : 찾은 파일에 대한 삭제 등의 추가적인 명령 실행

Linux 운영체제에서 하드웨어 메모리가 가득차게 되면 논리적인 메모리 저장공간 역할을 수행하게 되는 파티션 이름?
-> SWAP

RAID 0에 대한 설명 : 최소 2개의 디스크에 데이터를 동시에 분산 저장, 디스크에 데이터를 분산 저장하기 때문에 처리속도가 향상된다.
스트라이핑이라고도 부르는 방식이다.
```

## 24.05.19 80
```
네트워크 계층에서 IP는 핵심 프로토콜이다. 단편화 작업 중 분할되는 Data를 구별하기 위한 것은?
-> DF Flag

네트워크를 관리하는 Lee 사원은 잦은 IP 충돌로 인하여 장애 신고를 많이 받고 있어 IP 정책을 DHCP로 변경하고자 한다.
-> 수시로 변경되거나 이동할 수 있기 때문 (교육장용 PC)

/etc/hosts : 서버 관리자 Kim은 dns 서버가 없고 인터넷이 없는 환경에서 그룹웨어를 운영하고 있다.
그룹웨어 주소를 치고 그룹웨어를 접속하고 싶을 경우 /etc/hosts 파일을 수정하여 로컬 DNS를 설정할 수 있다.

LAN의 매체 접근 방식 중 버스구조에서 사용하고 데이터를 전송하려면 채널이 사용 중인지 아닌지를 검사한 후 채널이 사용중이지 않으면
모든 노드가 채널을 사용할 수 있으며 동시에 데이터 전송이 일어나면 충돌이 일어난다.
-> CSMA/CD

무선랜 기술 표준의 설명으로 옳지 않은 것?
-> IEEE802.11ac 기술 표준은 802.11n을 기반으로 60Hz의 밀리미터파 스펙트럼에서 동작하는 802.11 네트워크에 대한 새로운 물리계층을 정의한다

Linux에서 열려 있는 port 정보를 확인하는 명령어?
-> netstat

tracert에서 수행하는 동일한 정보를 보여주면서 홉과 다른 세부 정보 사이의 시간에 관한 정보를 출력이 끝날 때까지 저장
-> pathping

Linux에서 특정 서비스를 제공하는 Daemon이 살아있는지 확인할 때 사용하는 명령어?
-> ps

전원부를 따로 설치 또는 연결하지 않고 전원을 동시에 보낼 수 있는 것
-> POE Switch

```
