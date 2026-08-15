<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 750" width="100%" height="100%" style="background-color: #0d0d0d; font-family: 'SF Pro Display', 'Helvetica Neue', Helvetica, Arial, sans-serif;">
  <defs>
    <!-- Gradiente sutil para a barra de título -->
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#1c1c1e" />
      <stop offset="100%" stop-color="#151517" />
    </linearGradient>
    <!-- Gradiente para a imagem de fundo (simula a foto escura) -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#000000" />
      <stop offset="100%" stop-color="#111111" />
    </linearGradient>
  </defs>

  <!-- Fundo Principal -->
  <rect width="1200" height="750" fill="url(#bgGrad)" />

  <!-- Barra Superior -->
  <rect x="0" y="0" width="1200" height="45" fill="url(#titleGrad)" stroke="#333" stroke-width="0.5" />
  
  <!-- Botões da Janela (Mac) -->
  <circle cx="25" cy="22" r="6" fill="#ff5f57" />
  <circle cx="48" cy="22" r="6" fill="#febc2e" />
  <circle cx="71" cy="22" r="6" fill="#28c840" />

  <!-- Caminho do Terminal -->
  <text x="600" y="27" fill="#aaaaaa" font-size="13" text-anchor="middle" font-family="monospace">mumitacho.com.br — % ./profile.sh --live</text>

  <!-- Linha divisória -->
  <line x1="0" y1="45" x2="1200" y2="45" stroke="#333" stroke-width="1" />

  <!-- ================= CONTEÚDO PRINCIPAL ================= -->
  
  <!-- Coluna Esquerda: Foto da Mão (Renderizada em cima da outra) -->
  <!-- Você precisa substituir 'file:///...' pela URL real da sua imagem da mão -->
  <image href="file:///C:/Users/Downloads/segunda%20imagem.jpg" x="70" y="70" width="400" height="650" preserveAspectRatio="xMidYMid slice" opacity="0.85" />

  <!-- Coluna Direita: Informações -->
  <g transform="translate(520, 70)">
    
    <!-- Nome e Role -->
    <text x="0" y="40" fill="#ffffff" font-size="48" font-weight="bold" letter-spacing="1">Luis Gustavo</text>
    <text x="0" y="75" fill="#00ffcc" font-size="32" font-weight="bold">(Mumitacho)</text>
    <rect x="0" y="95" width="60" height="4" fill="#00ffcc" rx="2" />
    <text x="0" y="135" fill="#b0b0b0" font-size="22" font-weight="500">UI/UX Design, Frontend</text>
    <text x="0" y="165" fill="#888888" font-size="16">Londrina, Paraná, Brasil</text>

    <!-- Contato -->
    <text x="0" y="210" fill="#00ffcc" font-size="15" font-weight="bold">CONTATO</text>
    <rect x="0" y="220" width="180" height="1" fill="#333" />
    
    <text x="0" y="250" fill="#dcdcdc" font-size="14">📧 munitacho.com.br</text>
    <text x="0" y="275" fill="#dcdcdc" font-size="14">📷 @mumitacho</text>
    <text x="0" y="300" fill="#dcdcdc" font-size="14">🐙 github.com/mumitacho</text>

    <!-- Formação -->
    <text x="0" y="350" fill="#00ffcc" font-size="15" font-weight="bold">FORMAÇÃO</text>
    <rect x="0" y="360" width="180" height="1" fill="#333" />
    
    <text x="0" y="390" fill="#e0e0e0" font-size="13">🎓 MBA Data Science, IA e Analytics</text>
    <text x="20" y="410" fill="#888" font-size="12">USP (início: 10/2026)</text>
    <text x="0" y="440" fill="#e0e0e0" font-size="13">🎓 Pós-grad. Análise, Proj. e Ger. de Sist.</text>
    <text x="20" y="460" fill="#888" font-size="12">Anhanguera (concluída: 07/2026)</text>
    <text x="0" y="490" fill="#e0e0e0" font-size="13">🎓 Graduação Análise e Desenvolvimento</text>
    <text x="20" y="510" fill="#888" font-size="12">Unopar (2023 – 2025)</text>
    <text x="0" y="540" fill="#e0e0e0" font-size="13">🔧 Técnico em Mecatrônica</text>
    <text x="20" y="560" fill="#888" font-size="12">Colégio CEEP Castaldi (2016 – 2019)</text>

    <!-- Habilidades (Tags) -->
    <text x="0" y="600" fill="#00ffcc" font-size="15" font-weight="bold">COMPETÊNCIAS</text>
    <rect x="0" y="610" width="180" height="1" fill="#333" />
    
    <g transform="translate(0, 630)">
      <rect x="0" y="0" width="85" height="22" fill="#2a2a2a" rx="12" />
      <text x="42" y="15" fill="#00ffcc" font-size="11" text-anchor="middle">Meta Ads</text>
      
      <rect x="95" y="0" width="90" height="22" fill="#2a2a2a" rx="12" />
      <text x="140" y="15" fill="#00ffcc" font-size="11" text-anchor="middle">Google Ads</text>
      
      <rect x="195" y="0" width="65" height="22" fill="#2a2a2a" rx="12" />
      <text x="227" y="15" fill="#00ffcc" font-size="11" text-anchor="middle">UI/UX</text>
      
      <rect x="270" y="0" width="75" height="22" fill="#2a2a2a" rx="12" />
      <text x="307" y="15" fill="#00ffcc" font-size="11" text-anchor="middle">SQL/Python</text>
      
      <rect x="0" y="30" width="100" height="22" fill="#2a2a2a" rx="12" />
      <text x="50" y="45" fill="#00ffcc" font-size="11" text-anchor="middle">Premiere</text>
      
      <rect x="110" y="30" width="85" height="22" fill="#2a2a2a" rx="12" />
      <text x="152" y="45" fill="#00ffcc" font-size="11" text-anchor="middle">WordPress</text>
      
      <rect x="205" y="30" width="95" height="22" fill="#2a2a2a" rx="12" />
      <text x="252" y="45" fill="#00ffcc" font-size="11" text-anchor="middle">Direct Response</text>
    </g>

  </g>
</svg>
