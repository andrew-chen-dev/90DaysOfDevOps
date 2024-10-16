---
title: '#90DaysOfDevOps - Introduction - Day 1'
published: true
description: 90DaysOfDevOps - Introduction
tags: 'devops, 90daysofdevops, learning'
cover_image: null
canonical_url: null
id: 1048731
date: '2022-04-17T10:12:40Z'
---
## Andrew's Notes!

DevOps is a software development mindset/pipeline based on CI/CD (Continuous Integration Continuous Deployment). It seeks to align the Development and Operations halves of the software development cycle. 

Development: Code gets planned and produced.
Operations: Code gets tested and deployed. Think VMs, networking, servers, containers -- whatever is needed to test run the code in a production environment. This is either in the cloud or on-prem (mostly AWS or Azure, some GCP).

It's symbolized by this infinity sign diagram, also known as the DevOps CI/CD pipeline: ![image](https://github.com/user-attachments/assets/03f22651-8106-4432-99a6-e2a924bb5e94)

**Development** starts with 
1. Planning
2. Coding - Git Commits
3. Building - Maven, Gradle
4. Testing - Selenium
5. Releasing (this is where it's packaged and then enters the rigorous, hopefully automated Operations segment)
**Operations** continues with
6. Deploying - Linux 
7. Operating - Ansible, Docker (most popular container tool), K8s (container orchestration platform -- operating containers at scale)
8. Monitoring and Observability - Nagios (Infrastructure monitoring and application monitoring)

Then the process cycles -- it's how DevOps software delivery can keep adding features, keep testing, keep scaling, and keep being resilient to faults. What ties this all together is the efficient CI/CD pipeline and **automation**. Automation helps you run AUTOMATIC functional tests(does the code work?), regression tests (did the code break any preexisting code?), security tests, and performance tests. Automation (as I know from writing scripts as a sysadmin) helps you get far ahead of fires before they start. 

Tools for implementing CI/CD pipeline include Jenkins, Github actions, Gitlab CICD. You will need to learn how the CI/CD tools integrate with the other tools to test and deploy code. CI/CD tools like Jenkins automatically deploy the application

IaC (Infrastructure as Code) is also a concept to be familiar with: Using code to provision and manage infrastructure. If one of the below environments goes down, you want to be able to easily replicate the infrastructure through code.

![image](https://github.com/user-attachments/assets/3cdd9251-ddc9-472e-a440-4910d75e7cf2)

DevOps is absolutely overwhelming! But that's ok: one step at a time. Before starting, I'm currently confident in networking and systems administration (and Googling :)). I at least know most of the concepts or have some passing familiarity with.

My goal for this course is to get a 
1. firm understanding of the overall DevOps cycle
2. how each tool fits into that cycle
3. what tools I lack familiarity in



## Introduction - Day 1

Day 1 of our 90 days and adventure to learn a good foundational understanding of DevOps and tools that help with a DevOps mindset.

This learning journey started for me a few years back, but my focus then was around virtualisation platforms and cloud-based technologies, I was looking mostly into Infrastructure as Code and Application configuration management with Terraform and Chef.

Fast forward to March 2021, I was given an amazing opportunity to concentrate my efforts around the Cloud Native strategy at Kasten by Veeam. Which was going to be a massive focus on Kubernetes and DevOps and the community surrounding these technologies. I started my learning journey and quickly realised there was a very wide world aside from just learning the fundamentals of Kubernetes and Containerisation and it was then when I started speaking to the community and learning more and more about the DevOps culture, tooling and processes so I started documenting some of the areas I wanted to learn in public.

[So you want to learn DevOps?](https://blog.kasten.io/devops-learning-curve)

## Let the journey begin

If you read the above blog, you will see this is a high-level contents for my learning journey and I will say at this point I am nowhere near an expert in any of these sections but what I wanted to do was share some resources both FREE and some paid for but an option for both as we all have different circumstances.

Over the next 90 days, I want to document these resources and cover those foundational areas. I would love for the community to also get involved. Share your journey and resources so we can learn in public and help each other.

You will see from the opening readme in the project repository that I have split things into sections and it is 12 weeks plus 6 days. For the first 6 days, we will explore the fundamentals of DevOps in general before diving into some of the specific areas. By no way is this list exhaustive and again, I would love for the community to assist in making this a useful resource.

Another resource I will share at this point and that I think everyone should have a good look at, maybe create your mind map for yourself and your interest and position, is the following:

[DevOps Roadmap](https://roadmap.sh/devops)

I found this a great resource when I was creating my initial list and blog post on this topic. You can also see other areas go into a lot more detail outside of the 12 topics I have listed here in this repository.

## First Steps - What is DevOps?

There are so many blog articles and YouTube videos to list here, but as we start the 90-day challenge and we focus on spending around an hour a day learning something new or about DevOps, I thought it was good to get some of the high level of "what DevOps is" down to begin.

Firstly, DevOps is not a tool. You cannot buy it, it is not a software SKU or an open source GitHub repository you can download. It is also not a programming language, it is also not some dark art magic either.

DevOps is a way to do smarter things in Software Development. - Hold up... But if you are not a software developer should you turn away right now and not dive into this project??? No. Not at all. Stay... Because DevOps brings together a combination of software development and operations. I mentioned earlier that I was more on the VM side and that would generally fall under the Operations side of the house, but within the community, there are people with all different backgrounds where DevOps is 100% going to benefit the individual, Developers, Operations and QA Engineers all can equally learn these best practices by having a better understanding of DevOps.

DevOps is a set of practices that help to reach the goal of this movement: reducing the time between the ideation phase of a product and its release in production to the end-user or whomever it could be an internal team or customer.

Another area we will dive into in this first week is around **The Agile Methodology**. DevOps and Agile are widely adopted together to achieve continuous delivery of your **Application**.

The high-level takeaway is that a DevOps mindset or culture is about shrinking the long, drawn out software release process from potentially years to being able to drop smaller releases more frequently. The other key fundamental point to understand here is the responsibility of a DevOps engineer to break down silos between the teams I previously mentioned: Developers, Operations and QA.

From a DevOps perspective, **Development, Testing and Deployment** all land with the DevOps team.

The final point I will make is to make this as effective and efficient as possible we must leverage **Automation**.

## Resources

I am always open to adding additional resources to these readme files as it is here as a learning tool.

My advice is to watch all of the below and hopefully you have also picked something up from the text and explanations above.

- [DevOps in 5 Minutes](https://www.youtube.com/watch?v=Xrgk023l4lI)
- [What is DevOps? Easy Way](https://www.youtube.com/watch?v=_Gpe1Zn-1fE&t=43s)
- [DevOps roadmap 2022 | Success Roadmap 2022](https://www.youtube.com/watch?v=7l_n97Mt0ko)
- [From Zero to DevOps Engineer - DevOps Roadmap for YOUR specific background
](https://www.youtube.com/watch?v=G_nVMUtaqCk)

If you made it this far, then you will know if this is where you want to be or not. See you on [Day 2](day02.md).
