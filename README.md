# ☁️ Laboratório do bootcamp XP Inc. - Cloud com Inteligência Artificial

![GitHub repo size](https://img.shields.io/github/repo-size/ismael12br/resumo-do-lab)
![GitHub last commit](https://img.shields.io/github/last-commit/ismael12br/resumo-do-lab)
![GitHub license](https://img.shields.io/github/license/ismael12br/resumo-do-lab)

> Este repositório documenta os aprendizados adquiridos no laboratório de computação em nuvem, parte do bootcamp **Cloud com Inteligência Artificial** da DIO em parceria com a XP Investimentos. O conteúdo aborda desde os conceitos fundamentais até a aplicação prática com foco na plataforma Microsoft Azure.

---

## 📚 Sumário

- [☁️ Computação em nuvem](#☁️-computação-em-nuvem)
- [🔐 Responsabilidade compartilhada](#🔐-responsabilidade-compartilhada)
- [🌩️ Modelos de implantação](#🌩️-modelos-de-implantação)
  - [🔒 Nuvem privada](#🔒-nuvem-privada)
  - [🌐 Nuvem pública](#🌐-nuvem-pública)
  - [⚖️ Nuvem híbrida](#⚖️-nuvem-híbrida)
- [🛠️ Modelos de serviço](#🛠️-modelos-de-serviço)
  - [🖥️ IaaS](#🖥️-iaas)
  - [🧰 PaaS](#🧰-paas)
  - [📦 SaaS](#📦-saas)
- [💸 Despesas de capital (CapEx)](#💸-despesas-de-capital-capex)
- [💰 Despesas operacionais (OpEx)](#💰-despesas-operacionais-opex)
- [💡 Modelo baseado em consumo](#💡-modelo-baseado-em-consumo)
- [🏆 Benefícios da nuvem](#🏆-benefícios-da-nuvem)
  - [📶 Alta disponibilidade](#📶-alta-disponibilidade)
  - [📈 Escalabilidade](#📈-escalabilidade)
  - [🔁 Elasticidade](#🔁-elasticidade)
  - [🔒 Confiabilidade](#🔒-confiabilidade)
  - [📉 Previsibilidade](#📉-previsibilidade)
  - [🛡️ Segurança](#🛡️-segurança)
  - [⚙️ Governança](#⚙️-governança)
  - [🧩 Gerenciabilidade](#🧩-gerenciabilidade)
- [📘 Microsoft Azure](#📘-microsoft-azure)
  - [🌐 Visão geral](#🌐-visão-geral)
  - [🧩 Serviços do Azure](#🧩-serviços-do-azure)
- [🚀 Autor](#🚀-autor)

---

## ☁️ Computação em nuvem

A computação em nuvem é o fornecimento de serviços de computação pela Internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala.
Pode envolver a computação, rede e armazenamento.

## **🌥️ Tipos de nuvem**

### 🔒 Nuvem privada
- Ambiente criado pelas próprias organizações em seu datacenter sendo totalmente responsáveis pelos serviços que operam e não permitem acesso aos usuários fora da organização.
- As organizações têm controle total sobre os recursos e a segurança.
- As organizações são responsáveis pela manutenção e pelas atualizações de hardware.

### 🌐 Nuvem pública
- Pertence a serviços de nuvem ou provedor de hosting, fornece recursos e serviços a várias organizações e usuários, podendo ser acessada por meio de uma conexão segura.
- Nenhuma despesa de capital para escalar verticalmente.
- Os aplicativos podem ser provisionados e desprovisionados rapidamente.
- As organizações pagam apenas pelo que utilizam.

### ⚖️ Nuvem híbrida
- Combinação entre nuvem privada e nuvem pública para permitir que aplicativos sejam executados no local mais adequado.
- As organizações determinam onde executar seus aplicativos.
- As organizações controlam a segurança, a conformidade e os requisitos legais.
- Fornece a maior flexibilidade.

---

## 💸 Despesas de capital (CapEx)
- O gasto inicial de dinheiro em infraestrutura física.
- As despesas do CapEx têm um valor que se reduz com o tempo.

## 💰 Despesas operacionais (OpEx)
- Gastar com produtos e serviços conforme necessário, pagamento conforme o uso.
- Seja cobrado imediatamente.

## 💡 Modelo baseado em consumo
- Os provedores de serviços em nuvem operam em um modelo baseado no consumo, o que significa que os usuários finais pagam somente pelos recursos que usam.
- Melhor previsão de custos.
- São fornecidos preços para recursos e serviços individuais.
- A cobrança é feita com base no seu uso real.

---

## 🏆 Benefícios da nuvem
- **📶 Alta disponibilidade**: A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer. Contém garantia de tempo de atividade, dependendo do serviço. Essas garantias fazem parte dos SLAs (Contratos de Nível de Serviço).

- **📈 Escalabilidade**: Refere-se a capacidade de ajustar recursos para atender à demanda, ou seja, poderá adicionar mais recursos para lidar melhor com o aumento da demanda ou reduzir recursos quando a demanda cair, garantindo que pagará apenas pelo que utilizar.

- **🔁 Elasticidade**: Se ocorrer um aumento repentino da demanda, seus recursos poderiam ser expandidos, logo, ao reduzir a demanda, os recursos também poderão ser reduzidos horizontalmente de forma automatizada ou manual.

- **🔒 Confiabilidade**: Devido a sua descentralização, possui infraestrutura confiável e resiliente, permitindo que se tenha recursos implantados em várias regiões do mundo. Logo, se houver uma catástrofe em uma região, as outras ainda funcionarão normalmente.

- **📉 Previsibilidade**: Permite que avance com confiança, seja no desempenho ou no custo.

- **🛡️ Segurança**: A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes, mas é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.

- **⚙️ Governança**: A auditoria baseada em nuvem ajuda a sinalizar recursos fora de conformidade e propõe estratégias de mitigação.

- **🧩 Gerenciabilidade**: Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo: escalar automaticamente a implantação de recursos com base na necessidade; implantar recursos com base em modelo pré-configurado; implantar recursos por meio de portal da web, por linha de comando, por APIs ou usando o PowerShell.

## 🛠️ Tipos de serviço de nuvem
- **🖥️ IaaS** (infraestrutura como serviço): Cria uma infraestrutura de TI de pagamento conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem. É o serviço mais flexível onde você configura e gerencia o hardware para seu aplicativo.

- **🧰 PaaS** (plataforma como serviço): Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente. Foco no desenvolvimento de aplicativos e permite o gerenciamento da plataforma por meio da nuvem.

- **📦 SaaS** (Software como Serviço): Os usuários se conectam e usam aplicativos com base em nuvem pela Internet: por exemplo, Microsoft Office 365, email e calendários. Os usuários para apenas o software que utilizam (modelo de assinatura).

## 🏗️ Arquitetura e serviços do Azure

### 🛡️ Identidade, acesso e segurança
- Microsoft Entra ID: serviço de identidade e acesso baseado em nuvem do Microsoft Azure.
- Permite autenticação.
- Logo único (SSO).
- Gerenciamento de aplicativos.
- B2B do Microsoft Entra External ID (permitindo que usuários autenticados em outros serviços também possam ser autenticados no Entra ID).
- B2C do Identidades Externas do Azure AD (permite que consumidores do aplicativo tenham acesso ao serviço, mesmo usando autenticação de outro serviço, como Google ou Facebook).
- Gerenciamento de dispositivos.

### 🏢 Microsoft Entra Domain Services
- Permite que se obtenha os benefícios dos serviços de domínio baseados em nuvem sem gerenciar os controladores de domínio.
- Execute aplicativos herdados (que não podem utilizar os padrões de autenticação modernos) na nuvem.
- Sincronizar automaticamente a partir do Microsoft Entra ID.

### 🔐 Autenticação X Autorização
- **Autenticação**: Identifica a pessoa ou serviço buscando acesso a um recurso; solicita credenciais de acesso legítimo; base para criar princípios de identidade e controle de acesso seguros.

- **Autorização**: Determina o nível de acesso de uma pessoa ou serviço autenticado; define quais dados eles podem acessar e o que podem fazer com eles.

- **Autenticação multifator**: Fornece segurança adicional para as identidades, exigindo dois ou mais elementos para autenticação completa.

### ⚙️ Acesso condicional
- É utilizado para reunir sinais, tomar decisões e impor políticas organizacionais.
- Utiliza-se de: associação de usuário ou grupo; local do IP; dispositivo; aplicativo e detecção de risco.

### 🧑‍💼 Controle de acesso baseado em função
- Gerenciamento de acesso de granularidade fina.
- Divida as tarefas dentro da equipe e conceda somente a quantidade de acesso de que os usuários precisam para trabalhar.
- Habilite o acesso ao portal do Azure e o controle de acesso aos recursos.
- Permissão herdada.

### 🧱 Confiança zero
- Permite que o usuário tenha acesso ao mínimo de permissões possíveis.

### 🧯 Proteção completa
- Uma abordagem em camadas para proteger sistemas de computador.
- Fornece vários níveis de proteção.
- Ataques contra uma camada são isolados das camadas subsequentes.

### 🛡️🧠 Microsoft Defender para Nuvem
- É um serviço de monitoramento que fornece proteção contra ameaças nos datacenters do Azure e locais.
- Fornce recomendações de segurança.
- Detecta e bloqueia malware.
- Analisa e identifica ataques potenciais.
- Controle de acesso just-in-time para portas.

---

Projeto desenvolvido como parte do bootcamp Cloud com IA – DIO e XP Investimentos.

---

Este projeto permitiu colocar em prática os conceitos de nuvem e IA aprendidos em curso/bootcamp. Foram utilizados serviços reais de computação em nuvem e aplicações de linguagem natural para simular cenários profissionais.

---

## 🚀 Autor

- **Ismael Lopes**  
- GitHub: [@ismael12br](https://github.com/ismael12br)  
- LinkedIn: [linkedin.com/in/ismael-lopes](https://linkedin.com/in/ismael-lopes)
