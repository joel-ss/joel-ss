> ☁️ Cloud · AWS · Infraestructura como Código

```hcl
module "joel" {
  role      = "IT Technician @ AD Systems"
  education = "Técnico Superior en Sistemas (CFGS ASIX)"
  focus     = ["AWS", "Terraform", "IaC"]
  learning  = ["Kubernetes (EKS)", "CI/CD"]
}
```

Me interesan las arquitecturas en la nube y automatizar infraestructura con
Terraform. Aquí recojo los proyectos en los que he ido trabajando, sobre todo
en el ecosistema de **AWS**.

---

### 🛠️ Tecnologías y herramientas

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-02A8EF?style=for-the-badge&logo=packer&logoColor=white)

---

### 📌 Proyectos destacados

**☁️ CI/CD con Terraform y GitHub Actions** — [Proyecto-Cloud/CI-CD-amb-Terraform-i-GitHub-Actions](https://github.com/Proyecto-Cloud/CI-CD-amb-Terraform-i-GitHub-Actions)
Trabajo final de la asignatura de Cloud (grupal). Pipeline CI/CD desacoplado que
despliega infraestructura en AWS con Terraform y una aplicación sobre Kubernetes
(EKS), orquestado con GitHub Actions: `terraform plan` comentado en cada Pull
Request, `apply` automático al hacer merge y estado remoto en S3 + DynamoDB con
*state locking*.
> *Mi parte:* el clúster **EKS** y la app de demostración (escalada en varios
> pods tras un Network Load Balancer) que sirve para validar el pipeline y
> visualizar el cambio de nodo/pod en cada despliegue.

**🎓 DRACS Hybrid — Infraestructura en AWS** — [DRAC-QUEENS/AWS](https://github.com/DRAC-QUEENS/AWS)
Trabajo Final de Grado (grupal): infraestructura híbrida on-premise + cloud. La
parte de AWS, escrita íntegramente en Terraform, despliega **GLPI** (ticketing e
inventario) sobre un **Auto Scaling Group multi-AZ**, con base de datos en **RDS
(MariaDB)** y ficheros compartidos en **EFS**, expuesto con TLS a través de
**NLB + ALB** y accesible desde la red on-premise mediante una **VPN WireGuard**.
Incluye imágenes base construidas con **Packer**, segmentación de red
pública/privada y copias de seguridad automatizadas.
> *Mi parte:* diseñé y desarrollé toda la infraestructura de AWS en Terraform
> (red, alta disponibilidad y balanceo, cómputo, seguridad y backups).

**📚 Ejercicios de Cloud** — [joel-ss/optcloud](https://github.com/joel-ss/optcloud)
Colección de ejercicios prácticos de la asignatura de Cloud, resueltos casi por
completo con Terraform (HCL): provisión de recursos en AWS y práctica de
infraestructura como código.

---

### 📫 Dónde encontrarme

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joel-sanchez-simon/)

<!--![Estadísticas](https://github-readme-stats.vercel.app/api?username=joel-ss&show_icons=true&theme=default)
-->
