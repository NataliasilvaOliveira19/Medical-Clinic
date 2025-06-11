<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Clínica Vida - Início</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    * {
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      margin: 0;
      background: linear-gradient(to right, #f4f6f8, #e0f0ff);
      background-image: url('https://cdn.prod.website-files.com/66351b9f531bf70f210e21e5/66351b9f531bf70f210e277a_medico-com-um-estetoscopio-nas-maos-e-fundo-do-hospital-scaled.webp');
      background-repeat: no-repeat;
      background-size: cover;
      background-position: center;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    header {
      background-color: white;
      padding: 10px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    header img {
      height: 50px;
    }

    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #2f80ed;
      font-weight: 600;
    }

    nav a:hover {
      color: #1d62cc;
    }

    .container {
      flex: 1;
      padding: 60px 20px;
      text-align: center;
    }

    h1 {
      color: #2f80ed;
      margin-bottom: 20px;
    }

    p {
      color: #333;
      font-size: 18px;
      max-width: 600px;
      margin: 0 auto 40px;
    }

    .grid-content {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      max-width: 900px;
      margin: 0 auto;
    }

    .extra-content {
      background-color: rgba(255, 255, 255, 0.9);
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
      text-align: left;
    }

    .extra-content h2 {
      margin-top: 0;
      color: #2f80ed;
      font-size: 20px;
    }

    .extra-content ul {
      list-style: none;
      padding: 0;
      margin-top: 10px;
    }

    .extra-content ul li {
      margin-bottom: 8px;
    }

    .extra-content blockquote {
      font-style: italic;
      color: #444;
      margin: 0;
    }

    footer {
      background-color: #f1f1f1;
      padding: 15px;
      text-align: center;
      font-size: 14px;
      color: #555;
    }
  </style>
</head>

<body>
  <header>
    <img
      src="https://img.freepik.com/vetores-gratis/hospital-logo-design-vector-medical-cross_53876-136743.jpg?semt=ais_hybrid&w=740"
      alt="Logo Clínica Vida">
    <nav>
      <a href="paginainicial.html">Início</a>
      <a href="paciente.html">Cadastro Paciente</a>
      <a href="medico.html">Cadastro Médico</a>
      <a href="login.html">Login</a>
    </nav>
  </header>

  <div class="container">
    <h1>Bem-vindo à Clínica Vida</h1>
    <p><strong>Sua saúde em primeiro lugar. Faça seu cadastro, consulte um médico e acompanhe seus atendimentos com praticidade.</strong></p>

    <div class="grid-content">
      <!-- Bloco 1 -->
      <div class="extra-content">
        <h2>Atendimento Humanizado</h2>
        <p>Nossa equipe médica oferece cuidado com empatia e escuta atenta em todas as consultas.</p>
      </div>

      <!-- Bloco 2 -->
      <div class="extra-content">
        <h2>Diferenciais</h2>
        <ul>
          <li>✅ Especialistas experientes</li>
          <li>✅ Agendamento rápido</li>
          <li>✅ Resultados online</li>
          <li>✅ Estrutura moderna</li>
        </ul>
      </div>

      <!-- Bloco 3 -->
      <div class="extra-content">
        <h2>Compromisso com a Saúde</h2>
        <p>Trabalhamos com foco na prevenção, diagnóstico rápido e acompanhamento contínuo do seu bem-estar.</p>
      </div>

      <!-- Bloco 4 -->
      <div class="extra-content">
        <h2>Mensagem da Clínica</h2>
        <blockquote>“A saúde é o bem mais precioso. Confie em quem cuida de você com responsabilidade e carinho.”</blockquote>
      </div>
    </div>
  </div>

  <footer>
    © 2025 Clínica Vida. Todos os direitos reservados.
  </footer>
</body>

</html>
