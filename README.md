# SynapseAI Solutions - GitHub Pages

Site institucional da SynapseAI Solutions - IA Generativa Vertical para Finanças, Saúde e Educação.

## 📁 Estrutura do Projeto

```
synapse_ai/
├── index.html          # Página principal (synapseai-site)
├── 404.html           # Página de erro 404 customizada
├── README.md          # Documentação do projeto
├── assets/
│   ├── css/
│   │   └── style.css  # Estilos adicionais
│   ├── js/
│   │   └── script.js  # JavaScript adicional
│   └── images/        # Imagens do site
└── .nojekyll          # Desabilita o Jekyll no GitHub Pages
```

## 🚀 Como Usar

### Deploy Automático com GitHub Actions

1. **Crie um repositório no GitHub**
   - Nome do repositório: `synapse_ai` ou `[seu-usuario].github.io` (para página de usuário)

2. **Faça o upload dos arquivos**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/[seu-usuario]/synapse_ai.git
   git push -u origin main
   ```

3. **Configure o GitHub Pages (IMPORTANTE)**
   - Vá em **Settings** → **Pages**
   - Em **Source**, selecione: **GitHub Actions** (não "Deploy from a branch")
   - O workflow será executado automaticamente após o push

4. **Verifique o Deploy**
   - Vá na aba **Actions** do seu repositório
   - Você verá o workflow "Deploy to GitHub Pages" rodando
   - Após concluir com sucesso (✅), seu site estará disponível

5. **Acesse seu site**
   - URL: `https://[seu-usuario].github.io/synapse_ai/`
   - Ou: `https://[seu-usuario].github.io/` (se for repositório de usuário)
   - O link exato aparecerá no log do workflow

### Deploy Manual
Se preferir executar o deploy manualmente:
1. Vá na aba **Actions**
2. Selecione "Deploy to GitHub Pages"
3. Clique em "Run workflow"
4. Selecione a branch `main` e clique em "Run workflow"

## ✨ Funcionalidades

- **Design Moderno**: Interface clean e profissional
- **Produtos de IA**: Apresentação de soluções verticais para diferentes setores
- **Design Responsivo**: Adaptável a todos os dispositivos
- **Animações Suaves**: Transições e efeitos visuais elegantes
- **Seções Especializadas**: Finanças, Educação e Saúde
- **Página 404 Customizada**: Página de erro personalizada

## 🎨 Produtos Apresentados

### Soluções para Finanças
- **FinBrain**: Análise financeira com IA
- **RiskGen**: Gestão de riscos automatizada

### Soluções para Educação
- **EduMentor AI**: Tutor personalizado
- **CourseGen Studio**: Criador de cursos com IA

### Soluções para Saúde
- **ClinicaGPT**: Assistente médico inteligente

### Personalização
- O arquivo `index.html` contém todo o conteúdo e estilos inline
- Cores e design já otimizados para a marca SynapseAI
- Ícones e gráficos integrados via SVG inline

## 📝 Notas

- **GitHub Actions**: O deploy é feito automaticamente a cada push na branch `main`
- **Workflow**: O arquivo `.github/workflows/deploy.yml` configura o processo de deploy
- **Permissões**: O GitHub Actions precisa de permissões para fazer deploy no Pages
- O arquivo `.nojekyll` é importante para servir corretamente arquivos que começam com underscore
- Para formulário funcional, integre com serviços como Formspree, Netlify Forms ou backend próprio

## 🔧 Desenvolvimento Local

Para testar localmente:
1. Abra o arquivo `index.html` diretamente no navegador
2. Ou use um servidor local como Live Server no VS Code

## 📄 Licença

Este projeto está sob licença MIT. Sinta-se livre para usar e modificar.

## 🏢 Sobre a SynapseAI Solutions

A SynapseAI Solutions constrói produtos de IA generativa orientados a domínio para:
- **Finanças**: Análise e gestão de riscos
- **Educação**: Aprendizado personalizado
- **Saúde**: Assistência médica inteligente

## 👤 Autor

SynapseAI Solutions - IA Generativa Vertical

---

**Última atualização:** 2024