# How to use

1. Create AWS cloud9 IDE `Ubuntu Serber 18.04 LTS`


2. Disable `AWS managed temporary credentials` 


3. Set up permisstion for AWS Cloud9

	export AWS_ACCESS_KEY_ID={your key id}
	
	export AWS_SECRET_ACCESS_KEY={your secret key}
	
	export AWS_DEFAULT_REGION=ap-northeast-1


4. Install EKS 

	cd 01-install-eks-cluster/
	bash eks_install.sh


5. Install Jenkins

	cd ../02-install-jenkins/
	bash install.sh 


6.  get jenkins url

	bash get-links.sh

7. log in jenkins link

    username: admin
    password: admin

