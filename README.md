# 2018/04/07/토
- VPC는 개인별로 분리되어 있는 영역
- VPC안에 복수개의 서브넷이 존재
- block처리를 해야할 경우는 VPC에서 하는게 좋다
- 22번 포트 Bastion는 경유서버?
- VPC peering
  - 예를들어 어카운트가 분리되어있거나 복수개의 vpc를 경유서버를 통해서 통과하도록 할때 사용
- 네트워크 LB는 IP가 LB의 IP로 바뀌지 않고 그대로 들어옴
- 오토스케일링은 CPU나 네트워크의 부하등에 의해 실행되도록 설정가능
- [HCI](http://www.fujitsu.com/jp/products/computing/virtual/tech/term/hci)
- S3는 버전관리가 가능. (버전별의 용량은 늘어나기 때문에 주의)
- 속도: EBS > EFS > S3
- RDS는 병목현상이 없다
 - 마스터, 스탠바이, 리드레플리카의 3중 구성
- 클라우드프론트는 컨텐츠 전송할때 압축(gzip)해서 전송가능
