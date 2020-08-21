	1. Register a domain in godaddy
	- russeldns.com
	
	2. Use Route 53 to configure the DNS
	- NS entries:
		ns-840.awsdns-41.net.
		ns-1977.awsdns-55.co.uk.
		ns-1142.awsdns-14.org.
		ns-40.awsdns-05.com.
	-Run DNS Checker
            - Created an apex entry
            - Created an www entry
	
	3. Use Elastic Beanstalk as the Pipeline management
            - Open the tutorial
            - Createdd the local app
            - Tested it locally
            - eb init
               - eb init -p python-3.6 russeldns --region us-west-2
            - Installed EB cli
                  - pip install awsebcli --upgrade
            - Deploy
        
        4. Use git as a version control system - OK
        - https://github.com/russelcoolxxx/russeldns.com
	
	AWS Keys:
	Access Key ID: "?" 
	Secret Access Key: "?"  
	
	
	#Domain
	
	# DNS - Domain Name System / Server
	You can think of it as a phone book.
	
	name (i.e: russeldns.com)
	
	and the phone nunmber as the IP address:
	i.e: russeldns.com
	- Domain Name Server: 35.161.54.227
	- Domain Name Server: 54.212.45.126
	
	- To figure out what is your domain NS (Name Server)
	you can navigate to whatismydns.com
