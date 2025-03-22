# hidayat351.github.io
<html>
<head>
    <title>Download Video TikTok Tanpa Watermark</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100">
    <header class="bg-blue-600 text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">TikTok Video Downloader</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#" class="hover:underline">Home</a></li>
                    <li><a href="#" class="hover:underline">About</a></li>
                    <li><a href="#" class="hover:underline">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container mx-auto mt-10 p-4">
        <div class="bg-white p-6 rounded-lg shadow-lg">
            <h2 class="text-2xl font-bold mb-4">Download Video TikTok Tanpa Watermark</h2>
            <form id="downloadForm" class="flex flex-col space-y-4">
                <input type="text" id="videoUrl" class="p-2 border border-gray-300 rounded" placeholder="Masukkan URL Video TikTok">
                <button type="submit" class="bg-blue-600 text-white p-2 rounded hover:bg-blue-700">Download</button>
            </form>
            <div id="result" class="mt-6 hidden">
                <h3 class="text-xl font-bold mb-2">Video Anda:</h3>
                <video id="videoPreview" controls class="w-full rounded-lg shadow-lg">
                    <source id="videoSource" src="" type="video/mp4">
                    Browser Anda tidak mendukung video tag.
                </video>
            </div>
        </div>
    </main>

    <footer class="bg-gray-800 text-white p-4 mt-10">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 TikTok Video Downloader. All rights reserved.</p>
        </div>
    </footer>

    <script>
        document.getElementById('downloadForm').addEventListener('submit', function(event) {
            event.preventDefault();
            const videoUrl = document.getElementById('videoUrl').value;
            if (videoUrl) {
                // Simulasi proses download video tanpa watermark
                const videoSource = document.getElementById('videoSource');
                videoSource.src = 'https://placehold.co/600x400?text=Video+TikTok+Tanpa+Watermark';
                document.getElementById('result').classList.remove('hidden');
                document.getElementById('videoPreview').load();
            }
        });
    </script>
</body>
</html>
