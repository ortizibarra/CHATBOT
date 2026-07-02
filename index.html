<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beauty AI Assistant</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        .beauty-gradient { background: linear-gradient(135deg, #fdfcfb 0%, #e2d1c3 100%); }
        .glass-panel { background: rgba(255, 255, 255, 0.7); backdrop-filter: blur(15px); border: 1px solid rgba(255, 255, 255, 0.5); }
        .chat-scroll::-webkit-scrollbar { width: 6px; }
        .chat-scroll::-webkit-scrollbar-thumb { background: #d1b5a5; border-radius: 10px; }
    </style>
</head>
<body class="beauty-gradient min-h-screen font-sans text-stone-800 p-4 md:p-8">

    <div class="max-w-4xl mx-auto glass-panel rounded-3xl shadow-2xl overflow-hidden h-[85vh] flex flex-col">
        <!-- Header -->
        <header class="p-6 border-b border-stone-200 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <div class="bg-rose-200 p-2 rounded-full text-rose-600"><i data-lucide="sparkles"></i></div>
                <h1 class="text-2xl font-serif font-bold italic text-stone-700">Beauty Advisor AI</h1>
            </div>
            <span class="text-xs uppercase tracking-widest text-stone-500 font-semibold">Tu consultora personal</span>
        </header>

        <!-- Chat Area -->
        <div id="chat-messages" class="flex-1 overflow-y-auto p-6 space-y-6 chat-scroll">
            <div class="flex gap-4">
                <div class="w-8 h-8 rounded-full bg-rose-300 flex items-center justify-center text-white"><i data-lucide="bot" class="w-4 h-4"></i></div>
                <div class="bg-white p-4 rounded-2xl rounded-tl-none shadow-sm max-w-md">
                    ¡Hola! Soy tu asistente de belleza. Puedo recomendarte rutinas de skin care, tips de maquillaje profesional o ayudarte a elegir el labial perfecto para tu tono de piel. ¿Qué te gustaría descubrir hoy?
                </div>
            </div>
        </div>

        <!-- Input Area -->
        <div class="p-6 bg-white/50 border-t border-stone-200">
            <form id="chat-form" class="flex gap-3">
                <input type="text" id="chat-input" class="flex-1 bg-white border border-stone-300 rounded-full px-6 py-3 focus:ring-2 focus:ring-rose-300 outline-none transition" placeholder="Pregunta sobre maquillaje, piel o tendencias...">
                <button type="submit" class="bg-stone-800 text-white px-6 py-3 rounded-full hover:bg-stone-900 transition flex items-center gap-2">
                    <span class="hidden md:inline">Enviar</span> <i data-lucide="send" class="w-4 h-4"></i>
                </button>
            </form>
        </div>
    </div>

    <script>
        lucide.createIcons();

        const chatForm = document.getElementById('chat-form');
        const chatInput = document.getElementById('chat-input');
        const chatMessages = document.getElementById('chat-messages');

        function addMessage(text, isBot = true) {
            const div = document.createElement('div');
            div.className = `flex gap-4 ${!isBot ? 'flex-row-reverse' : ''}`;
            div.innerHTML = `
                <div class="w-8 h-8 rounded-full ${isBot ? 'bg-rose-300' : 'bg-stone-400'} flex items-center justify-center text-white shrink-0">
                    <i data-lucide="${isBot ? 'bot' : 'user'}" class="w-4 h-4"></i>
                </div>
                <div class="${isBot ? 'bg-white' : 'bg-rose-100'} p-4 rounded-2xl ${isBot ? 'rounded-tl-none' : 'rounded-tr-none'} shadow-sm max-w-md">
                    ${text}
                </div>
            `;
            chatMessages.appendChild(div);
            lucide.createIcons();
            chatMessages.scrollTop = chatMessages.scrollHeight;
        }

        chatForm.onsubmit = (e) => {
            e.preventDefault();
            const msg = chatInput.value.trim();
            if (!msg) return;

            addMessage(msg, false);
            chatInput.value = '';

            setTimeout(() => {
                let reply = "¡Qué excelente elección! Para ese estilo, te recomiendo enfocar el maquillaje en la luminosidad natural de la piel. ¿Deseas saber más sobre técnicas de difuminado o productos recomendados?";
                const lower = msg.toLowerCase();
                
                if (lower.includes('labial')) reply = "Los tonos terracota y nude rosado son tendencia esta temporada. Si tienes piel cálida, busca matices dorados; si es fría, opta por tonos azulados.";
                else if (lower.includes('piel') || lower.includes('skin')) reply = "La clave de una piel radiante es la hidratación profunda antes del maquillaje. Nunca olvides tu bloqueador solar y un buen suero con vitamina C.";
                else if (lower.includes('ojos')) reply = "El 'smokey eye' suave en tonos café es un clásico atemporal que ilumina la mirada. ¿Quieres que te explique paso a paso cómo aplicarlo?";

                addMessage(reply, true);
            }, 800);
        };
    </script>
</body>
</html>