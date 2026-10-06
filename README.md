# 이승준 | 인프라 엔지니어 포트폴리오

서버와 네트워크의 동작을 이해하고, 문제의 원인을 단계별로 확인하는 인프라 엔지니어를 준비하고 있습니다.  
Linux 서버 구성, 네트워크 통신 구현, 패킷 분석과 CCNA 네트워크 설정을 학습하며 내용을 정리합니다.

## 기술 및 도구

- **서버·가상화:** Ubuntu, Linux, VirtualBox, VMware, OpenSSH, Nginx
- **네트워크·분석:** TCP/IP, UDP, ARP, Wireshark, tcpdump
- **CCNA 학습:** IPv4/IPv6, VLAN, Trunk, LACP, 정적 라우팅, OSPF, ACL
- **프로그래밍:** Python

## 주요 프로젝트 및 실습

### 1. Ubuntu 서버 구축
VirtualBox에 Ubuntu 서버를 설치하고 SSH 원격 접속과 Nginx 웹 서비스를 구성했습니다. NAT 포트 포워딩을 설정하고, HTTP 응답과 접속 로그 확인 및 서비스 중지·복구를 실습했습니다.

### 2. Python UDP 통신
Python으로 UDP 에코 서버와 클라이언트를 구현하고 왕복시간(RTT)을 측정했습니다. 타임아웃과 서버 종료 시 발생하는 수신 오류를 구분하여 예외 처리를 보완했습니다.

### 3. TCP 연결·패킷 분석
netstat과 Wireshark로 웹사이트 접속 전후의 TCP 연결 상태와 3-way handshake를 분석했습니다. IP와 포트 조합을 기준으로 연결을 추적하며 상태 변화를 확인했습니다.

### 4. ARP 스푸핑 분석
수업용 가상머신 환경에서 실제 IP·MAC 주소와 위조 ARP 응답을 비교했습니다. tcpdump와 전달 로그를 통해 중간 노드의 트래픽을 관찰했습니다.

### 5. CCNA 네트워크 구성 학습
CCNA LAB 문제를 기반으로 IPv4·IPv6 주소 설정, VLAN·Trunk, LACP EtherChannel과 정적 라우팅·OSPF 구성 방법을 학습했습니다. ACL, DHCP Snooping, DAI 등 접근 제어와 스위치 보안 설정도 함께 정리했습니다.

## 링크


