# 🚀 AWS Infrastructure Lab

<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/contatodavidson-pixel/aws-infra-lab?color=blue&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/contatodavidson-pixel/aws-infra-lab?color=green&style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/contatodavidson-pixel/aws-infra-lab?color=orange&style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)

**Repositório de estudos práticos em Cloud AWS, DevOps e Infraestrutura como Código**

*Aprendendo na prática | Construindo portfólio | Evoluindo continuamente*

</div>

---

## 👋 Sobre este Repositório

Este repositório documenta minha jornada de aprendizado em **Cloud Computing** e **DevOps**, com foco prático na plataforma **AWS**. Cada projeto aqui representa um experimento real, com erros, acertos e lições aprendidas.

> 💡 **Por que criei este repositório?**
> Para sair da teoria e colocar a mão na massa. Acredito que o melhor jeito de aprender é construindo — mesmo que imperfeito no começo.

---

## 🗂️ Projetos

| Projeto | Descrição | Tecnologias | Status |
|---------|-----------|-------------|--------|
| 🔜 VPC do Zero | Criar uma VPC completa com subnets, IGW e route tables | Terraform, AWS VPC | Em breve |
| 🔜 EC2 + Load Balancer | Subir instâncias EC2 com auto scaling e ALB | Terraform, EC2, ALB | Em breve |
| 🔜 Deploy com CI/CD | Pipeline de deploy automatizado com GitHub Actions | GitHub Actions, AWS | Em breve |

> Os projetos serão adicionados progressivamente conforme avanço nos estudos.

---

## 🧠 Arquitetura de Referência

```
Usuário → Internet → Load Balancer (ALB)
                          ↓
              ┌───────────┴───────────┐
           EC2 (AZ-1)           EC2 (AZ-2)
              └───────────┬───────────┘
                          ↓
                    RDS (banco de dados)
                          ↓
                 S3 (armazenamento / logs)
```

---

## ☁️ Serviços AWS que Estou Estudando

- **EC2** — Instâncias de computação em nuvem
- **S3** — Armazenamento de objetos
- **RDS** — Banco de dados gerenciado
- **IAM** — Controle de identidade e acesso
- **VPC** — Rede privada virtual
- **CloudWatch** — Monitoramento e logs
- **ALB / Auto Scaling** — Alta disponibilidade

---

## 🛠️ Ferramentas & Tecnologias

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

---

## 📚 Roadmap de Estudos

- [x] Criar conta AWS e configurar IAM
- [x] Criar repositório no GitHub
- [ ] Provisionar primeira VPC com Terraform
- [ ] Subir instância EC2 e acessar via SSH
- [ ] Configurar S3 com políticas de acesso
- [ ] Criar pipeline CI/CD com GitHub Actions
- [ ] Implementar monitoramento com CloudWatch

---

## 🔐 Boas Práticas que Sigo

- Nunca exponho credenciais AWS no código
- Uso variáveis de ambiente e Secrets do GitHub
- Sigo o princípio do menor privilégio no IAM
- Documento cada projeto com README próprio

---

## 👨‍💻 Sobre Mim

**Davidson Batista** — Profissional em transição para a área de Cloud & DevOps.

Estou construindo meu portfólio técnico na prática, projeto a projeto.

🔗 **GitHub:** [github.com/contatodavidson-pixel](https://github.com/contatodavidson-pixel)

---

## ⭐ Contribuições

Sugestões, dicas e feedback são muito bem-vindos!
Se este repositório te ajudou de alguma forma, deixe uma ⭐ — isso me motiva a continuar!

---

<div align="center">
<i>🚧 Repositório em constante evolução — acompanhe o progresso!</i>
</div>
