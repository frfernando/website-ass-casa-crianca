<div align="center">
  <h1>🧒 Portal Institucional · Associação Casa da Criança e do Adolescente</h1>
  <p><strong>Plataforma Socioeducativa Filantrópica · Captação Solidária, Projetos Comunitários & Transparência</strong></p>
  <p>
    <a href="https://casa-da-crianca-regente-feijo.pages.dev"><img src="https://img.shields.io/badge/Site-Publicado-22c55e?style=for-the-badge&logo=cloudflarepages&logoColor=white" alt="Site publicado no Cloudflare Pages" /></a>
    <a href="https://github.com/frfernando/website-ass-casa-crianca"><img src="https://img.shields.io/badge/Causa-Educação_&_Infância-FF5F00?style=for-the-badge&logo=probot&logoColor=white" alt="Causa Social" /></a>
    <a href="https://github.com/frfernando/website-ass-casa-crianca"><img src="https://img.shields.io/badge/Governança-Marco_Legal_MROSC-3b82f6?style=for-the-badge&logo=civicrm&logoColor=white" alt="Governança" /></a>
  </p>
</div>

---

## 📌 Visão Geral do Estudo de Caso

A **Associação Casa da Criança e do Adolescente de Regente Feijó - SP** tem um portal institucional com informações sobre sua atuação, o Serviço de Acolhimento em Família Acolhedora, canais de contato, formas de apoio e uma área de transparência.

**Site publicado:** [casa-da-crianca-regente-feijo.pages.dev](https://casa-da-crianca-regente-feijo.pages.dev). O domínio próprio da associação não foi alterado.

---

## 🎯 Objetivo do Portal

* Reunir informações institucionais e sobre o Serviço de Acolhimento em Família Acolhedora.
* Facilitar o acesso aos canais de contato e às formas de apoio.
* Apresentar referências de transparência, sem sugerir que arquivos não anexados estejam disponíveis para download.

---

## 💡 O Porquê (A Estratégia de Engenharia)

* **Transparência:** A página apresenta referências a documentos institucionais. Os arquivos não estão anexados ao portal; a disponibilidade deve ser confirmada diretamente com a associação.
* **Contato e interesse:** Os formulários preparam um rascunho de e-mail para a pessoa revisar e enviar. Não há endpoint/backend recebendo ou armazenando os dados.
* **Hospedagem:** O site está publicado no Cloudflare Pages no projeto `casa-da-crianca-regente-feijo`. O status de produção no Pages não implica que o domínio próprio esteja configurado.

---

## 🚀 O Depois (Resultados & Impacto)

| Área | Estado atual |
|---|---|
| Site institucional | Publicado em `casa-da-crianca-regente-feijo.pages.dev` |
| Formulários | Abrem rascunho `mailto:`; envio depende da pessoa e de seu aplicativo de e-mail |
| Documentos | Referências na página; arquivos devem ser solicitados e sua disponibilidade confirmada |
| Domínio próprio | Não conectado por este projeto |

---

## 🧰 Estrutura de Páginas & Stack Tecnológica

* **Páginas:** `index.html` reúne as rotas institucionais em uma interface de navegação client-side; `wireframe.html` é uma prévia marcada para não indexação.
* **Stack:** `HTML5`, CSS e JavaScript no cliente, Tailwind Play CDN e publicação estática no Cloudflare Pages.

---

## 🛠️ Como Executar o Projeto Localmente

```bash
# 1. Clonar o repositório
git clone https://github.com/frfernando/website-ass-casa-crianca.git
cd website-ass-casa-crianca

# 2. Iniciar servidor local (na raiz clonada do repositório)
python3 -m http.server 8080
# Acesse no navegador: http://localhost:8080

# Publicar no projeto Pages deste site
npx wrangler pages deploy . --project-name=casa-da-crianca-regente-feijo --branch=main
```

---

<div align="center">
  <p>Engenharia e Arquitetura desenvolvidas por <b><a href="https://github.com/frfernando">Fernando Reis</a></b> · <b><a href="https://sanbernarda.com">SanBernarda Studio</a></b></p>
</div>
