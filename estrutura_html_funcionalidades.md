# Estrutura HTML e Funcionalidades Modernas para o FBBRODONTO

## Estrutura HTML Leve

### Arquitetura de Arquivos
```
/
├── index.html           # Página principal
├── css/
│   ├── styles.css       # Estilos principais
│   └── responsive.css   # Estilos responsivos
├── js/
│   ├── main.js          # Funcionalidades principais
│   └── components.js    # Componentes interativos
└── images/              # Diretório de imagens
```

### Estrutura HTML Base
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="FBBRODONTO - Plataforma gratuita de estudos em odontologia">
    <title>FBBRODONTO - Estudar odontologia agora ficou fácil</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="css/responsive.css">
    <!-- Fontes Google -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome para ícones -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <!-- Logo e navegação -->
    </header>
    
    <!-- Banner Principal -->
    <section class="hero">
        <!-- Conteúdo do banner -->
    </section>
    
    <!-- Seções de conteúdo -->
    <main>
        <!-- Seção de Impacto -->
        <section class="impact">
            <!-- Conteúdo sobre impacto -->
        </section>
        
        <!-- Resumos Nota 10 -->
        <section class="summaries">
            <!-- Cards de resumos -->
        </section>
        
        <!-- Assistente Virtual -->
        <section class="assistant">
            <!-- Conteúdo do assistente DON -->
        </section>
        
        <!-- Questões de Prova -->
        <section class="questions">
            <!-- Conteúdo de questões -->
        </section>
        
        <!-- Teste de Conhecimento -->
        <section class="knowledge-test">
            <!-- Conteúdo de testes -->
        </section>
        
        <!-- Cursos -->
        <section class="courses">
            <!-- Conteúdo de cursos -->
        </section>
    </main>
    
    <!-- Rodapé -->
    <footer>
        <!-- Conteúdo do rodapé -->
    </footer>
    
    <!-- Scripts JS -->
    <script src="js/components.js"></script>
    <script src="js/main.js"></script>
</body>
</html>
```

## Otimizações para HTML Leve

1. **Carregamento Assíncrono de Scripts**
   ```html
   <script src="js/main.js" async defer></script>
   ```

2. **Lazy Loading para Imagens**
   ```html
   <img src="placeholder.jpg" data-src="imagem-real.jpg" alt="Descrição" class="lazy-load">
   ```

3. **Minificação de CSS e JS**
   - Arquivos CSS e JS serão minificados para produção

4. **Otimização de Imagens**
   - Uso de WebP para melhor compressão
   - Dimensionamento adequado para cada dispositivo

5. **Uso de SVG para Ícones**
   - Ícones vetoriais leves em vez de imagens raster

## Funcionalidades Modernas

### 1. Assistente Virtual Interativo (DON)
- Interface de chat com IA
- Respostas rápidas para dúvidas comuns
- Sugestões de conteúdo relacionado
- Implementação com JavaScript puro (sem dependências pesadas)

### 2. Sistema de Resumos Interativos
- Navegação por tabs entre diferentes especialidades
- Modo de leitura com ajuste de fonte e contraste
- Marcadores e destaques personalizados
- Compartilhamento direto para redes sociais

### 3. Banco de Questões Dinâmico
- Filtros por especialidade, dificuldade e tema
- Feedback imediato após resposta
- Explicações detalhadas para cada questão
- Progresso salvo localmente (localStorage)

### 4. Modo Estudo Focado
- Timer pomodoro integrado
- Bloqueio de distrações
- Notificações de intervalos
- Estatísticas de estudo

### 5. Flashcards Interativos
- Sistema de repetição espaçada
- Criação de flashcards personalizados
- Compartilhamento de conjuntos de flashcards
- Sincronização entre dispositivos

### 6. Competição de Conhecimento
- Ranking entre amigos
- Desafios diários
- Conquistas e medalhas
- Compartilhamento de resultados

### 7. Modo Offline
- Conteúdo principal disponível offline
- Sincronização automática quando online
- Service Workers para cache de recursos

### 8. Personalização de Interface
- Temas claro/escuro
- Ajuste de tamanho de fonte
- Preferências de layout salvas

## Tecnologias Leves

1. **Vanilla JavaScript**
   - Sem frameworks pesados
   - Módulos ES6 para organização
   - Polyfills apenas quando necessário

2. **CSS Moderno**
   - Variáveis CSS para temas
   - Grid e Flexbox para layouts
   - Animações otimizadas

3. **Otimização de Performance**
   - Code splitting para carregar apenas o necessário
   - Preload de recursos críticos
   - Compressão de assets

4. **Acessibilidade**
   - ARIA labels
   - Navegação por teclado
   - Alto contraste opcional
   - Textos alternativos para imagens

5. **PWA (Progressive Web App)**
   - Instalável em dispositivos
   - Funcionalidades offline
   - Notificações push (opcional)

## Paleta de Cores Roxo e Verde

- **Roxo Principal**: #6a1b9a
- **Roxo Secundário**: #9c27b0
- **Roxo Claro**: #ce93d8
- **Verde Principal**: #2e7d32
- **Verde Secundário**: #43a047
- **Verde Claro**: #81c784
- **Neutro Escuro**: #333333
- **Neutro Claro**: #f5f5f5
