# eks-cluster

terraform aws module 을 사용하여 간단하게 eks 클러스터를 생성해보았습니다.

로드밸런서 컨트롤러, EFS CSI driver, Prometheus, Grafana 를 한 번에 설치가능하도록 구현했습니다. 

실제 클러스터 안에서 helm 명령어를 사용하는 것과 같은 방식으로 구현했습니다.


