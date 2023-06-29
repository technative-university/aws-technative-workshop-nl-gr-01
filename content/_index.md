---
title: AWS Workshop (NL/GR)

---

![](/images/136828712.png)

# **AWS Workshop**{.technative-title}
### Practical overview of some **useful AWS** cases

---

<!-- : .wrap  -->

##### intro {.technative-title}

|||

## **About me**

<img src="/images/658612.jpg" width="200" />

|||

- • Pim Snel <[pim@technative.eu](mailto:pim@technative.eu)>
- • Cloud Engineer at TechNative NL
- • Previous life... ran a software development company
- • Loving the good life...
- &nbsp; (family, wine, beer, foodie, music festivals... play around!)

&nbsp;

&nbsp; &nbsp;&nbsp; &nbsp;obsessed with Open Source software..
{.technative-title}

---

<!-- : .wrap .size-70 .aligncenter -->

### **Creativity** meets the **Cloud**

### Reasons to learn AWS..{.technative-title}

---

<!-- : .wrap  -->

##### intro {.technative-title}

|||

## **Why learn AWS**


|||

- • It's a toystore filled with building blocks
- • Idea's turn into reality much faster
- • There are no borders between development and infrastructure

---

<!-- : .wrap .size-70 .aligncenter -->

##### Let's get started

### The Warming up..{.technative-title}

---

<!-- : .wrap  -->

##### Browsing through the AWS Admin Console {.technative-title}

|||

## **Takeways**

- • Get familiarized with AWS Console
- • Learn to find the most important services
- • something with regions

|||

- • Navigating in the menu
- • Searching for a service
- • Typical services: S3, EC2, IAM, Route 53
- • Bookmarking
- • Dark Mode

---

<!-- : .wrap .size-70 .aligncenter -->

you spent hours building a huge demo..<br>
and this happens...


## **WTF**

# 😱

#### everything is gone!!!

---

<!-- : .wrap .size-70 .aligncenter -->

##### Have you selected the correct region? {.technative-title}

---

<!-- : .wrap  -->

##### AWS Billing and the Cost Explorer {.technative-title}

|||

## **Takeways**

- • Always be aware of your cloud spend
- • Learn how to identify costly services

|||

- • Billing overview
- • Using the Cost Explorer
- • Turn off unused services that cost money

<!-- : .wrap .size-70 .aligncenter -->

---

<!-- : .wrap .size-70 .aligncenter -->

## Now lets _really_ start

### **Installing a LAMP machine** {.technative-title}


---

<!-- : .wrap  -->

##### Installing an EC2 Bitnami Lamp machine {.technative-title}

|||

## **Takeways**

- • Learn how to install prebuild AMI's
- • Learn about security groups
- • Learn EC2 basics
- • Some basic and advanged SSH stuff

|||

#### **Steps we need to take.**

- • Setup
- • First Connect
- • Open the web interface
- • Getting stuff inside your VM
- • Access phpMyAdmin via a SSH tunnel

<!-- : .wrap .size-70 .aligncenter -->

---

<!-- : .wrap .size-70 .aligncenter -->

## Our Managed Services DNA

### Creating Infrastructure as Code with **Terraform** {.technative-title}

---

<!-- : .wrap  -->

##### A minimal Terraform Example {.technative-title}

|||

## **Takeways**

- • Learn how to get CLI access to AWS
- • Understand the concept of Terraform
- • Learn how to deploy resources in AWS

|||

#### **Steps we need to take.**

- • Prepare AWS CLI
- • Install Terraform
- • Create a litte terraform project
- • Deploy and test

<!-- : .wrap .size-70 .aligncenter -->

---

<!-- : .wrap .size-70 .aligncenter -->

## Terraform is modular

### Implementing external terraform modules in **Terraform** {.technative-title}

---

<!-- : .wrap  -->

##### A modular Terraform Exercise {.technative-title}

|||

## **Takeways**

- • Learn how to navigate in the Terraform Registry
- • Learn how to implement Terraform Modules
- • Learn about Lambda, API Gateway and SES

|||

#### **Steps we need to take.**

- • Read the [exercise instructions](https://github.com/technative-university/03-terraform-module-form-endpoint)
- • Read find the *html-form-action* module
- • Read module the module instructions
- • Deploy and test

<!-- : .wrap .size-70 .aligncenter -->

---

---








## **company** is unhappy with Vercel

# 😒

|||

## Bad support

<!-- : .wrap .size-70 .bg-white .shadow -->

The NextJS Hosting Plan support is poor, considering the price we pay.

|||

## Too expensive

Current growth will drive the costs unreasonable high.

---

<!-- : .wrap .size-70 .aligncenter -->

##### company asked TechNative to compare other hosting options.

### These are the results..{.technative-title}

---

<!-- : .wrap .size-70 .aligncenter -->

## first some starting points

---

<!-- : .wrap  -->

##### starting points {.technative-title}

|||

## **Wannahaves**

|||

- • (FrontEnd) Developer Happiness

- • Maintainable & KISS

- • Affordable and Cost Transparency

- • Well Supported

- • Future proof

&nbsp;

&nbsp; &nbsp;&nbsp; &nbsp;and Cloud Native is the Holy Grail..
{.technative-title}

---

<!-- : .wrap  -->
##### starting points {.technative-title}

|||

## **Hard Specs**

|||

- • NextJS 13
- • Server Site Rendering or Generation
- • Incremental Static Regeneration (ISR)
- • Using middleware
- • Pipelines that can work with the WireGuard VPN


---

<!-- : .wrap .size-70 .aligncenter -->

## Inventory of options

---

##### Inventory of options {.technative-title}

|||

### Serverless NextJS

|||

- • Using the serverless framework.
- • Officially supports untill NextJS 11
- • NextJS 12 together with ISR and SSR in feature branches.
- • Some success with company frontend running Next 12
- • NextJS 13 upgrade broke our implementation, (we made a git mess)

&nbsp;

The project seems to have stopped being active.
{.text-intro}

---

##### Inventory of options {.technative-title}

|||

### Terraform AWS NextJS

|||

- • Most promising, best papers, most elegant
- • Terraform module deploying to AWS
- • Creates CloudFront, S3, Lambda and Lamda@edge components
- • The Next 13 upgrade was a big issue
- • Lead developer was hired by Vercel
- • Project is orphaned.

&nbsp;

We'll keep watching this.
{.text-intro}

---

<!-- : .wrap .size-70 .aligncenter -->

##### Inventory of options {.technative-title}

### Other projects

&nbsp;

- **slagd nexjs**, just one developer
- **cdk-nextjs**, not mature


---

<!-- : .wrap .size-70 .aligncenter -->
## Remaining competitors

---

##### Remaining competitors {.technative-title}

|||

## **AWS Amplify**
### November Release

|||

- • Custom docker image for VPN connectivity
- • https://test.api.tracklib.com was not possible to setup
- • Hidden resources: has pro's and con's
- • Missing logs (misconfiguration?)
- • Performance mode @edge lambda functions
- • Supports Password Protection
- • Native support for Cypress tests
- • Pay as you go pricing

---

##### Remaining competitors {.technative-title}

|||

## **AWS Amplify**
### November Release

|||


#### Pricing

| Resource usage         | costs                        |
|------------------------|------------------------------|
| Build and Deploy       | $0.01 per minute             |
| Data Storage           | $0.023 per GB per month      |
| Data transfer out      | $0.15 per GB served          |
| Request Count (SSR)    | $0.30 per 1 million requests |
| Request Duration (SSR) | $0.20 per hour (GB-hour)     |

source:  https://aws.amazon.com/amplify/pricing/

---

##### Remaining competitors {.technative-title}

|||

## **AWS Amplify**
### November Release

|||

A test implementation is running on:
https://main.dgdttowx37yvx.amplifyapp.com

~~~
login:   tracklib
password: ww99ww99
~~~

---

##### Remaining competitors {.technative-title}

|||

### **Containerized NodeJS**

|||

- • Working setup exists ECS cluster.
- • Old fashioned but always fully compliant
- • Migrating Fargate will decrease maintaince
- • Cost competitive using fine grained autoscaling

---

<!-- : .wrap .size-70 .aligncenter -->
# Comparison

---

##### Comparison {.technative-title}

|||

## Scalability


| Solution             | Scalability            |
|----------------------|------------------------|
| NextJS on containers | architecture dependant |
| Vercel               | limited by plan        |
| Amplify              | unlimited              |

---

##### Comparison {.technative-title}

## Well supported



| Solution          | Current Features | Future feature | Customer Suppport     |
|-------------------|------------------------|----------------------|--------------------|
| NextJS containers | very good              | very good            | supplier dependant |
| Vercel            | very good              | very good            | poor               |
| Amplify           | good                   | good ambitions       | excellent          |

---

##### Comparison {.technative-title}

## Easy to understand
### for **DevOps** and **Developer**

| Solution          | Maintainability by DevOps | Usage by FrontEnd Developer |
|-------------------|---------------------------|-----------------------------|
| NextJS containers | normal                    | dependant on architecture   |
| Vercel            | easy                      | easy                        |
| Amplify           | normal                    | normal                      |

---

##### Comparison {.technative-title}

### Compliance with company technical requirements

| Solution          | Full stack compatibility  | FrontEnd compatibility |
|-------------------|---------------------------|------------------------|
| NextJS containers | complete                  | complete               |
| Vercel            | Missing VPN compatibility | complete               |
| Amplify           | Missing VPN compatibility | normal                 |


---

<!-- : .wrap .size-70 .aligncenter -->

# Conclusion

---

<!-- : .wrap .size-70 .aligncenter -->


# Conclusion

- Some troubles with changing versions.
- NextJS and NodeJS hosting innovation is moving fast.
- Challenging to formulate a long during strategy.
- There are good alternatives to move away from Vercel.

---

<!-- : .wrap .size-70 .aligncenter -->

# Conclusion

- Currently is no good serverless open source competitor.
- Serverless is successor of Containerized NextJS.

---

<!-- : .wrap .size-70 .aligncenter -->

# Conclusion

- The new Amplify service is promising
- Amplify deserves a deeper look

---

<!-- : .wrap .size-70 .aligncenter -->

# Conclusion

- A containerized solution in AWS is a good alternative.
- A containerized solution most technically transparent.
- A containerized solution most flexible choice available.


---

# **Lets** {.technative-title}
# **work** {.technative-title}
# **together** {.technative-title}

&nbsp;

## **Need a hand? Or a high five?**
## **Let us know – [hello@technative.nl](mailto:hello@technative.nl).**

## **We are ready when you are!**


