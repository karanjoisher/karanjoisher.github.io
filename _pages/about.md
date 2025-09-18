---
layout: about
title: about
permalink: /
description: Software Developer, B.Tech in Computer Engineering

profile:
  align: right
  image: prof_pic.jpg

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---
I am currently a Senior Software Engineer at Hewlett Packard Enterprise, developing high-performance RDMA library for distributed object storage systems.

My main interests include:
- Software development (Backend systems, microservices, distributed systems, etc.)
- Systems programming (Operating systems, networks, etc.)
- Tools development (Debuggers, graphics, etc.)

My goal is to develop performant, easy-to-use tools that leverage the immense potential offered by modern hardware, making overall computing experience much smoother and bloat free for users and developers.

Other than programming, my hobbies include:
- Sim Racing (mainly on iRacing)
- Go-karting
- Skiing

<br>

# Education

-----

<img align="left" width="100" src="../assets/img/neu.png" style="padding-right:15px">
#### **Northeastern University**
<strong>M.S. in Computer Science</strong><br>
<i>Boston, MA</i>&nbsp;&nbsp;|&nbsp;&nbsp;<i>Sep 2022 - Apr 2024 </i> 

-----
<strong>GPA:</strong> 4/4 <br> 
<strong>Coursework:</strong> Operating Systems <b><i>([Received Rockstar Programmer Award](https://karanjoisher.github.io/assets/pdf/Rockstar_Programmer_Award.pdf){:target="\_blank"})</i></b>, Program Design Paradigms, Database Management Systems<br>

-----

<img align="left" width="105" src="../assets/img/somaiya.jpg" style="padding-right:15px">
#### **K.J. Somaiya College of Engineering**
<strong>B.Tech in Computer Engineering</strong><br>
<i>Mumbai, India</i>&nbsp;&nbsp;|&nbsp;&nbsp;<i>Aug 2015 - May 2019</i>

-----
<strong>CGPA:</strong> 8.56/10 <br> 
<strong>Coursework:</strong> Computer Architecture, Operating Systems, Systems Programming and Compiler Construction, Fundamentals of Programming, Data Structures, Algorithms<br>

<br>
# Experience
-----
<img align="left" width="100" src="../assets/img/hpe.png" style="padding-right:15px">

#### **Hewlett Packard Enterprise**
<strong>Software Engineer 2</strong><br>
<i>Andover, Massachusetts</i>&nbsp;&nbsp;|&nbsp;&nbsp;<i>Jun 2024 - Present</i>

----- 
- Built NVGrid, a high-performance C++ RDMA library powering distributed object storage clusters, enabling east-west data transfer rates up to 400 Gb/s.
- Developed observability tooling to capture FlameGraphs, switch packet drops, and network statistics; to help diagnose performance bottlenecks.
- Tuned switch QoS policies, reduced lock contention and thread starvation, and balanced internode vs. disk I/O bandwidth, increasing cluster throughput from 128 Gb/s to 400 Gb/s.
- Replaced VMware ESXi with HPE VM Essentials and SR-IOV, enabling deployment of RDMA-capable Kubernetes clusters for development and testing, saving $3,500 per host annually in licensing costs.
- Developed a Producer–Consumer RDMA protocol to replace a Client–Server model, reducing internode operations per transaction from 4 to 3 and lowering latency by 5%.
- Developed an error injection API over gRPC that injects faults directly into the RDMA device context (CQ, async event queue), allowing validation of error-handling paths rarely triggered under organic workloads.
- Developed NAE scripts for Aruba CX 9300 switches to handle interface split and speed requirements, eliminating manual configuration and enabling factory units to support all HPE storage products.
- Tech used: C/C++, IBVerbs, Boost, gRPC, Redis, Kubernetes, Docker, Grafana, Bazel, GoogleTest, Jenkins

-----

<img align="left" width="100" src="../assets/img/hpe.png" style="padding-right:15px">

#### **Hewlett Packard Enterprise**
<strong>Software Engineer Intern</strong><br>
<i>Andover, Massachusetts</i>&nbsp;&nbsp;|&nbsp;&nbsp;<i>May 2023 - Dec 2023</i>

----- 
- Developed TCP channel for non-RDMA NICs, and Shared Memory channel for services on the same node
- Engineered Connection Manager library for establishing channel connections between nodes; used gRPC service framework and Redis for service look-up; and Boost state machine for connection orchestration
- Architected Telemetry library to monitor the health and performance metrics of NVGrid components and integrated it with Grafana for visualization
- Tech used: C/C++, IBVerbs, Boost, gRPC, Redis, Kubernetes, Docker, Grafana, Bazel, GoogleTest, Jenkins

-----

<img align="left" width="100" src="../assets/img/neu.png" style="padding-right:15px">

#### **Northeastern University**
<strong>Research Assistant</strong><br>
<i>Boston, Massachusetts</i>&nbsp;&nbsp;|&nbsp;&nbsp;<i>Jan 2023 - May 2023</i>

----- 
- Provided SME support for Discovery Cluster on topics ranging from Linux, Slurm, Docker, MPI, Cuda, and Distributed ML Training
- Orchestrated concourse pipelines to build and deploy containers of docker and Singularity
- Collaborated with researchers to construct and launch large ML models on multi-GPU clusters, leveraging PyTorch and TensorFlow

-----

<img align="left" width="100" src="../assets/img/barclays.png" style="padding-right:15px">

#### **Barclays**
<strong>Software Developer</strong><br>
<i>Pune, India</i>&nbsp;&nbsp;|&nbsp;&nbsp;<i>Jul 2019 - Jul 2022</i>

----- 
● <strong>Barclays Mobile Banking APIs</strong><br>
○ Designed and developed an ecosystem of APIs for setting up repayment plans for delinquent accounts.<br>
○ Gained 5x improvement in API response times by making downstream API calls asynchronous and parallel.<br>
○ Implemented a performance logging and monitoring library to track performance of these APIs.<br>
● <strong>Customer Outcome Testing Application</strong><br>
○ Gathered requirements from bank agents to understand how they manually reviewed collection cases.<br>
○ Developed a backend API and database components to digitize the manual case review process.<br>
○ Closely worked with bank agents to build UI and iterate over the application flow.<br>
○ <strong><i>Key Achievements</i></strong>: Reduced manual effort for case reviews by 232 hours/week (5.8 FTEs).<br>
● <strong>AWS Microservices and Cloud Infrastructure Automation</strong><br>
○ Developed microservices to create collection cases for delinquent accounts received via Apache Kafka events.<br>
○ Created CloudFormation templates to deploy auto-scaling ECS clusters, MSK clusters, RDS, and EC2 machines on the AWS cloud platform.<br>
○ Implemented AWS Lambdas for rotating credentials and replicating EBS volumes to backup data.<br>
○ Developed features for APIs to automatically fetch the latest credentials from AWS Secret Manager.<br>
○ <strong><i>Key Achievements</i></strong>: Single-click infra provisioning; Reduced server costs by demand-based cluster scaling.<br>

-----

<img align="left" width="100" src="../assets/img/accelo.jpg" style="padding-right:15px">

#### **Accelo Innovations**
<strong>Computer Vision Developer</strong><br>
<i>Mumbai, India</i>&nbsp;&nbsp;|&nbsp;&nbsp;<i>Aug 2017 - Oct 2017</i>

-----
- Developed <strong>depth mapping module (using stereo-vision)</strong> in <strong>Python</strong> and <strong>C</strong> using a two camera setup.
- Integrated <strong>Tensorflow's object detection</strong> with the depth mapping module to identify objects and calculate their distance from the vehicle.

-----

<img align="left" width="100" src="../assets/img/truckerrs.png" style="padding-right:15px">

#### **Truckerrs**
<strong>Frontend Developer</strong><br>
<i>Mumbai, India</i>&nbsp;&nbsp;|&nbsp;&nbsp;<i>May 2016 - Jun 2016</i>

-----
- Designed the <strong>UI/UX</strong> for the website.
- Implemented the <strong>front-end</strong> of the booking system and integrated it with the <strong>back-end API</strong>.
- Used <strong>Google Maps API</strong> for features such as tracing the path of the vehicle on map.

-----

<img align="left" width="100" src="../assets/img/tapthetech.png" style="padding-right:15px">

#### **TapTheTech**
<strong>Flash Animator</strong><br>
<i>Mumbai, India</i>&nbsp;&nbsp;|&nbsp;&nbsp;<i>Mar 2013 - Jan 2014</i>

-----
- TapTheTech was a group of students who believed <strong>MOOCs are the future of education</strong>. It went on to become one of the <strong>official learning hubs on Coursera</strong>
- I was one of the <strong>core team members</strong> and <strong>created content, animations</strong> for the educational videos on the <strong>[YouTube channel](https://www.youtube.com/user/TAPtheTECH){:target="\_blank"}</strong>; helped <strong>organize events</strong> in schools to spread awareness about MOOCs
