---
title: "DevOps Engineer & Cloud Architect | Portfólio"
layout: hextra-home
draft: false
---

{{< hextra/hero-badge link="https://github.com/guilermiii" >}}
  <div class="hx:w-2 hx:h-2 hx:rounded-full hx:bg-emerald-500"></div>
  <span>Disponível para novos projetos & consultoria</span>
  {{< icon name="arrow-circle-right" attributes="height=14" >}}
{{< /hextra/hero-badge >}}

<div class="hx:mt-6 hx:mb-4">
{{< hextra/hero-headline >}}
  Engenharia DevOps & Cloud Native<br class="hx:sm:block hx:hidden" />Automação, Resiliência e Escala
{{< /hextra/hero-headline >}}
</div>

<div class="hx:mb-8">
{{< hextra/hero-subtitle >}}
  Especialista em orquestração com Kubernetes, automação de CI/CD com GitOps, infraestrutura como código (IaC) e observabilidade moderna para sistemas distribuídos de alta disponibilidade.
{{< /hextra/hero-subtitle >}}
</div>

<div class="hx:mb-12 hx:flex hx:gap-3 hx:flex-wrap">
  {{< hextra/hero-button text="Ver Documentação" link="/docs" >}}
  {{< hextra/hero-button text="Acessar o Blog" link="/blog" >}}
</div>

<div class="hx:mt-6"></div>

{{< hextra/hero-section heading="h2" >}}Áreas de Atuação & Especialidades{{< /hextra/hero-section >}}

{{< hextra/feature-grid cols="3" >}}
  {{< hextra/feature-card
    title="Kubernetes & Containers"
    icon="cube"
    subtitle="Implementação de clusters de alta disponibilidade, Helm charts, Service Mesh e estratégias avançadas de deploy canary e blue-green."
  >}}
  {{< hextra/feature-card
    title="CI/CD & GitOps"
    icon="refresh"
    subtitle="Construção de pipelines declarativos com GitHub Actions e GitLab CI, integrados ao ArgoCD para entrega contínua segura e auditável."
  >}}
  {{< hextra/feature-card
    title="Infraestrutura como Código"
    icon="server"
    subtitle="Provisionamento automatizado, modular e seguro com Terraform, OpenTofu, Ansible e arquiteturas cloud imutáveis."
  >}}
  {{< hextra/feature-card
    title="Observabilidade & SRE"
    icon="presentation-chart-line"
    subtitle="Monitoramento em tempo real com Prometheus, dashboards Grafana, tracing distribuído com OpenTelemetry e gestão focada em SLIs/SLOs."
  >}}
  {{< hextra/feature-card
    title="Segurança & DevSecOps"
    icon="shield-check"
    subtitle="Varredura de vulnerabilidades em pipelines (Trivy), gestão centralizada de segredos com HashiCorp Vault e políticas de RBAC."
  >}}
  {{< hextra/feature-card
    title="Cloud & FinOps"
    icon="cloud"
    subtitle="Arquiteturas resilientes em AWS e GCP com foco em alta disponibilidade, confiabilidade e otimização contínua de custos de infraestrutura."
  >}}
{{< /hextra/feature-grid >}}

<div class="hx:mt-12"></div>

{{< hextra/hero-section heading="h2" >}}Projetos & Casos de Uso{{< /hextra/hero-section >}}

{{< cards >}}
  {{< card
    link="/docs"
    title="Internal Developer Platform (IDP)"
    icon="terminal"
    tag="Kubernetes / Helm"
    subtitle="Construção de plataforma self-service para desenvolvedores, padronizando esteiras e reduzindo o tempo de entrega de semanas para minutos."
  >}}
  {{< card
    link="/docs"
    title="Migração Cloud & Modernização GitOps"
    icon="cloud-upload"
    tag="Terraform / ArgoCD"
    subtitle="Migração de workloads legados para infraestrutura conteinerizada e gerenciada 100% via código com reconciliação contínua."
  >}}
  {{< card
    link="/docs"
    title="Stack Unificada de Observabilidade"
    icon="chart-bar"
    tag="Prometheus / Grafana"
    subtitle="Implementação da stack LGTM (Loki, Grafana, Tempo, Mimir) para monitoramento de ponta a ponta e redução de 65% no MTTR."
  >}}
  {{< card
    link="/blog"
    title="Banana Blog: Artigos & Engenharia"
    icon="book-open"
    tag="Artigos Técnicos"
    subtitle="Tutoriais práticos, post-mortems de incidentes reais, automação de rotinas e melhores práticas do ecossistema Cloud Native."
  >}}
{{< /cards >}}

<div class="hx:mt-12"></div>

{{< hextra/hero-section heading="h2" >}}Ciclo de Entrega Contínua{{< /hextra/hero-section >}}

{{< steps >}}

### 1. Arquitetura Declarativa & IaC
Modelagem de topologias de rede, clusters e recursos em nuvem através de código versionado e modular com Terraform, garantindo isolamento total entre ambientes de desenvolvimento, homologação e produção.

### 2. Integração Contínua com DevSecOps
Validação automatizada de sintaxe, testes unitários, análise estática de segurança (SAST) e varredura de vulnerabilidades em imagens de contêineres com Trivy antes da publicação no registry.

### 3. Deploy Automatizado com GitOps
Sincronização declarativa via ArgoCD conectada ao repositório Git, executando validações pré-deploy, testes de fumaça (smoke tests) e suporte a rollback instantâneo caso os critérios de saúde falhem.

### 4. Observabilidade & Operações Confiáveis
Coleta centralizada de métricas e traces em tempo real com Prometheus e OpenTelemetry, disparando alertas inteligentes para os canais de plantão e sustentando práticas de SRE para maximizar a confiabilidade do sistema.

{{< /steps >}}

<div class="hx:mt-12"></div>

{{< hextra/hero-section heading="h2" >}}Stack & Ferramentas{{< /hextra/hero-section >}}

{{< tabs >}}

  {{< tab name="Containers & Cloud" >}}
- **Orquestração & Contêineres**: Kubernetes, Docker, Helm, Kustomize, Podman.
- **Provedores Cloud**: AWS (EKS, ECS, S3, IAM, VPC), Google Cloud (GKE), Azure (AKS).
- **Networking & Ingress**: Ingress NGINX, Traefik, Cert-Manager, Istio Service Mesh.
  {{< /tab >}}

  {{< tab name="CI/CD & GitOps" >}}
- **Pipelines**: GitHub Actions, GitLab CI, Jenkins.
- **Continuous Delivery & GitOps**: ArgoCD, Flux CD.
- **Registries de Artefatos**: Harbor, GitHub Packages (GHCR), AWS ECR.
  {{< /tab >}}

  {{< tab name="IaC & Automação" >}}
- **Infraestrutura como Código**: Terraform, OpenTofu, Terragrunt.
- **Gerenciamento de Configuração**: Ansible.
- **Construção de Imagens**: Packer.
- **Scripting & Automação**: Bash / Shell, Python, Go.
  {{< /tab >}}

  {{< tab name="Observabilidade & SRE" >}}
- **Métricas & Dashboards**: Prometheus, Grafana, VictoriaMetrics.
- **Logs & Tracing**: Loki, Promtail, OpenTelemetry, Tempo, Jaeger.
- **Alertas & Gestão de Incidentes**: Alertmanager, PagerDuty, Grafana OnCall.
  {{< /tab >}}

  {{< tab name="Segurança & Compliance" >}}
- **Segurança de Contêineres & IaC**: Trivy, Checkov, SonarQube, Cosign.
- **Gestão de Segredos**: HashiCorp Vault, AWS Secrets Manager, Sealed Secrets.
- **Políticas & Compliance**: Open Policy Agent (OPA) / Gatekeeper, Kyverno.
  {{< /tab >}}

{{< /tabs >}}

<div class="hx:mt-12"></div>

{{< hextra/hero-section heading="h2" >}}Vamos Conversar?{{< /hextra/hero-section >}}

{{< callout type="info" emoji="🚀" >}}
Interessado em acelerar suas esteiras de entrega contínua, estruturar uma plataforma em nuvem resiliente ou modernizar suas operações com Kubernetes e GitOps?

Conecte-se comigo no [GitHub](https://github.com/guilermiii/blog-banana-ops), explore os tutoriais práticos no [Banana Blog](/blog) ou consulte as documentações técnicas em [Documentos](/docs)!
{{< /callout >}}
