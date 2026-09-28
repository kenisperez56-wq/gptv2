<!DOCTYPE html>
<html>

<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>JSFiddle 7ng95ma0</title>

  <style>
    
  </style>

  
</head>
<body>
  <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GPTV2 - Asistente IA</title>
    <style>
        :root {
            --bg: #0f172a;
            --chat-bg: #1e293b;
            --accent: #3b82f6;
            --text: #f8fafc;
            --text-secondary: #94a3b8;
        }

        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .chat-container {
            width: 100%;
            max-width: 600px;
            height: 80vh;
            background: var(--chat-bg);
            border-radius: 12px;
            display: flex;
            flex-direction: column;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            border: 1px solid #334155;
            overflow: hidden;
        }

        .chat-header {
            padding: 1rem;
            background: #090d16;
            font-weight: bold;
            font-size: 1.1rem;
            text-align: center;
            border-bottom: 1px solid #334155;
            color: var(--accent);
        }

        .chat-messages {
            flex: 1;
            padding: 1rem;
            overflow-y: auto;
            display: flex;
            flex-direction: column;
            gap: 0.8rem;
        }

        .message {
            padding: 0.8rem 1rem;
            border-radius: 8px;
            max-width: 80%;
            line-height: 1.4;
            font-size: 0.95rem;
        }

        .message.user {
            background: var(--accent);
            color: white;
            align-self: flex-end;
        }

        .message.ai {
            background: #334155;
            color: var(--text);
            align-self: flex-start;
        }

        .chat-input-area {
            padding: 1rem;
            background: #090d16;
            display: flex;
            gap: 0.5rem;
            border-top: 1px solid #334155;
        }

        .chat-input-area input {
            flex: 1;
            padding: 0.75rem 1rem;
            background: var(--chat-bg);
            border: 1px solid #475569;
            border-radius: 6px;
            color: white;
            outline: none;
            font-size: 1rem;
        }

        .chat-input-area input:focus {
            border-color: var(--accent);
        }

        .chat-input-area button {
            background: var(--accent);
            color: white;
            border: none;
            padding: 0 1.2rem;
            border-radius: 6px;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.2s;
        }

        .chat-input-area button:hover {
            background: #2563eb;
        }
    </style>
</head>
<body>

    <div class="chat-container">
        <div class="chat-header">GPTV2 Assistant</div>
        <div class="chat-messages" id="chatMessages">
            <div class="message ai">¡Hola! Soy GPTV2. ¿En qué te puedo ayudar hoy?</div>
        </div>
        <div class="chat-input-area">
            <input type="text" id="userInput" placeholder="Escribe tu mensaje..." onkeypress="handleKeyPress(event)">
            <button onclick="sendMessage()">Enviar</button>
        </div>
    </div>

    <script>
        // 🔑 PEGA TU API KEY AQUÍ ENTRE LAS COMILLAS
        const API_KEY = "vck_1Ths6tPjLiAUThz5HEVmDI49DvNZwrcJ0ObqqjfWBNB8SOtopN1qIFKM"; 

        async function sendMessage() {
            const input = document.getElementById('userInput');
            const messagesContainer = document.getElementById('chatMessages');
            const text = input.value.trim();

            if (!text) return;
            if (API_KEY === "TU_API_KEY_AQUI") {
                alert("¡Recuerda colocar tu API Key real en el código!");
                return;
            }

            // Mostrar mensaje del usuario
            messagesContainer.innerHTML += `<div class="message user">${text}</div>`;
            input.value = '';
            messagesContainer.scrollTop = messagesContainer.scrollHeight;

            // Mostrar estado de carga temporal
            const loadingId = 'loading-' + Date.now();
            messagesContainer.innerHTML += `<div class="message ai" id="${loadingId}">Pensando...</div>`;
            messagesContainer.scrollTop = messagesContainer.scrollHeight;

            try {
                // Petición a la API (Ejemplo usando OpenAI / Vercel Gateway compatible)
                const response = await fetch('https://api.openai.com/v1/chat/completions', {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json',
                        'Authorization': `Bearer ${API_KEY}`
                    },
                    body: JSON.stringify({
                        model: "gpt-4o-mini",
                        messages: [{ role: "user", content: text }]
                    })
                });

                const data = await response.json();
                const reply = data.choices && data.choices[0] ? data.choices[0].message.content : "Error en la respuesta de la IA.";

                // Reemplazar "Pensando..." por la respuesta real
                document.getElementById(loadingId).remove();
                messagesContainer.innerHTML += `<div class="message ai">${reply}</div>`;

            } catch (error) {
                document.getElementById(loadingId).remove();
                messagesContainer.innerHTML += `<div class="message ai">Hubo un error de conexión.</div>`;
            }

            messagesContainer.scrollTop = messagesContainer.scrollHeight;
        }

        function handleKeyPress(e) {
            if (e.key === 'Enter') {
                sendMessage();
            }
        }
    </script>
</body>
</html>

  <script>
    
  </script>
</body>
</html>
