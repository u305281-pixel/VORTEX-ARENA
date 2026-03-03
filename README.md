# VORTEX-ARENA
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VORTEX ARENA</title>
    <style>
        /* TÜM TASARIM BURADA - DIŞ BAĞLANTI YOK, HATA VERMEZ */
        body { background: #050505; color: white; font-family: 'Segoe UI', sans-serif; margin: 0; padding: 0; display: flex; justify-content: center; min-height: 100vh; }
        .container { width: 100%; max-width: 450px; padding: 25px; box-sizing: border-box; }
        .header { text-align: center; margin-bottom: 40px; margin-top: 20px; }
        h1 { font-style: italic; letter-spacing: -2px; font-weight: 900; font-size: 35px; margin: 0; text-transform: uppercase; }
        .neon { color: #39FF14; text-shadow: 0 0 15px rgba(57, 255, 20, 0.5); }
        .slogan { font-size: 10px; color: #555; letter-spacing: 5px; text-transform: uppercase; margin-top: 5px; }
        
        /* Kart Tasarımları */
        .card { background: #111; border: 1px solid #222; border-radius: 15px; padding: 20px; margin-bottom: 15px; position: relative; overflow: hidden; }
        .card-label { font-size: 9px; color: #39FF14; font-weight: bold; text-transform: uppercase; margin-bottom: 15px; display: block; letter-spacing: 2px; }
        
        .match-box { display: flex; justify-content: space-between; align-items: center; text-align: center; }
        .team { flex: 1; }
        .team-name { font-size: 12px; font-weight: bold; margin-top: 8px; }
        .vs { font-size: 18px; font-weight: 900; font-style: italic; color: #333; }
        .date { text-align: center; font-size: 11px; color: #666; margin-top: 15px; border-top: 1px solid #1a1a1a; pt: 10px; padding-top: 10px; }

        .player { display: flex; align-items: center; background: #1a1a1a; padding: 12px; border-radius: 10px; margin-bottom: 10px; border-left: 3px solid #39FF14; }
        .p-info { margin-left: 15px; }
        .p-name { font-size: 13px; font-weight: bold; display: block; }
        .p-role { font-size: 9px; color: #555; text-transform: uppercase; }
        
        .btn { background: #39FF14; color: black; border: none; width: 100%; padding: 18px; border-radius: 12px; font-weight: 900; font-size: 13px; text-transform: uppercase; margin-top: 20px; letter-spacing: 1px; }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <h1>VORTEX <span class="neon">ARENA</span></h1>
            <div class="slogan">Agresif, fütüristik ve elit</div>
        </div>

        <div class="card">
            <span class="card-label">Sıradaki Turnuva Maçı</span>
            <div class="match-box">
                <div class="team">
                    <div style="font-size: 30px;">🐺</div>
                    <div class="team-name text-neon">VORTEX</div>
                </div>
                <div class="vs">VS</div>
                <div class="team">
                    <div style="font-size: 30px; opacity: 0.3;">❓</div>
                    <div class="team-name" style="color:#444">TBD</div>
                </div>
            </div>
            <div class="date">15 MART 2026 | SAAT 21:00</div>
        </div>

        <div style="margin-top: 30px; margin-bottom: 15px;">
            <span class="card-label" style="color: white; border-left: 2px solid #39FF14; padding-left: 10px;">Aktif Kadro</span>
        </div>

        <div class="player">
            <div style="font-size: 20px;">🥷</div>
            <div class="p-info">
                <span class="p-name">GHOST_WALKER</span>
                <span class="p-role">Entry Fragger</span>
            </div>
        </div>

        <div class="player" style="border-left-color: #444;">
            <div style="font-size: 20px;">🎯</div>
            <div class="p-info">
                <span class="p-name">REAPER_AWP</span>
                <span class="p-role">Sniper</span>
            </div>
        </div>

        <button class="btn">Takıma Katılmak İçin Başvur</button>
        
        <p style="text-align: center; font-size: 9px; color: #222; margin-top: 30px; letter-spacing: 2px;">VORTEX-ARENA OFFICIAL HUB</p>
    </div>

</body>
</html>

Agresif, fütüristik ve elit
