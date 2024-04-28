# s3-file-storage-example

we can either use “aws-java-sdk” from maven

https://www.youtube.com/watch?v=vY7c7k8xmKE
Spring Boot With Amazon S3 : File Upload & Download Example | S3 Bucket | JavaTechie
https://github.com/Java-Techie-jt/s3-file-storage-example

<!-- https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk -->
```
<dependency>
    <groupId>com.amazonaws</groupId>
    <artifactId>aws-java-sdk</artifactId>
    <version>1.11.486</version>
</dependency>
```

or we could use spring-cloud-starter-aws.

```
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-aws</artifactId>
</dependency>
```
since I’m using spring cloud I have used the “spring-cloud-starter-aws” for this sample app.


git init
git checkout -b main
git add .
git commit -m "first commit"
git remote add origin https://github.com/Pabitramaiti/dockerizing-google-jib-example.git
git push -u origin main