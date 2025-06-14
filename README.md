<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Tecno Educ</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Tecno Educ</h1>
    <p>Aprende a utilizar ChatGPT, Canva y Zoom con recursos interactivos</p>
  </header>

  <nav>
    <ul>
      <li><a href="#chatgpt">ChatGPT</a></li>
      <li><a href="#canva">Canva</a></li>
      <li><a href="#zoom">Zoom</a></li>
      <li><a href="#quiz">Quiz</a></li>
    </ul>
  </nav>

  <main>
    <section id="chatgpt">
      <h2>¿Qué es ChatGPT?</h2>
      <p>ChatGPT es una herramienta de inteligencia artificial que puede ayudarte a escribir, aprender y crear contenido.</p>
      <a href="https://chat.openai.com" target="_blank" class="btn">Ir a ChatGPT</a>
    </section>

    <section id="canva">
      <h2>¿Qué es Canva?</h2>
      <p>Canva es una plataforma de diseño gráfico muy intuitiva que te permite crear presentaciones, infografías y más.</p>
      <a href="https://www.canva.com" target="_blank" class="btn">Ir a Canva</a>
    </section>

    <section id="zoom">
      <h2>¿Qué es Zoom?</h2>
      <p>Zoom es una aplicación de videoconferencias ideal para clases en línea, reuniones y webinars.</p>
      <a href="https://zoom.us" target="_blank" class="btn">Ir a Zoom</a>
    </section>

    <section id="quiz">
      <h2>Quiz: ¿Qué tanto aprendiste?</h2>
      <form id="quizForm">
        <div class="quiz-item">
          <p>1. ¿Qué herramienta usarías para diseñar una presentación?</p>
          <label><input type="radio" name="q1" value="Canva"> Canva</label><br>
          <label><input type="radio" name="q1" value="Zoom"> Zoom</label><br>
          <label><input type="radio" name="q1" value="ChatGPT"> ChatGPT</label>
        </div>
        <div class="quiz-item">
          <p>2. ¿Cuál herramienta sirve para hablar por videollamada?</p>
          <label><input type="radio" name="q2" value="ChatGPT"> ChatGPT</label><br>
          <label><input type="radio" name="q2" value="Canva"> Canva</label><br>
          <label><input type="radio" name="q2" value="Zoom"> Zoom</label>
        </div>
        <div class="quiz-item">
          <p>3. ¿Cuál herramienta puede ayudarte a redactar textos?</p>
          <label><input type="radio" name="q3" value="ChatGPT"> ChatGPT</label><br>
          <label><input type="radio" name="q3" value="Zoom"> Zoom</label><br>
          <label><input type="radio" name="q3" value="Canva"> Canva</label>
        </div>
        <button type="submit" class="btn">Enviar respuestas</button>
      </form>
      <div id="result"></div>
    </section>
  </main>

  <footer>
    <p>© 2025 Tecno Educ. Proyecto educativo en GitHub.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
