<h1 align="center">Welcome to Scalable MPEG-DASH streaming application 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
</p>

> a video streaming platform utilizing OAuth Google social login for user authentication, AWS S3 buckets with pre-signed URLs for secure storage, and AWS Lambda functions triggered by SNS events for server updates. Leveraged AWS CloudWatch alarms to dynamically scale an auto-scaling group of EC2 instances, configured with FFmpeg, to efficiently transcode uploaded videos into adaptive bit rates. Resulted in seamless video streaming experience for users with adaptive bit rate through MPEG-DASH, optimizing resource utilization and scaling dynamically based on workload demands.

### ✨ [Demo](demo.youtube)

## Techologies used 
  <p>
      Backend : 
    <ul>
      <li>
          Express
      </li>
       <li>
          Mongodb
      </li>
    </ul>
  </p>
  <p>
    Amazon web services used :
    <ul>
      <li>
        S3 buckets 
      </li>
      <li>
        Simple Notification service (SNS)
      </li>
      <li>
        Simple Queue Service (SQS)
      </li>
      <li>
        Lamda function
      </li>
      <li>
        Cloudwatch
      </li>
      <li>
        EC2, Custom AMI, Launch Template, Auto scaling group
      </li>
      <li>
        Cloudfront
      </li>
    </ul>
  </p>

## Feature highlight

<ul>
  <li>
    Oauth2.0 Google social login for seamless authentication
  </li>
 <li>
    Decoupled Architecture using SNS, SQS and lambda
    
  </li>
   <li>
    Resource efficient step scaling of EC2 auto scaling group with Cloudwatch metrics.
    
  </li>
   <li>
    Transcoding of videos into multiple bit rate chunks to enable MPEG-DASH based Adoptive bitrate streaming through FFMPEG.
    
  </li>
   <li>
    low latency content delivery using Cloudfront 
    
  </li>
   <li>
    Secure credentials mangement using Parameter store, permission access using IAM roles.
    
  </li>
</ul>



## Install

```sh
adf
```

## Usage

```sh
asdasd
```

## Author

👤 **ashlesh shenoy**

* Website: https://www.linkedin.com/in/ashlesh-shenoy/
* Github: [@Ashlesh shenoy](https://github.com/Ashlesh shenoy)
* LinkedIn: [@https:\/\/www.linkedin.com\/in\/ashlesh-shenoy\/](https://linkedin.com/in/https:\/\/www.linkedin.com\/in\/ashlesh-shenoy\/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://www.linkedin.com/in/ashlesh-shenoy/). 

## Show your support

Give a ⭐️ if this project helped you!

