# spring-cloud-config-files-storage
<!-- PROJECT SHIELDS -->

<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/yewin-mm/spring-cloud-config-files-storage.svg?style=for-the-badge
[contributors-url]: https://github.com/yewin-mm/spring-cloud-config-files-storage/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/yewin-mm/spring-cloud-config-files-storage.svg?style=for-the-badge
[forks-url]: https://github.com/yewin-mm/spring-cloud-config-files-storage/network/members
[stars-shield]: https://img.shields.io/github/stars/yewin-mm/spring-cloud-config-files-storage.svg?style=for-the-badge
[stars-url]: https://github.com/yewin-mm/spring-cloud-config-files-storage/stargazers
[issues-shield]: https://img.shields.io/github/issues/yewin-mm/spring-cloud-config-files-storage.svg?style=for-the-badge
[issues-url]: https://github.com/yewin-mm/spring-cloud-config-files-storage/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/ye-win-1a33a292/

<h1 align="center">
  Overview
  <img src="https://github.com/yewin-mm/spring-cloud-config-files-storage/blob/master/github/template/images/overview/cloud_config.png" /><br/>
</h1>


# spring-cloud-config-files-storage
* This is the microservice config file storage for centralization configuration.
* Nowadays, We used spring cloud config for centralization for all configures at one place over `Git` call config repository (properties or yml files store). 
* Also, we don't need to restart our application again if we changed something in our `application.properties` files or if we want to change something in that config file.
* So, Spring Cloud Config is used for centralized configuration and used to change config at runtime collaborate with Spring boot Actuator build in `Refresh` api. 
* This project is communicate with [Cloud Config Server](https://github.com/yewin-mm/spring-cloud-config-server) for fetching (pulling) config value through that server <br> 
and communicate with [Spring Cloud Config Sample Microservice A](https://github.com/yewin-mm/spring-cloud-config-sample-microservice-a) as for config sample client service <br>
and communicate with [Spring Cloud Config Sample Microservice B](https://github.com/yewin-mm/spring-cloud-config-sample-microservice-b) as for another config sample client service.

<!-- TABLE OF CONTENTS -->
## Table of Contents
- [About The Project](#about-the-project)
    - [Built With](#built-with)
- [Getting Started](#getting-started)
    - [Before you begin](#before-you-begin)
    - [Clone Project](#clone-project)
- [Contact Me](#contact)
- [Becoming a Sponsor](#becoming-a-sponsor)
- [Contributing](#Contributing)


<a name="about-the-project"></a>
## ⚡️About The Project
This is Demo repository for Spring Cloud Config file storage. <br>
This config file storage is for all appliactions as centralization and [cloud config server](https://github.com/yewin-mm/spring-cloud-config-server) will fetch desire application properties from this repository through `Git`.<br>
So, firstly, you need to put `application.properties` or `yml` for this application to `Github` or `Bitbucket` or you can even use your local config folder which already committed to local git repository. <br>
Here, config file means your application require file like `application.properties` or `application.yml` file.

<a name="built-with"></a>
### 🪓 Built With
This project is just application properties or application yml file storage.

<a name="getting-started"></a>
## 🔥 Getting Started
There is no need to set up anything.

<a name="before-you-begin"></a>
### 🔔 Before you begin
If you are new in Git, GitHub and new in Spring Boot configuration structure, <br>
You should see basic detail instructions first in here [Spring Boot Application Instruction](https://github.com/yewin-mm/spring-boot-app-instruction)<br>
If you are not good enough in basic API knowledge with Java Spring Boot and other spring basic knowledge, you should learn below example projects first. <br>
Click below links.
* [Spring Boot Sample CRUD Application](https://github.com/yewin-mm/spring-boot-sample-crud) (for sample CRUD application)
* [Reading Values from Properties files](https://github.com/yewin-mm/reading-properties-file-values) (for reading values from properties files)
* [Spring Profile](https://github.com/yewin-mm/spring-profile-properties-yml-file) (for knowing spring profiles)
* [Cloud Config Server](https://github.com/yewin-mm/spring-cloud-config-server) (for config server)
* [Spring Cloud Config Sample Microservice A](https://github.com/yewin-mm/spring-cloud-config-sample-microservice-a) (for sample config client)
* [Spring Cloud Config Sample Microservice B](https://github.com/yewin-mm/spring-cloud-config-sample-microservice-a) (for another sample config client)


<a name="clone-project"></a>
### 🥡 Clone Project
* Clone the repo
   ```sh
   git clone https://github.com/yewin-mm/spring-cloud-config-files-storage.git
   ```

<a name="contact"></a>
## ✉️ Contact Me
Name - Ye Win <br> LinkedIn profile -  [Ye Win](https://www.linkedin.com/in/ye-win-1a33a292/)  <br> Email Address - <a href="mailto:yewin.mmr@gmail.com?">yewin.mmr@gmail.com</a> <br> WhatsApp - [+959252656065](https://wa.me/959252656065?text=Hi) <br> Website - [My Website](https://yewin.me/)

Project Link: [Spring Cloud Config File Storage](https://github.com/yewin-mm/spring-cloud-config-files-storage)


<a name="becoming-a-sponsor"></a>
## 🥰 Becoming a Sponsor
If you like any of my projects or if you want to support my work, please kindly consider becoming a sponsor. <br>
It gives me great motivation and I can relentlessly maintain my projects and contribute to the open-source community.

<a href="https://www.buymeacoffee.com/yewin" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="150" ></a>


<a name="contributing"></a>
## ⭐ Contributing
Contributions are what make the open source community such an amazing place to be learnt, inspire, and create. Any contributions you make are **greatly appreciated**.
<br>If you want to contribute....
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/yourname`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeatures'`)
4. Push to the Branch (`git push -u origin feature/yourname`)
5. Open a Pull Request
