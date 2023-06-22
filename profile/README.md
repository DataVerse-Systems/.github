![mygreatheader](systems.gif)

| David Prutch | David Siebert |
|:---------------:|:----------:|
|   [![linkedin](https://github.com/201d8-team1/.github/blob/main/profile/icons8-linkedin-100.png)](https://www.linkedin.com/in/david-prutch-1027/) [![github](https://github.com/201d8-team1/.github/blob/main/profile/icons8-github-94.png)](https://github.com/PrutchD) | [![linkedin](https://github.com/201d8-team1/.github/blob/main/profile/icons8-linkedin-100.png)](https://www.linkedin.com/in/davidpsiebert/) [![github](https://github.com/201d8-team1/.github/blob/main/profile/icons8-github-94.png)](https://github.com/Siebert-David) |

| Gerald Reitmeyer | Robert Gillespie |
|:------------------:|:------------:|
|   [![linkedin](https://github.com/201d8-team1/.github/blob/main/profile/icons8-linkedin-100.png)](https://www.linkedin.com/in/gerald-reitmeyer/) [![github](https://github.com/201d8-team1/.github/blob/main/profile/icons8-github-94.png)](https://github.com/gerreit) | [![linkedin](https://github.com/201d8-team1/.github/blob/main/profile/icons8-linkedin-100.png)](https://www.linkedin.com/in/robert-gillespie-420918272/)[![github](https://github.com/201d8-team1/.github/blob/main/profile/icons8-github-94.png)](https://github.com/Puyallup253) |

# Repositories
[Documentation](https://github.com/DataVerse-Systems/Documentation)

[Presentation and Project Organizatioin](https://github.com/DataVerse-Systems/Presentation-and-Project-Organization-)

[Scripts](https://github.com/DataVerse-Systems/Scripts)

# Purpose

DataVerse Solutions is an organization created as a course project. Our group is currently enrolled at [CodeFellows](https://www.codefellows.org/) in the Cyber Security Engineering program.

# Scenario 
DataVerse Systems Is a subsidiary of Globex. We handle all It infrastructure for Globex and their aquisitions. SunFlow, a startup that develops solar powered smart home devices, was just purchased by Globex. Our task is to update SunFlow's core IT infrastructure and prototype the process of integrating new companies.

# Initial Setup 
Simulate Globex Cloud Server.
- We created a Virtual Private Cloud on AWS.
- We also created a Private EC2 instance running Windows Server 2019.
- We configured DNS and created the Globex domain.

# Solutions
- Our team established IPSec VPN connection between AWS VPC and SunFlow internal network running pfSense Router.
- We established Windows Server as primary DNS server for pfSense router.
- We connected Windows 10 Host computers to Globex domain for global access to resources providing Authentication and Authorization.
- We also configured traffic mirroring on the AWS side of the VPN for Accounting of network traffic between SunFlow and Globex.

# Documentation Reopsitory
[Documentation](https://github.com/DataVerse-Systems/Documentation) houses all the standard operating procedures and network design elements used to fulfill the requirements of this prototype network implementation.

# Scripts Repository
[Scripts](https://github.com/DataVerse-Systems/Scripts) contains any and all scripts created to automate the network setup process for future repeatability.

# Presentation and Project Organization
[Presentation and Project Organizatioin](https://github.com/DataVerse-Systems/Presentation-and-Project-Organization-) contains our teams preparation paperwork, presentation materials and a link to our [Presentation Video]().
