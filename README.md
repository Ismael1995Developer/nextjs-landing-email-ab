
# Landing Page – Infoprodutos

<p align="center">
  <img src="./public/logo.png" alt="Logo do projeto" width="160" />
</p>

## 📖 Descrição do Projeto

**Landing Page – Infoprodutos** é um website desenvolvido para **divulgação e conversão de vendas digitais**, com foco em:

- Apresentação clara da oferta do infoproduto;  
- Copywriting otimizado para conversão;  
- Estrutura de CTA (Call to Action) estratégicos;  
- Layout responsivo e acessível;  
- Integração com ferramentas externas (e-mail marketing, checkout, analytics);  
- SEO & Open Graph para alcance orgânico e compartilhamento eficiente;  
- UI consistente com componentes acessíveis.  

### Projeto pensado para **alta conversão, acessibilidade e desempenho**, seguindo boas práticas do ecossistema **React/Next.js**.

## 🚀 Como instalar o projeto e rodar

### 🔗 Acesso Web (produção)
O site está hospedado na **Vercel**.  
URL [https://personal-portfolio-bfvm.vercel.app/]


## 📂 Estrutura de Pastas 
```bash
landingpage-infoprodutos/
├─ app/                    # Rotas/Layouts (App Router)
│  ├─ layout.tsx
│  ├─ page.tsx
│  └─ (sections)/...       # Seções da landing page (hero, oferta, depoimentos)
├─ components/             # Componentes reutilizáveis (shadcn/ui + custom)
├─ lib/                    # Utils, configs (ex.: next-seo.config.ts)
├─ public/                 # Imagens (logo, mockups, favicons, og-images)
├─ styles/                 # globals.css, tailwind utilities
├─ types/                  # Tipagens compartilhadas
├─ data/                   # JSON/TS com dados de produtos, depoimentos
├─ tailwind.config.ts
├─ postcss.config.js
├─ next.config.js
├─ tsconfig.json
└─ package.json
````

## ♿ Acessibilidade, SEO e Performance

* **A11y**: componentes Radix + semântica correta + foco/teclado.
* **SEO**: next-seo, metatags OG/Twitter, sitemaps, palavras-chave do nicho.
* **Performance**: imagens otimizadas (next/image), prefetch de rotas, lazy loading.
* **Conversão**: CTAs em destaque, timers e elementos de persuasão.
* **Responsividade**: Tailwind + breakpoints consistentes.


## 🗂 Versionamento

Versão atual: **1.0.0 (inicial)**


# 👤 Autor

*José Ismael Correia*

📧 [ismael1995internacional@gmail.com](mailto:ismael1995internacional@gmail.com)


## 📞 Contato e Suporte

* Issues e melhorias: abra uma **Issue** ou **Pull Request** no GitHub.
* Implantação: verifique o painel da Vercel e logs de build para troubleshooting.


## 📜 Licença do Projeto

Este repositório está licenciado sob a **All rights reserved**.



## 📚 Libs utilizadas

* **Next.js** – framework React para web moderna
* **React** – biblioteca UI
* **TypeScript** – tipagem estática
* **Tailwind CSS** – estilização utilitária
* **shadcn/ui** – camada de componentes pronta, sobre Radix
* **Radix UI** – primitives acessíveis
* **next-seo** – helpers para SEO
* **lucide-react** – ícones


## 🛠 Ferramentas, linguagem e frameworks

* **Linguagem**: TypeScript
* **Frameworks**: Next.js, React
* **Estilos**: Tailwind CSS + shadcn/ui
* **Ícones**: lucide-react
* **SEO**: next-seo
* **Controle de versão**: Git + GitHub
* **CI/CD & Hosting**: Vercel
* **Qualidade de código**: ESLint + Prettier

---

## 📦 Dependências

### Runtime (dependencies)

* next
* react / react-dom
* next-seo (MIT)
* lucide-react (ISC)
* shadcn/ui
* Radix UI (MIT)

### Desenvolvimento (devDependencies)

* typescript, @types/react, @types/node
* tailwindcss, postcss, autoprefixer
* eslint, eslint-config-next, prettier

---

## 📄 Licenças de Terceiros (avisos)

| Biblioteca / Recurso  | Licença | Fonte                                            |
| --------------------- | ------- | ------------------------------------------------ |
| next-seo              | MIT     | [GitHub](https://github.com/garmeeh/next-seo)    |
| Radix UI (primitives) | MIT     | [radix-ui.com](https://www.radix-ui.com/)        |
| shadcn/ui             | MIT     | [ui.shadcn.com](https://ui.shadcn.com/)          |
| lucide-react          | ISC     | [GitHub](https://github.com/lucide-icons/lucide) |
| Tailwind CSS          | MIT     | [tailwindcss.com](https://tailwindcss.com/)      |
| React / React DOM     | MIT     | [react.dev](https://react.dev/)                  |
| Next.js               | MIT     | [nextjs.org](https://nextjs.org/)                |

