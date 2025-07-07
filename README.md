‎<!DOCTYPE html>
‎<html lang="pt">
‎<head>
‎  <meta charset="UTF-8" />
‎  <meta name="viewport" content="width=device-width, initial-scale=1" />
‎  <title>English with Edy - Curso de Inglês</title>
‎
‎  <!-- Importando fontes do Google Fonts -->
‎  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&family=Patrick+Hand&display=swap" rel="stylesheet" />
‎
‎  <style>
‎    * {
‎      box-sizing: border-box;
‎      margin: 0;
‎      padding: 0;
‎    }
‎
‎    body {
‎      font-family: 'Patrick Hand', cursive; /* fonte manuscrita simples */
‎      background-color: #f5f6f8; /* branco / cinza muito claro */
‎      color: #444444; /* cinza escuro */
‎      line-height: 1.6;
‎    }
‎
‎    /* Menu */
‎    nav {
‎      background-color: #001f3f; /* azul marinho */
‎      padding: 15px 30px;
‎      display: flex;
‎      justify-content: space-between;
‎      align-items: center;
‎      flex-wrap: wrap;
‎    }
‎
‎    nav .logo {
‎      color: #ffffff; /* branco */
‎      font-family: 'Dancing Script', cursive; /* fonte manuscrita caligráfica */
‎      font-size: 28px;
‎      font-weight: 700;
‎      letter-spacing: 1px;
‎    }
‎
‎    nav ul {
‎      list-style: none;
‎      display: flex;
‎      gap: 20px;
‎    }
‎
‎    nav ul li a {
‎      color: #cccccc; /* cinza claro */
‎      text-decoration: none;
‎      font-weight: 600;
‎      transition: color 0.3s;
‎      font-family: 'Patrick Hand', cursive;
‎      font-size: 18px;
‎    }
‎
‎    nav ul li a:hover {
‎      color: #87ceeb; /* azul claro */
‎    }
‎
‎    header {
‎      background-color: #dbe9f4; /* azul muito claro */
‎      color: #001f3f; /* azul marinho */
‎      text-align: center;
‎      padding: 60px 20px;
‎      font-family: 'Patrick Hand', cursive;
‎    }
‎
‎    header h1 {
‎      font-size: 38px;
‎      margin-bottom: 10px;
‎      font-weight: 700;
‎    }
‎
‎    header p {
‎      font-size: 20px;
‎      opacity: 0.85;
‎      font-weight: 500;
‎    }
‎
‎    .course-image {
‎      max-width: 100%;
‎      border-radius: 12px;
‎      margin: 30px auto;
‎      display: block;
‎      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.15);
‎    }
‎
‎    section {
‎      padding: 45px 25px;
‎      max-width: 900px;
‎      margin: auto;
‎      background: #ffffff; /* branco */
‎      border-radius: 14px;
‎      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.08);
‎      margin-top: 30px;
‎      color: #001f3f; /* azul marinho */
‎      font-family: 'Patrick Hand', cursive;
‎      font-size: 18px;
‎    }
‎
‎    section h2 {
‎      color: #001f3f; /* azul marinho */
‎      margin-bottom: 18px;
‎      font-weight: 700;
‎      font-size: 26px;
‎    }
‎
‎    ul {
‎      margin-left: 24px;
‎      margin-bottom: 25px;
‎      line-height: 1.8;
‎    }
‎
‎    .btn {
‎      background-color: #001f3f; /* azul marinho */
‎      color: #ffffff; /* branco */
‎      padding: 14px 30px;
‎      border: none;
‎      border-radius: 8px;
‎      font-size: 20px;
‎      text-decoration: none;
‎      display: inline-block;
‎      margin-top: 25px;
‎      transition: background-color 0.3s, color 0.3s;
‎      font-weight: 700;
‎      cursor: pointer;
‎      box-shadow: 0 4px 10px rgba(0, 31, 63, 0.7);
‎      font-family: 'Dancing Script', cursive;
‎    }
‎
‎    .btn:hover {
‎      background-color: #87ceeb; /* azul claro */
‎      color: #001f3f;
‎      box-shadow: 0 6px 15px rgba(135, 206, 235, 0.9);
‎    }
‎
‎    footer {
‎      text-align: center;
‎      padding: 25px;
‎      background-color: #001f3f; /* azul marinho */
‎      color: #ffffff; /* branco */
‎      margin-top: 45px;
‎      font-weight: 600;
‎      font-family: 'Patrick Hand', cursive;
‎      font-size: 18px;
‎    }
‎
‎    @media (max-width: 600px) {
‎      nav ul {
‎        flex-direction: column;
‎        gap: 12px;
‎        margin-top: 12px;
‎      }
‎
‎      header h1 {
‎        font-size: 30px;
‎      }
‎
‎      header p, section, footer {
‎        font-size: 16px;
‎      }
‎    }
‎  </style>
‎</head>
‎<body>
‎
‎  <!-- Menu de Navegação -->
‎  <nav>
‎    <div class="logo">English with Edy</div>
‎    <ul>
‎      <li><a href="#">Início</a></li>
‎      <li><a href="#">Sobre</a></li>
‎      <li><a href="#">Conteúdo</a></li>
‎      <li><a href="#">Contato</a></li>
‎    </ul>
‎  </nav>
‎
‎  <!-- Cabeçalho -->
‎  <header>
‎    <h1>Curso de Inglês Online</h1>
‎    <p>Aprenda a falar inglês com confiança e fluência!</p>
‎  </header>
‎
‎  <!-- Imagem do Curso -->
‎  <img 
‎    src="https://images.unsplash.com/photo-1600195077075-44c7b4d21f2a?auto=format&fit=crop&w=1000&q=80"
‎    alt="Pessoa estudando inglês"
‎    class="course-image"
‎  >
‎
‎  <!-- Seção Principal -->
‎  <section>
‎    <h2>O que você vai aprender</h2>
‎    <ul>
‎      <li>Inglês para o dia a dia e trabalho</li>
‎      <li>Conversação prática com áudio e vídeo</li>
‎      <li>Gramática simples e direta</li>
‎      <li>Vocabulário moderno e útil</li>
‎    </ul>
‎
‎    <h2>Vantagens do curso</h2>
‎    <ul>
‎      <li>Aulas gravadas + materiais PDF</li>
‎      <li>Acesso vitalício e certificado</li>
‎      <li>Grupo de prática com professores</li>
‎      <li>Suporte via WhatsApp</li>
‎    </ul>
‎
‎    <a href="#" class="btn">Inscreva-se agora</a>
‎  </section>
‎
‎  <!-- Rodapé -->
‎  <footer>
‎    &copy; 2025 English with Edy. Todos os direitos reservados.
‎  </footer>
‎
‎</body>
‎</html>
‎
