<div align="center">
  <h1>🧒 Portal Institucional · Associação Casa da Criança e do Adolescente</h1>
  <p><strong>Plataforma Socioeducativa Filantrópica · Captação Solidária, Projetos Comunitários & Transparência</strong></p>
  <p>
    <a href="https://github.com/frfernando/website-ass-casa-crianca"><img src="https://img.shields.io/badge/Status-Produção-22c55e?style=for-the-badge&logo=statuspage&logoColor=white" alt="Status" /></a>
    <a href="https://github.com/frfernando/website-ass-casa-crianca"><img src="https://img.shields.io/badge/Causa-Educação_&_Infância-FF5F00?style=for-the-badge&logo=probot&logoColor=white" alt="Causa Social" /></a>
    <a href="https://github.com/frfernando/website-ass-casa-crianca"><img src="https://img.shields.io/badge/Governança-Marco_Legal_MROSC-3b82f6?style=for-the-badge&logo=civicrm&logoColor=white" alt="Governança" /></a>
  </p>
</div>

---

## 📌 Visão Geral do Estudo de Caso

A **Associação Casa da Criança e do Adolescente de Regente Feijó - SP** é uma organização da sociedade civil que promove oficinas pedagógicas, esportivas, culturais e reforço socioeducativo para centenas de crianças e jovens no contraturno escolar.

O projeto consistiu no desenvolvimento de uma **Sede Digital Acolhedora e Transparente**, com o objetivo de conectar a entidade a padrinhos e doadores, recrutar voluntários capacitados e cumprir com excelência as exigências de transparência perante o Tribunal de Contas do Estado (TCE-SP) e o Ministério Público.

---

## 🔍 O Antes (O Desafio)

* **Invisibilidade das Oficinas e Ações Diárias:** A entidade executava um trabalho pedagógico de alto impacto com teatro, judô, informática e música, mas não possuía uma vitrine digital pública para registrar e compartilhar essas conquistas com a sociedade.
* **Falta de um Canal Digital de Doações Recorrentes:** Doadores locais e empresas parceiras encontravam dificuldades para saber como realizar contribuições financeiras ou doações de insumos escolares.
* **Dificuldade na Divulgação de Chamamentos Públicos:** Dificuldade em centralizar a prestação de contas dos termos de colaboração celebrados com a administração municipal.

---

## 💡 O Porquê (A Estratégia de Engenharia)

* **Por que Portal de Transparência Aberto (`transparencia.html`)?**  
  Construção de uma área documental em estrita conformidade com a Lei de Acesso à Informação (Lei nº 12.527/11) e o MROSC (Lei nº 13.019/14), abrigando atas de posse, relatórios financeiros e demonstrativos de recursos públicos repassados.
* **Por que Galeria de Projetos e Vídeos de Baixo Consumo?**  
  Implementação de área multimídia com fotos das atividades e players de vídeo otimizados para rápida reprodução em smartphones sem consumir os dados móveis de famílias e voluntários.
* **Por que Arquitetura Estática & Custo Zero de Infraestrutura?**  
  Entidades filantrópicas precisam direcionar cada centavo para as crianças. O projeto foi projetado para rodar em arquitetura serverless estática, garantindo **R$ 0,00 de custo mensal de servidor**.

---

## 🚀 O Depois (Resultados & Impacto)

| Métrica / Critério | Cenário Anterior | Novo Portal Casa da Criança |
|---|---|---|
| **Credibilidade Institucional** | Ausência de domínio próprio | **Sede Digital oficial com prestação de contas pública** |
| **Captação de Voluntários & Apoio** | Apenas boca a boca | **Formulários e canais diretos integrados ao WhatsApp** |
| **Acesso a Editais e Parcerias** | Barreira técnica para empresas auditadas | **Certidões e balanços contábeis abertos para download** |
| **Custo de Hospedagem Web** | Orçamentos caros de agências | **R$ 0,00 mensal (Zero Custo Recorrente)** |

---

## 🧰 Estrutura de Páginas & Stack Tecnológica

* **Páginas Modulares:**
  * `index.html`: Banner de acolhimento, números de impacto social e galeria de depoimentos.
  * `projetos.html`: Detalhamento das oficinas socioeducativas (esporte, cultura, tecnologia e apoio psicossocial).
  * `doar.html`: Chave PIX oficial, campanhas de apadrinhamento e contas bancárias institucionais.
  * `transparencia.html`: Repositório público de demonstrativos de receitas/despesas e relatórios fiscais.
  * `como-ajudar.html`, `quem-somos.html`, `contato.html`: Portais de voluntariado e localização.
* **Stack:** `HTML5 Semântico`, `CSS3 Moderno`, `Design Mobile-First` e `JavaScript Vanilla Leve`.

---

## 🛠️ Como Executar o Projeto Localmente

```bash
# 1. Clonar o repositório
git clone https://github.com/frfernando/website-ass-casa-crianca.git
cd website-ass-casa-crianca

# 2. Iniciar servidor local
python3 -m http.server 8080
# Acesse no navegador: http://localhost:8080
```

---

<div align="center">
  <p>Engenharia e Arquitetura desenvolvidas por <b><a href="https://github.com/frfernando">Fernando Reis</a></b> · <b><a href="https://sanbernarda.com">SanBernarda Studio</a></b></p>
</div>
