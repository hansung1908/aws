# aws
아마존에서 여분의 서버를 대여해주는 클라우드 서비스

클라우드 서비스를 활용하기 위해 기본지식을 학습 (axw, linux, network)
내 프로젝트를 단순 배포하기 위해 환경을 구축 (ec2) (iaas: 인프라 - 물리적 컴퓨터) 배포를 간편하게 (shell script)

환경 구축 없이 내 프로젝트를 배포 (엘라스틱 빈 스톡) (paas: 플랫폼 - 물리적 컴퓨터(플랫폼))
배포 자동화를 구축 (github action) 무중단 배포 (로드 밸런서, 롤링 배포)

정적 ip 할당을 위해 network load balancer를 활용

전산실 구축시 유의점 : 토지, 건물, 하드웨어 장비(서버(중지 x), 침입 방지 or 차단 시스템(ips, ids, 방화벽), 로드 밸런서(L4 장비), 각종 네트워크 장비),
에어컨(반도체 온도 조절), 전기,복잡한 케이블 정리, 소방 시설, 전산실 보안
