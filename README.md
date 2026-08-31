<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Examen de Inglés: Tiempos Verbales</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f6f9;
      color: #333;
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
    }
    h1, h2 {
      text-align: center;
      color: #2c3e50;
    }
    .instructions {
      background-color: #e8f4f8;
      border-left: 5px solid #3498db;
      padding: 10px 15px;
      margin-bottom: 25px;
      border-radius: 4px;
    }
    .section {
      background: #ffffff;
      padding: 20px;
      margin-bottom: 25px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .question {
      margin-bottom: 20px;
    }
    .question p {
      font-weight: bold;
      margin-bottom: 8px;
    }
    .options label {
      display: block;
      margin-bottom: 6px;
      cursor: pointer;
    }
    input[type="text"] {
      width: 100%;
      padding: 8px;
      box-sizing: border-box;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    select {
      padding: 6px;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
    .match-row {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 10px;
    }
    .match-row span {
      width: 45%;
    }
    button {
      display: block;
      width: 100%;
      padding: 12px;
      background-color: #27ae60;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 18px;
      cursor: pointer;
    }
    button:hover {
      background-color: #219150;
    }
    #results {
      margin-top: 20px;
      padding: 15px;
      background: #fff;
      border-radius: 8px;
      text-align: center;
      font-size: 20px;
      font-weight: bold;
      display: none;
    }
  </style>
</head>
<body>

  <h1>Examen de Inglés</h1>
  <div class="instructions">
    <p><strong>Temas evaluados:</strong> Present Simple, Past Simple, Future with <em>Will</em> & <em>Be Going to</em>.</p>
    <p>Responde todas las preguntas y presiona el botón "Enviar Examen" al final para ver tu calificación.</p>
  </div>

  <form id="quizForm">

    <div class="section">
      <h2>Parte 1: Opción Múltiple (A, B, C)</h2>

      <div class="question">
        <p>1. She _____ to the gym every Monday morning. (Present Simple)</p>
        <div class="options">
          <label><input type="radio" name="q1" value="A"> A) go</label>
          <label><input type="radio" name="q1" value="B"> B) goes</label>
          <label><input type="radio" name="q1" value="C"> C) is going</label>
        </div>
      </div>

      <div class="question">
        <p>2. They _____ a fantastic movie last night. (Past Simple)</p>
        <div class="options">
          <label><input type="radio" name="q2" value="A"> A) watched</label>
          <label><input type="radio" name="q2" value="B"> B) watch</label>
          <label><input type="radio" name="q2" value="C"> C) will watch</label>
        </div>
      </div>

      <div class="question">
        <p>3. Look at those dark clouds! It _____ rain soon. (Future - Evidence)</p>
        <div class="options">
          <label><input type="radio" name="q3" value="A"> A) will</label>
          <label><input type="radio" name="q3" value="B"> B) is going to</label>
          <label><input type="radio" name="q3" value="C"> C) went to</label>
        </div>
      </div>

      <div class="question">
        <p>4. I think people _____ live on Mars in the year 2100. (Future - Prediction)</p>
        <div class="options">
          <label><input type="radio" name="q4" value="A"> A) are going to</label>
          <label><input type="radio" name="q4" value="B"> B) will</label>
          <label><input type="radio" name="q4" value="C"> C) did</label>
        </div>
      </div>
    </div>

    <div class="section">
      <h2>Parte 2: Ordenar las Palabras</h2>
      <p>Escribe la oración ordenada correctamente (respeta las mayúsculas y puntos finales):</p>

      <div class="question">
        <p>5. Ordena: <em>always / breakfast / at / eats / He / 8 AM.</em></p>
        <input type="text" id="q5" placeholder="Escribe la oración completa aquí...">
      </div>

      <div class="question">
        <p>6. Ordena: <em>did / Where / go / yesterday / you / ?</em></p>
        <input type="text" id="q6" placeholder="Escribe la pregunta completa aquí...">
      </div>

      <div class="question">
        <p>7. Ordena: <em>are / visit / to / going / We / Rome / next summer.</em></p>
        <input type="text" id="q7" placeholder="Escribe la oración completa aquí...">
      </div>
    </div>

    <div class="section">
      <h2>Parte 3: Relacionar Columnas</h2>
      <p>Selecciona la terminación correcta para formar oraciones coherentes:</p>

      <div class="match-row">
        <span>8. If you drop the glass, it...</span>
        <select id="q8">
          <option value="">-- Selecciona --</option>
          <option value="A">bought a new car yesterday.</option>
          <option value="B">will break into pieces.</option>
          <option value="C">are going to study medicine next semester.</option>
        </select>
      </div>

      <div class="match-row">
        <span>9. My brother sold his old bike and...</span>
        <select id="q9">
          <option value="">-- Selecciona --</option>
          <option value="A">bought a new car yesterday.</option>
          <option value="B">will break into pieces.</option>
          <option value="C">are going to study medicine next semester.</option>
        </select>
      </div>

      <div class="match-row">
        <span>10. According to their plan, they...</span>
        <select id="q10">
          <option value="">-- Selecciona --</option>
          <option value="A">bought a new car yesterday.</option>
          <option value="B">will break into pieces.</option>
          <option value="C">are going to study medicine next semester.</option>
        </select>
      </div>
    </div>

    <div class="section">
      <h2>Parte 4: Organizar el Texto (Párrafo)</h2>
      <p>Asigna el número correcto (del 1 al 4) a cada frase para formar una historia cronológica y coherente:</p>

      <div class="question">
        <p>
          <select id="q11_1">
            <option value="">-</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
          </select>
          Yesterday, Sarah woke up early and packed her bags for vacation.
        </p>
        <p>
          <select id="q11_2">
            <option value="">-</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
          </select>
          Now, she usually spends her free time relaxing at the hotel pool.
        </p>
        <p>
          <select id="q11_3">
            <option value="">-</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
          </select>
          Tomorrow, she is going to explore the famous mountain trails.
        </p>
        <p>
          <select id="q11_4">
            <option value="">-</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
          </select>
          She hopes she will have an unforgettable experience before returning home.
        </p>
      </div>
    </div>

    <button type="button" onclick="evaluateQuiz()">Enviar Examen</button>
  </form>

  <div id="results"></div>

  <script>
    function evaluateQuiz() {
      let score = 0;
      let totalQuestions = 11;

      // Respuestas Parte 1
      const q1 = document.querySelector('input[name="q1"]:checked');
      if (q1 && q1.value === 'B') score++;

      const q2 = document.querySelector('input[name="q2"]:checked');
      if (q2 && q2.value === 'A') score++;

      const q3 = document.querySelector('input[name="q3"]:checked');
      if (q3 && q3.value === 'B') score++;

      const q4 = document.querySelector('input[name="q4"]:checked');
      if (q4 && q4.value === 'B') score++;

      // Respuestas Parte 2 (Normalizadas eliminando espacios extras)
      const q5 = document.getElementById('q5').value.trim().toLowerCase();
      if (q5 === 'he always eats breakfast at 8 am.' || q5 === 'he always eats breakfast at 8am.') score++;

      const q6 = document.getElementById('q6').value.trim().toLowerCase();
      if (q6 === 'where did you go yesterday?') score++;

      const q7 = document.getElementById('q7').value.trim().toLowerCase();
      if (q7 === 'we are going to visit rome next summer.') score++;

      // Respuestas Parte 3
      const q8 = document.getElementById('q8').value;
      if (q8 === 'B') score++;

      const q9 = document.getElementById('q9').value;
      if (q9 === 'A') score++;

      const q10 = document.getElementById('q10').value;
      if (q10 === 'C') score++;

      // Respuesta Parte 4 (Orden correcto: 1, 2, 3, 4)
      const p1 = document.getElementById('q11_1').value;
      const p2 = document.getElementById('q11_2').value;
      const p3 = document.getElementById('q11_3').value;
      const p4 = document.getElementById('q11_4').value;

      if (p1 === '1' && p2 === '2' && p3 === '3' && p4 === '4') score++;

      // Mostrar Resultados
      const resultsDiv = document.getElementById('results');
      resultsDiv.style.display = 'block';
      resultsDiv.innerHTML = `Tu puntaje es: ${score} de ${totalQuestions} (${((score/totalQuestions)*100).toFixed(1)}%)`;
      
      if (score === totalQuestions) {
        resultsDiv.style.color = '#27ae60';
        resultsDiv.innerHTML += "<br>¡Excelente trabajo! Has dominado los tiempos verbales.";
      } else {
        resultsDiv.style.color = '#e74c3c';
        resultsDiv.innerHTML += "<br>Sigue practicando para mejorar tu puntuación.";
      }
    }
  </script>
</body>
</html>
