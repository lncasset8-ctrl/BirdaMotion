# BirdaMotion
Birdsmotion series 1
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AuraSpace — Jurnal Kreatif Digital</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;700&family=Syne:wght@500;700;800&display=swap" rel="stylesheet">
</head>
<body>

    <header class="header">
        <div class="brand">AuraSpace<span>.</span></div>
        <div class="header-actions">
            <button id="theme-toggle" class="btn-icon" aria-label="Toggle Theme">
                <svg class="sun-icon" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="4"></circle><path d="M12 2v2"></path><path d="M12 20v2"></path><path d="m4.93 4.93 1.41 1.41"></path><path d="m17.66 17.66 1.41 1.41"></path><path d="M2 12h2"></path><path d="M20 12h2"></path><path d="m6.34 17.66-1.41 1.41"></path><path d="m19.07 4.93-1.41 1.41"></path></svg>
            </button>
        </div>
    </header>

    <main class="container">
        <section class="input-section">
            <h1 class="hero-title">Tuangkan <br>Isi Pikiranmu.</h1>
            <div class="card input-card">
                <textarea id="note-input" placeholder="Tuliskan ide, mood, atau kutipan hari ini..."></textarea>
                <div class="card-footer">
                    <div class="mood-selector">
                        <span class="mood-btn active" data-color="#ffb7b2">🌸 Elegan</span>
                        <span class="mood-btn" data-color="#b5ead7">🌿 Tenang</span>
                        <span class="mood-btn" data-color="#ffdac1">☀️ Hangat</span>
                        <span class="mood-btn" data-color="#c7ceea">🔮 Misterius</span>
                    </div>
                    <button id="add-btn" class="btn-primary">Simpan Cerita</button>
                </div>
            </div>
        </section>

        <section class="board-section">
            <div class="section-header">
                <h2>Ruang Memorimu</h2>
                <span class="counter" id="note-counter">0 Catatan</span>
            </div>
            <div class="notes-grid" id="notes-grid">
                </div>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>
