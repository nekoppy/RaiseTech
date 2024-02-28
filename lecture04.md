# 第4回課題

* VPC

![VPC](vpc.png)

* EC2

![EC2](ec20128.png)

* RDS
  
![rds](rds0128.png)

* セキュリティグループの内容
  
![sg](sg0128.png)

* RDSのセキュリティグループ

![rds_sg](rds_sg0129.png)

* RDSのサブネットグループに含まれているサブネット
  
![subnet](subnet0128.png)

* RDSのサブネットグループに含まれるサブネットがパブリックかプライベートか判別できるエビデンス

***パブリックサブネットと、プライベートサブネットはルートテーブルによる接続先がインターネットゲーウェイである事、それ以外である事で分類***

![subnet_detail](subnet0130-3.png)

![subnet_detail](subnet0130-4.png)

* EC2へSSH接続

`ssh -i [キー] ec2-user@[パブリック IPv4 DNS]`
  
![ec2_ssh](ssh0128.png)

* EC2からRDSへ接続

　`sudo dnf update -y`

 `sudo dnf install mariadb`

　`mysql -h [エンドポイント] -P 3306 -u admin -p`
  
![ec2_rds](sql0128.png)
