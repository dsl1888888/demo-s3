#demo s3 
#java

Below AWS services are used to achieve the functionality.
1. AWS EC2
2. AWS S3
3. AWS IAM
4. AWS CodeCommit
5. AWS SDK for Java


2021/4/5 星期一

Fix 

a.

<parent>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-parent</artifactId>
	<version>2.4.4</version>
	<relativePath/> <!-- lookup parent from repository -->
</parent>

b.
<dependency>
    <groupId>com.amazonaws</groupId>
    <artifactId>aws-java-sdk-s3</artifactId>
    <version>1.11.991</version>
</dependency>




参考地址

https://github.com/ashenjy/AWS-S3-image-upload-spring-boot-app
