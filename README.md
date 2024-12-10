<h1 align="left">Introdução à Computação em Nuvem com Microsoft Azure</h1>

<h2 align="left">📘 Sobre a Computação em Nuvem</h2>

###

<p align="left">A computação em nuvem é um modelo revolucionário que permite o fornecimento de recursos de TI sob demanda por meio da internet. Empresas como a Microsoft, com sua plataforma Azure, transformam a maneira como desenvolvemos, armazenamos e gerenciamos soluções digitais.</p>

<p align="left"><strong>🌟 Principais Objetivos da Nuvem:</strong></p>

- <strong>Escalabilidade</strong>: Adapte os recursos conforme a demanda cresce ou diminui.
- <strong>Economia de custos</strong>: Pague apenas pelo que for usado, sem desperdícios.
- <strong>Acesso global</strong>: Trabalhe de qualquer lugar com uma conexão à internet.
- <strong>Inovação rápida</strong>: Lance soluções e serviços rapidamente.

<p align="left"><strong>💻 Casos de Uso:</strong></p>

- Hospedagem de aplicativos.
- Armazenamento e backup de dados.
- Análise de dados em tempo real.
- Gerenciamento de máquinas virtuais.

###

<h2 align="left">🔍 Comparação de Modelos de Nuvem</h2>

<p align="left">Os modelos de nuvem oferecem flexibilidade para diferentes necessidades de negócios e desenvolvimento.</p>

<table border="1" style="border-collapse: collapse; width: 100%; text-align: left;">
  <thead>
    <tr>
      <th style="padding: 8px; background-color: #f2f2f2;">Modelo</th>
      <th style="padding: 8px; background-color: #f2f2f2;">Descrição</th>
      <th style="padding: 8px; background-color: #f2f2f2;">Ideal Para...</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 8px;">Infraestrutura como Serviço (IaaS)</td>
      <td style="padding: 8px;">Recursos básicos como máquinas virtuais e armazenamento.</td>
      <td style="padding: 8px;">Controle total sobre infraestrutura.</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Plataforma como Serviço (PaaS)</td>
      <td style="padding: 8px;">Ferramentas para desenvolver e implantar aplicativos sem gerenciar hardware.</td>
      <td style="padding: 8px;">Foco no desenvolvimento de software.</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Software como Serviço (SaaS)</td>
      <td style="padding: 8px;">Soluções completas entregues via internet (ex.: Microsoft 365).</td>
      <td style="padding: 8px;">Usuários finais que precisam de acesso direto a aplicativos prontos.</td>
    </tr>
  </tbody>
</table>

<p align="left"><strong>🛠️ Estratégias de Implantação:</strong></p>

- <strong>Nuvem Pública</strong>: Recursos compartilhados e gerenciados por provedores como o Azure.
- <strong>Nuvem Privada</strong>: Ambiente exclusivo para uma única organização.
- <strong>Nuvem Híbrida</strong>: Combina benefícios da pública e privada.

###

<h2 align="left">⚖️ Comparação: CapEx vs OpEx</h2>

<p align="left">Na adoção de soluções em nuvem, entender os modelos de custo é essencial:</p>

<p align="left"><strong>🛠️ Estratégias de Implantação:</strong></p>

<table border="1" style="border-collapse: collapse; width: 100%; text-align: left;">
  <thead>
    <tr>
      <th style="padding: 8px; background-color: #f2f2f2;">CapEx (Capital Expenditure)</th>
      <th style="padding: 8px; background-color: #f2f2f2;">OpEx (Operational Expenditure)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 8px;">Investimentos iniciais elevados: Compra de servidores, data centers, etc.</td>
      <td style="padding: 8px;">Despesas contínuas: Pagamentos mensais pelos serviços utilizados.</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Controle total sobre hardware e software.</td>
      <td style="padding: 8px;">Maior flexibilidade e escalabilidade financeira.</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Custos fixos com depreciação ao longo do tempo.</td>
      <td style="padding: 8px;">Custos variáveis, alinhados à demanda.</td>
    </tr>
  </tbody>
</table>

🔑 <strong>Principal Vantagem</strong>: A computação em nuvem prioriza o modelo OpEx, permitindo previsibilidade de custos e eliminando a necessidade de grandes investimentos iniciais.

###

<h2 align="left">📎 Como começar com Microsoft Azure?</h2>

1. Explore as ofertas gratuitas do Azure: Teste máquinas virtuais, armazenamento e outros serviços.
2. Escolha o modelo ideal para o seu projeto: Avalie entre IaaS, PaaS ou SaaS.
3. Implemente sua estratégia de nuvem: Escolha pública, privada ou híbrida conforme suas necessidades.

###

<h2 align="left">📦 Opções de disponibilidade para máquinas virtuais do Azure</h2>

<p align="left">O Azure oferece várias opções para garantir alta disponibilidade de suas máquinas virtuais:</p>

- **Conjuntos de Disponibilidade (Availability Sets)**: Distribuem VMs entre racks diferentes dentro de um datacenter. Garantem SLA de até 99,95%.
- **Zonas de Disponibilidade (Availability Zones)**: Distribuem VMs entre datacenters diferentes na mesma região, garantindo SLA de até 99,99%.
- **Conjuntos de Escala (Scale Sets)**: Permitem criar e gerenciar várias VMs automaticamente, com balanceamento de carga.
- **Backup e Recuperação**: Restauram rapidamente VMs em caso de falhas.

###

<h2 align="left">📂 Criar uma conta de armazenamento no Azure</h2>

<p align="left">Uma conta de armazenamento no Azure gerencia seus dados na nuvem de maneira organizada e segura:</p>

- **Tipos de Armazenamento**:
  - **Blob Storage**: Para dados não estruturados como arquivos e imagens.
  - **File Storage**: Armazenamento compartilhado acessível via SMB.
  - **Queue Storage**: Gerencia mensagens em fila para comunicação de aplicativos.
  - **Table Storage**: Banco de dados NoSQL para dados estruturados.

- **Níveis de Desempenho**:
  - **Standard**: Econômico, ideal para dados acessados com menos frequência.
  - **Premium**: Baixa latência, adequado para dados frequentemente acessados.

- **Replicação de Dados**:
  - **LRS (Locally-redundant storage)**: Dados replicados dentro de um único datacenter.
  - **GRS (Geo-redundant storage)**: Dados replicados entre datacenters em diferentes regiões.

###

<h2 align="left">🧑‍💻 Autor</h2>

Este README foi elaborado para auxiliar desenvolvedores em aprendizagem a entender os fundamentos da computação em nuvem.

🔗 Licença: Livre para uso e adaptação.

###

<h2 align="left">Sobre mim</h2>

###

<p align="left">✨ Criando bugs desde ...<br>📚 Atualmente estou aprendendo ...<br>🎯 Metas ...<br>🎲 Curiosidade: ...</p>

###

<h2 align="left">Eu codifico com</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="40" alt="C# logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="Python logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="HTML logo" />
</div>

###
