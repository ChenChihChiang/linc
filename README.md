# How to build EKS cluster and Jenkins 

1. Create AWS cloud9 IDE 

   	 AMI : Ubuntu Server 18.04 LTS


2. Disable `AWS managed temporary credentials` 


3. Set up permisstion for AWS Cloud9

	export AWS_ACCESS_KEY_ID={your key id}
	
	export AWS_SECRET_ACCESS_KEY={your secret key}
	
	export AWS_DEFAULT_REGION=ap-northeast-1


4. Install EKS 

	`cd 01-install-eks-cluster/`
	
	`bash eks_install.sh`


5. Install Jenkins

	`cd ../02-install-jenkins/`
	
	`bash install.sh` 


6.  get jenkins url

	`bash get-links.sh`

7. log in jenkins link

    username: admin
    
    password: admin

8. uninstall

   	`cd ../uninstall/`
   
   	`bash uninstall.sh`


PS. My friend and me threw a jenkins workhop 
    you can find on youtube and google docs
    
    https://www.youtube.com/watch?v=eM26quxVuao
    
    https://docs.google.com/presentation/d/1WApH5JjlhcJ5YCVIE-It5vdTAcrUaKHOgBfuIGqP18k/edit#slide=id.g88b4f90e25_1_9

