# Isaac Dev

## Visão Geral
Isaac Dev é um site pessoal e portfólio profissional projetado para destacar habilidades, projetos e experiências no desenvolvimento de software. O site apresenta uma interface moderna com tema ajustável e funcionalidades interativas.

## Características

### Design Responsivo
- Layout adaptável para todos os dispositivos (desktop, tablet e mobile)
- Interface intuitiva e de fácil navegação
- Experiência de usuário otimizada para diferentes tamanhos de tela

### Alternância de Tema
- Botão de tema personalizado localizado no meio do lado esquerdo
- Alternância fácil entre tema claro e escuro
- Preferência de tema armazenada para visitas futuras
- Animações suaves nas transições de tema

### Seções Principais
- **Início**: Apresentação pessoal e visão geral
- **Sobre**: Biografia, formação e habilidades
- **Projetos**: Portfólio de trabalhos com descrições detalhadas
- **Serviços**: Especialidades e serviços oferecidos
- **Blog**: Artigos técnicos e insights sobre desenvolvimento
- **Contato**: Formulário de contato e informações para conexão

## Tecnologias Utilizadas

### Frontend
- HTML5
- CSS3 (com animações e transições)
- JavaScript (ES6+)
- Biblioteca Font Awesome para ícones

### Performance
- Carregamento otimizado de recursos
- Código minificado para produção
- Imagens otimizadas para web

### Segurança
- Implementação de HTTPS
- Proteção contra ataques comuns (XSS, CSRF)
- Validação de dados nos formulários

## Instalação e Configuração

### Requisitos
- Servidor web (Apache, Nginx, etc.)
- Navegador moderno com suporte a JavaScript

### Passos para Instalação
1. Clone o repositório:
   ```
   git clone https://github.com/seu-usuario/isaac-dev.git
   ```

2. Navegue até o diretório do projeto:
   ```
   cd isaac-dev
   ```

3. Abra o arquivo `index.html` em seu navegador ou configure seu servidor web para apontar para o diretório do projeto.

## Personalização

### Modificando o Tema
O tema pode ser facilmente personalizado editando as variáveis CSS no arquivo `styles.css`:

```css
:root {
  --primary-color: #4F46E5;
  --secondary-color: #6366F1;
  --text-color-light: #333333;
  --text-color-dark: #e0e0e0;
  --background-light: #f5f5f5;
  --background-dark: #121212;
}
```

### Adicionando Projetos
Para adicionar novos projetos ao portfólio, edite o arquivo `projects.js`:

```javascript
const projects = [
  {
    title: "Nome do Projeto",
    description: "Descrição detalhada do projeto",
    technologies: ["HTML", "CSS", "JavaScript"],
    image: "caminho/para/imagem.jpg",
    link: "https://link-do-projeto.com"
  },
  // Adicione mais projetos aqui
];
```

## Contribuição
Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do repositório
2. Crie uma branch para sua feature: `git checkout -b feature/nova-feature`
3. Faça commit das suas mudanças: `git commit -m 'Adiciona nova feature'`
4. Envie para o branch: `git push origin feature/nova-feature`
5. Abra um Pull Request

## Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.

## Contato
Isaac - [email@isaacdev.com](mailto:email@isaacdev.com)

Website: [www.isaacdev.com](https://www.isaacdev.com)

LinkedIn: [linkedin.com/in/isaacdev](https://linkedin.com/in/isaacdev)

GitHub: [github.com/isaacdev](https://github.com/isaacdev)

---

&copy; 2025 Isaac Dev. Todos os direitos reservados.
