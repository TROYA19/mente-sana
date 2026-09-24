<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirigiendo a tu Aplicación...</title>
    <!-- Redirección HTML automática en 2 segundos -->
    <meta http-equiv="refresh" content="2; url=https://aistudio.google.com/apps/ebc3140e-982d-4755-8f47-0f57a3dd2d27?showPreview=true">
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white min-h-screen flex items-center justify-center font-sans p-4">
    <div class="max-w-md w-full bg-gray-800 rounded-2xl shadow-2xl p-8 border border-gray-700 text-center">
        <!-- Ícono decorativo -->
        <div class="w-16 h-16 bg-blue-600/20 text-blue-400 rounded-full flex items-center justify-center mx-auto mb-4 animate-bounce">
            <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
            </svg>
        </div>

        <h1 class="text-2xl font-bold mb-2">Abriendo Aplicación</h1>
        <p class="text-gray-400 text-sm mb-6">
            Serás redirigido automáticamente a Google AI Studio en unos momentos...
        </p>
        
        <!-- Botón manual por si no redirige solo -->
        <a href="https://aistudio.google.com/apps/ebc3140e-982d-4755-8f47-0f57a3dd2d27?showPreview=true" 
           class="inline-block w-full py-3 px-6 bg-blue-600 hover:bg-blue-500 transition-colors text-white font-semibold rounded-xl shadow-lg hover:shadow-blue-500/25">
            Abrir Aplicación Ahora
        </a>

        <p class="text-xs text-gray-500 mt-6">
            Recuerda iniciar sesión en Google para poder acceder.
        </p>
    </div>

    <script>
        // Redirección por JavaScript como respaldo
        setTimeout(() => {
            window.location.href = "https://aistudio.google.com/apps/ebc3140e-982d-4755-8f47-0f57a3dd2d27?showPreview=true";
        }, 1500);
    </script>
</body>
</html>