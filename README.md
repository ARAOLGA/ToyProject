# 프로젝트 개요
이 프로젝트는 K8S 환경에서 web서비스를 목표로 합니다.
개발자가 커밋을 발생시키면 ci/cd 파이프 라인이 동작하여 docker image까지 만드는 과정을 수행합니다.

# 프로젝트 목표
- 로그 및 메트릭 데이터의 실시간 수집 및 분석을 위한 시각화 대시보드 구축
- 시스템의 안정성과 확장성 확보

# 기술 스택
- k8s, metallb
- git
- jenkins, argocd
- prometheus, grafana
- java spring, mysql

# 환경 구축
- Manager: jenkins, argocd, prometheus, grafana등이 설치되고 k8s에 명령을 내림
- Worker1, 2: manager의 명령에 의해 web과 db가 구성되어 있는 docker image를 받아와 웹 페이지를 띄움

# 플랫폼 구성 환경
![image](https://github.com/ARAOLGA/ToyProject/assets/156294667/4a2cfe3b-65a9-4e3c-ad30-fdaeac7980db)

## 담당 업무
- 일정 수립 및 역할 분담
- 어려움을 겪는 팀원 지원 (jenkins 부분을 맡은 팀원을 도와 jenkins를 pod로 올리기 위해 Docker in Docker 구성)
- 보고서 작성
