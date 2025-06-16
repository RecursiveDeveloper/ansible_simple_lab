## 🚀 About Me
I'm a junior DevOps engineer with some expertise in BackEnd development using Java and Node.js; scripting skills with Python, Bash and JavaScript; besides CI/CD and cloud knowledge of AWS and Azure DevOps tools ...

<p align="center">
<img src="https://c4.wallpaperflare.com/wallpaper/694/164/1000/digital-art-animals-eagle-bird-of-prey-birds-hd-wallpaper-preview.jpg" alt="Logo" width="400" height="230">
</p>

![linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![mysql](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white)
![aws](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![azuredevops](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)

## 🔗 Portfolio
[![portfolio](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RecursiveDeveloper)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jhoan-jesus-ortiz-sandoval-a66152198/)

# Provision an Apache Web Server with Ansible and Vagrant

This project provisions a local Ubuntu virtual machine using Vagrant and installs an Apache web server using Ansible. The Ansible playbook installs common utilities, sets up Apache (with support for both Debian and RedHat families), ensures the service is running, and deploys a simple HTML welcome page.

![Simple_Ansible-lab_diagram](https://raw.githubusercontent.com/RecursiveDeveloper/static-media-content/refs/heads/main/Simple_Ansible-lab_diagram_2.png)

## Tech Stack 

- **Client:** ---
- **Server:** Apache (provisioned via Ansible)
- **Database:** ---
- **Cloud provider:** ---
- **Tools:** Vagrant, Ansible

## Installation

1. Install VirtualBox as your virtual machine provider [Install VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. Install Vagrant according to your operating system [Install Vagrant](https://developer.hashicorp.com/vagrant/downloads)

## Deployment

To deploy this project run

```bash
  vagrant up
```

This will start a VM, install Ansible, and run the playbook to provision Apache and other utilities.

For more information about Vagrant commands check [vagrant-cheat-sheet](https://gist.github.com/wpscholar/a49594e2e2b918f4d0c4)

If needed, you can modify the playbook tasks in [playbooks/playbook.yml](playbooks/playbook.yml) to include additional packages or configuration.

## Authors

- [@RecursiveDeveloper](https://github.com/RecursiveDeveloper)

## License