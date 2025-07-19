# ![aws](https://github.com/julien-muke/Search-Engine-Website-using-AWS/assets/110755734/01cd6124-8014-4baa-a5fe-bd227844d263) 🔒 React App CI/CD Deployment on S3 with Custom Domain & HTTPS using Route 53 + CloudFront

<div align="center">

  <br />
    <a href="https://youtu.be/o4fNDCAqyzM" target="_blank">
      <img src="https://github.com/user-attachments/assets/e6a72dcf-a68d-4c23-ab94-4371c4a8f37b" alt="Project Banner">
    </a>
  <br />

<h3 align="center">How to Add a Custom Domain and HTTPS to Your React App on AWS S3 using Route 53 and CloudFront</h3>

   <div align="center">
     Build this hands-on demo step by step with my detailed tutorial on <a href="http://www.youtube.com/@julienmuke/videos" target="_blank"><b>Julien Muke</b></a> YouTube. Feel free to subscribe 🔔!
    </div>
</div>

## 🚨 Tutorial

This repository contains the steps corresponding to an in-depth tutorial available on my YouTube
channel, <a href="http://www.youtube.com/@julienmuke/videos" target="_blank"><b>Julien Muke</b></a>.

If you prefer visual learning, this is the perfect resource for you. Follow my tutorial to learn how to build projects
like these step-by-step in a beginner-friendly manner!

<a href="https://youtu.be/o4fNDCAqyzM" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" /></a>

## <a name="introduction">🤖 Introduction</a>

This project builds upon [Part 1: CI/CD Pipeline for React App on AWS](#) by securing the deployed app with a custom domain and SSL/TLS encryption using AWS Route 53, CloudFront, and ACM.


## <a name="steps">🌐 Features</a>

• Custom domain (e.g., www.myapp.com)<br>
• HTTPS with free SSL certificate (via ACM)<br>
• CDN caching and speed boost (via CloudFront)<br>
• DNS routing with Route 53<br>

## <a name="steps">🧰 AWS Services Used</a>

• Amazon S3 (static site hosting)<br>
• AWS CodePipeline (CI/CD)<br>
• AWS Certificate Manager (SSL/TLS)<br>
• Amazon CloudFront (CDN + HTTPS)<br>  
• Amazon Route 53 (DNS)<br>

## <a name="pre">✅ Prerequisites</a>

Before you begin, ensure you have the following set up:
 
• Working S3 React app from Part 1<br>
• Domain registered (Route 53 preferred)<br>
• AWS CLI configured<br>

## <a name="steps">🚀 Setup Steps</a>

1. **Request an SSL Certificate** in ACM (us-east-1)<br>
2. **Create a CloudFront Distribution** pointing to your S3 endpoint<br>
3. **Configure Route 53** to route your domain to CloudFront<br>
4.  🎉 Done! Your React app is now live with HTTPS and a custom domain!<br>  

## 📺 Video Tutorial
Check out the full video tutorial here 👉 [YouTube Link]

## 📬 Feedback
Found it helpful? Star ⭐ the repo and share with your friends!
Issues or bugs? Open an issue or reach out on LinkedIn.


## 🗑️ Cleaning Up

When you are finished with the project, you can delete all the created AWS resources to avoid incurring further costs.
