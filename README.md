# Global-Static-Website-Hosting-using-S3-CloudFront-CDN

A production-ready static website hosting solution using **AWS S3** and **CloudFront** with **CDN** optimization and secure global delivery.

- **Project Objective :**

To design and implement a **scalable, secure, and high-performance** static website hosting solution using Amazon S3 and CloudFront CDN, ensuring **global content delivery** with optimized **latency** and **caching**.

- **Project Overwiew :**

This project demonstrates how to host a static website using Amazon S3 and **enhance** its performance and **security** using **Amazon CloudFront**. 

The website files are **stored** in an **S3 bucket** and **served globally** through **CloudFront edge locations**. 

The setup includes **static website hosting**, **secure access configuration**, **HTTPS enforcement**, and **cache optimization** using CDN mechanisms.

- **Services Used :**
  
  --Amazon S3
  
  --Amazon CloudFront
  
  --AWS IAM

- **Key Features :**

  --Static website hosting using S3
  
  --Global content delivery using CloudFront CDN
  
  --HTTPS secure access with automatic redirection
  
  --Improved performance through caching
  
  --Controlled access using Origin Access Control (OAC)
  
  --Cache invalidation for real-time content updates
  
  --Highly scalable and cost-effective architecture

- **Real-World Applications :**

  --Company landing pages
  
  --Portfolio websites
  
  --Documentation hosting
  
  --Marketing campaign pages
  
  --Static frontend for web applications
  
  --Content delivery for global users

- **Archiecture Diagram :**

![Project Screenshot](Archiecture-Diagram.png)

- **Project Flow :**

1. User requests website using CloudFront URL
2. CloudFront checks if content is cached
3. If cached → serves directly (fast response)
4. If not cached → fetches from S3 bucket
5. Content is delivered to user and cached at edge location
6. Future requests are served faster from cache



![Project Screenshot](screenshots/)
