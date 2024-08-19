## Hello!

Nice to meet you, my name is Sergei Ivanov 👋 

### About me:
I'm an **OpenStack Engineer** with over 6 years of experience in deploying, maintaining, and troubleshooting in private and public clouds. IT professional with 17+ years, specializing in Linux administration for more than a decade. Managed diverse cloud projects using tools like kolla-ansible, openstack-ansible, kayobe, etc.

Also interested in **networks** and the **Python** programming language.

### Contacts:
<div id="socials" align="center"><a href="https://www.linkedin.com/in/ivanov-sergei/"><img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:ivanovs.it@gmail.com"><img src="https://img.shields.io/badge/mail-blue?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</div>

### Skills:
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/openstack/openstack-original.svg" height="75" width="75" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ansible/ansible-plain.svg" height="75" width="75" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/terraform/terraform-original.svg" height="75" width="75" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bash/bash-original.svg" height="75" width="75" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" height="75" width="75" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/prometheus/prometheus-original.svg" height="75" width="75" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-plain.svg" height="75" width="75" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/gitlab/gitlab-original.svg" height="75" width="75"/>&nbsp;
    
### Projects:
---
* **2018**
  * **Deploying OpenStack version Queens in a closed-network circuit.**    
  Customer: One of the largest fintech companies in Russia.  
  *Stack: foreman, git, ansible, openstack, gitlab-ci*
    <details><summary>Details</summary>
    Project involved preparing an all-in-one image for deploying private clouds in a closed environment.<br>
    The image included all necessary components such as OS packages, Python packages, and Ansible playbooks.<br>
    The project was based on the open-source <a href="https://github.com/openstack/openstack-ansible">openstack-ansible</a> project.<br>
    My role included preparing Ansible configuration in a test environment and customizing Ansible playbooks to meet client requirements.<br>
    Preparing documentation for the Operations team on deploying a private cloud.
  </details>

  **2019**
  * **Deploying a service region for bare metal deployment using the OpenStack Ironic project.**  
  Customer: One of the largest CDN providers in Europe.  
  *Stack: openstack, git, ansible, jenkins, diskimage-builder*
    <details><summary>Details</summary>
    To deploy the service region, the <a href="https://github.com/openstack/openstack-ansible">openstack-ansible</a> project was used.<br>
    Image preparation was done using the diskimage-builder project.<br>
    Setting up a CI/CD pipelines for Jenkins.
    </details>

  **2021**
  * **Deploying a new OpenStack distribution using the [Kayobe](https://github.com/openstack/kayobe) project.**  
    Customer: Public cloud provider.  
    *Stack: openstack, git, ansible, docker, prometheus, victoriametrics*
    <details><summary>Details</summary>
    The project aimed to replace the existing cloud with a new one that meets scalability, maintainability, and update criteria.<br>
    To meet business requirements, it was decided to use the <a href="https://github.com/openstack/kayobe">Kayobe</a> project, which includes <a href="https://github.com/openstack/bifrost">Bifrost</a> + <a href="https://github.com/openstack/kolla-ansible">Kolla-ansible</a>.<br>
    ML2/OVN was used as the Neutron backend.<br>
    Additional OpenStack components, including Octavia and Barbican, were integrated into the new distribution.<br>
    Monitoring based on Prometheus, VictoriaMetrics, and Grafana was also implemented.<br>
    Deployment adjustments were made to facilitate offline deployment using Pulp.<br>
    Functionality was verified using Tempest.<br>
    Performance thresholds were evaluated using Rally.<br>  
    My role in the project involved developing configurations for Kayobe, testing hypotheses, and cloud testing.
    </details>
