
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- SEO -->
    <title>SMART4GREEN 2026 | I Seminario Multidisciplinario de Innovación para el Desarrollo Sostenible</title>
    <meta name="description" content="SMART4GREEN 2026: 14 ponencias online el 16 y 17 de noviembre y feria presencial de emprendimientos el 17 de noviembre de 09h00 a 13h00. Organiza ESPOCH Sede Morona Santiago.">
    <meta name="keywords" content="SMART4GREEN 2026, desarrollo sostenible, inteligencia artificial, IoT, Amazonía, investigación científica, innovación tecnológica, emprendimiento, sostenibilidad, ESPOCH, Morona Santiago">
    <meta name="author" content="ESPOCH Sede Morona Santiago">
    <meta name="robots" content="index, follow">
    <meta name="theme-color" content="#0E3B2E">
    <link rel="canonical" href="https://smart4green.espoch.edu.ec/">

    <!-- Open Graph -->
    <meta property="og:type" content="website">
    <meta property="og:locale" content="es_EC">
    <meta property="og:url" content="https://smart4green.espoch.edu.ec/">
    <meta property="og:title" content="SMART4GREEN 2026 | I Seminario Multidisciplinario de Innovación para el Desarrollo Sostenible">
    <meta property="og:description" content="16 y 17 de noviembre de 2026. Seminario online y feria presencial de emprendimientos de 09h00 a 13h00.">
    <meta property="og:image" content="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80">

    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="SMART4GREEN 2026 | I Seminario Multidisciplinario">
    <meta name="twitter:description" content="Seminario online el 16 y 17 de noviembre de 2026; feria presencial de 09h00 a 13h00.">
    <meta name="twitter:image" content="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80">

    <link rel="icon" href="https://www.espoch.edu.ec/favicon.ico" type="image/x-icon">

    <!-- Datos estructurados del evento (mejoran la presencia en Google) -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Event",
      "name": "SMART4GREEN 2026 – I Seminario Multidisciplinario de Innovación para el Desarrollo Sostenible",
      "startDate": "2026-11-16T08:00:00-05:00",
      "endDate": "2026-11-17T17:00:00-05:00",
      "eventAttendanceMode": "https://schema.org/MixedEventAttendanceMode",
      "eventStatus": "https://schema.org/EventScheduled",
      "location": [
        { "@type": "VirtualLocation", "url": "https://smart4green.espoch.edu.ec/" },
        { "@type": "Place", "name": "ESPOCH Sede Morona Santiago", "address": { "@type": "PostalAddress", "addressLocality": "Macas", "addressRegion": "Morona Santiago", "addressCountry": "EC" } }
      ],
      "organizer": { "@type": "Organization", "name": "Escuela Superior Politécnica de Chimborazo – Sede Morona Santiago", "url": "https://sedemacas.espoch.edu.ec/" },
      "description": "Seminario online con 14 ponencias en siete ejes temáticos y feria presencial de emprendimientos."
    }
    </script>

    <!-- Fuentes -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@500;600;700;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">

    <!-- Bootstrap 5.3 + Font Awesome 6 -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

    <style>
        :root {
            --forest-900: #0B2E24;
            --forest-800: #0E3B2E;
            --forest-700: #14523F;
            --forest-600: #1B6B50;
            --leaf-500: #2E9E6B;
            --leaf-100: #E6F4EC;
            --ocean-700: #0F4C81;
            --ocean-100: #E7F0F8;
            --gold-500: #D9A441;
            --ink-900: #111827;
            --ink-700: #374151;
            --ink-500: #6B7280;
            --line: #E5E7EB;
            --surface: #FFFFFF;
            --surface-alt: #F6F8F7;
            --radius: 14px;
            --shadow-sm: 0 1px 2px rgba(17, 24, 39, .06), 0 1px 3px rgba(17, 24, 39, .04);
            --shadow-md: 0 10px 30px rgba(11, 46, 36, .08);
            --ease: cubic-bezier(.4, 0, .2, 1);
            --nav-h: 72px;
        }

        html { scroll-behavior: smooth; scroll-padding-top: calc(var(--nav-h) + 12px); }
        body {
            font-family: 'Inter', system-ui, sans-serif;
            color: var(--ink-700);
            background: var(--surface);
            font-size: 1rem;
            line-height: 1.65;
            overflow-x: hidden;
        }
        h1, h2, h3, h4, h5, h6, .brand { font-family: 'Plus Jakarta Sans', sans-serif; color: var(--ink-900); letter-spacing: -.01em; }
        a { color: var(--ocean-700); }
        :focus-visible { outline: 3px solid var(--gold-500); outline-offset: 2px; }

        .skip-link { position: absolute; left: -999px; top: 8px; background: #fff; padding: 8px 14px; border-radius: 8px; z-index: 2000; }
        .skip-link:focus { left: 8px; }

        /* ---------- Barra superior ---------- */
        .top-bar { background: var(--forest-900); color: rgba(255,255,255,.85); font-size: .82rem; padding: 7px 0; }
        .top-bar a { color: rgba(255,255,255,.85); text-decoration: none; }
        .top-bar a:hover { color: #fff; }

        /* ---------- Navegación ---------- */
        .site-nav {
            background: rgba(255,255,255,.92);
            backdrop-filter: saturate(180%) blur(12px);
            border-bottom: 1px solid transparent;
            min-height: var(--nav-h);
            transition: border-color .3s var(--ease), box-shadow .3s var(--ease);
        }
        .site-nav.scrolled { border-color: var(--line); box-shadow: var(--shadow-sm); }
        .brand { font-weight: 800; font-size: 1.35rem; color: var(--forest-700); text-decoration: none; line-height: 1; }
        .brand span { color: var(--ocean-700); }
        .brand small { display: block; font-family: 'Inter', sans-serif; font-size: .68rem; font-weight: 600; letter-spacing: .12em; text-transform: uppercase; color: var(--ink-500); margin-top: 4px; }
        .site-nav .nav-link { font-weight: 500; font-size: .92rem; color: var(--ink-700); padding: .5rem .75rem !important; border-radius: 8px; }
        .site-nav .nav-link:hover { color: var(--forest-700); background: var(--leaf-100); }
        .site-nav .nav-link.active { color: var(--forest-700); font-weight: 600; }

        /* ---------- Botones ---------- */
        .btn-brand {
            background: var(--forest-700); color: #fff; border: 0;
            font-weight: 600; padding: .8rem 1.5rem; border-radius: 10px;
            transition: background .2s var(--ease), transform .2s var(--ease);
        }
        .btn-brand:hover { background: var(--forest-800); color: #fff; transform: translateY(-1px); }
        .btn-gold { background: var(--gold-500); color: var(--forest-900); border: 0; font-weight: 700; padding: .8rem 1.5rem; border-radius: 10px; }
        .btn-gold:hover { background: #C8922F; color: var(--forest-900); }
        .btn-ghost { border: 1.5px solid rgba(255,255,255,.55); color: #fff; font-weight: 600; padding: .75rem 1.4rem; border-radius: 10px; }
        .btn-ghost:hover { background: #fff; color: var(--forest-800); border-color: #fff; }
        .btn-outline-brand { border: 1.5px solid var(--forest-700); color: var(--forest-700); font-weight: 600; border-radius: 10px; padding: .6rem 1.2rem; }
        .btn-outline-brand:hover { background: var(--forest-700); color: #fff; }

        /* ---------- Hero ---------- */
        .hero {
            position: relative;
            color: #fff;
            padding: 96px 0 88px;
            background:
                radial-gradient(1200px 500px at 85% -10%, rgba(46,158,107,.35), transparent 60%),
                linear-gradient(160deg, rgba(11,46,36,.94) 0%, rgba(14,59,46,.90) 45%, rgba(15,76,129,.88) 100%),
                url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1920&q=70') center/cover no-repeat;
            overflow: hidden;
        }
        .hero::after {
            content: ''; position: absolute; inset: auto 0 0 0; height: 1px;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,.25), transparent);
        }
        .eyebrow {
            display: inline-flex; align-items: center; gap: .5rem;
            font-size: .78rem; font-weight: 600; letter-spacing: .14em; text-transform: uppercase;
            color: #BFE8D2; background: rgba(255,255,255,.08); border: 1px solid rgba(255,255,255,.18);
            padding: .45rem .9rem; border-radius: 999px;
        }
        .hero h1 { color: #fff; font-size: clamp(2.4rem, 5.5vw, 4.2rem); font-weight: 800; line-height: 1.05; margin: 1.25rem 0 1rem; }
        .hero h1 .accent { color: #8FE0B5; }
        .hero .lead { color: rgba(255,255,255,.88); font-size: clamp(1.05rem, 1.6vw, 1.25rem); max-width: 40rem; }
        .hero .axes { color: rgba(255,255,255,.7); font-size: .9rem; letter-spacing: .04em; }

        .hero-card {
            background: rgba(255,255,255,.07);
            border: 1px solid rgba(255,255,255,.16);
            backdrop-filter: blur(10px);
            border-radius: 18px;
            padding: 1.75rem;
        }
        .hero-card dt { font-size: .72rem; text-transform: uppercase; letter-spacing: .12em; color: rgba(255,255,255,.6); font-weight: 600; }
        .hero-card dd { color: #fff; font-weight: 500; margin-bottom: 1rem; }
        .hero-card dd:last-of-type { margin-bottom: 0; }
        .hero-card .icon { width: 36px; height: 36px; border-radius: 10px; background: rgba(143,224,181,.15); color: #8FE0B5; display: inline-flex; align-items: center; justify-content: center; flex-shrink: 0; }

        .countdown { display: grid; grid-template-columns: repeat(4, 1fr); gap: .6rem; }
        .countdown div { background: rgba(0,0,0,.18); border-radius: 12px; padding: .7rem .3rem; text-align: center; }
        .countdown strong { display: block; font-family: 'Plus Jakarta Sans', sans-serif; font-size: 1.6rem; font-weight: 800; color: #fff; line-height: 1.1; font-variant-numeric: tabular-nums; }
        .countdown span { font-size: .68rem; text-transform: uppercase; letter-spacing: .1em; color: rgba(255,255,255,.65); }

        /* ---------- Franja de datos clave ---------- */
        .facts { background: var(--surface); border-bottom: 1px solid var(--line); }
        .fact { display: flex; align-items: center; gap: .85rem; padding: 1.4rem 0; }
        .fact i { width: 44px; height: 44px; border-radius: 12px; display: inline-flex; align-items: center; justify-content: center; background: var(--leaf-100); color: var(--forest-700); font-size: 1.1rem; flex-shrink: 0; }
        .fact strong { display: block; color: var(--ink-900); font-weight: 600; font-size: .95rem; line-height: 1.3; }
        .fact small { color: var(--ink-500); }

        /* ---------- Secciones ---------- */
        section { position: relative; }
        .section { padding: 96px 0; }
        .section-alt { background: var(--surface-alt); }
        .kicker { display: inline-block; font-size: .78rem; font-weight: 700; letter-spacing: .14em; text-transform: uppercase; color: var(--leaf-500); margin-bottom: .75rem; }
        .section-title { font-size: clamp(1.75rem, 3vw, 2.4rem); font-weight: 800; line-height: 1.2; margin-bottom: 1rem; }
        .section-intro { color: var(--ink-500); font-size: 1.05rem; max-width: 44rem; }
        .section-head { margin-bottom: 3rem; }
        .section-head.center { text-align: center; }
        .section-head.center .section-intro { margin-inline: auto; }

        /* ---------- Acerca ---------- */
        .project-item { display: flex; gap: 1rem; padding: 1.1rem 1.25rem; border: 1px solid var(--line); border-radius: var(--radius); background: var(--surface); }
        .project-item i { color: var(--forest-700); font-size: 1.2rem; margin-top: .2rem; }
        .project-item h3 { font-size: .95rem; font-weight: 700; margin-bottom: .2rem; }
        .project-item p { font-size: .9rem; color: var(--ink-500); margin: 0; }
        .audience { display: grid; grid-template-columns: repeat(2, 1fr); gap: 1rem; }
        .audience div { background: var(--surface); border: 1px solid var(--line); border-radius: var(--radius); padding: 1.4rem 1.2rem; }
        .audience i { color: var(--ocean-700); font-size: 1.4rem; margin-bottom: .75rem; display: block; }
        .audience strong { color: var(--ink-900); font-weight: 600; font-size: .95rem; }

        /* ---------- Ejes ---------- */
        .axis-card {
            height: 100%; background: var(--surface); border: 1px solid var(--line); border-radius: var(--radius);
            padding: 1.75rem; transition: border-color .25s var(--ease), box-shadow .25s var(--ease), transform .25s var(--ease);
        }
        .axis-card:hover { border-color: rgba(27,107,80,.35); box-shadow: var(--shadow-md); transform: translateY(-3px); }
        .axis-num { font-family: 'Plus Jakarta Sans', sans-serif; font-weight: 800; font-size: .8rem; color: var(--leaf-500); letter-spacing: .1em; }
        .axis-icon { width: 52px; height: 52px; border-radius: 14px; background: var(--leaf-100); color: var(--forest-700); display: inline-flex; align-items: center; justify-content: center; font-size: 1.35rem; }
        .axis-card h3 { font-size: 1.1rem; font-weight: 700; margin: 1.1rem 0 .5rem; }
        .axis-card p { font-size: .92rem; color: var(--ink-500); margin: 0; }
        .axis-card.featured { background: linear-gradient(135deg, var(--forest-800), var(--ocean-700)); border: 0; color: #fff; }
        .axis-card.featured h3 { color: #fff; }
        .axis-card.featured p { color: rgba(255,255,255,.8); }
        .axis-card.featured .axis-icon { background: rgba(255,255,255,.12); color: #8FE0B5; }
        .axis-card.featured .axis-num { color: #8FE0B5; }

        /* ---------- Conferencistas ---------- */
        .speaker { height: 100%; background: var(--surface); border: 1px solid var(--line); border-radius: 18px; overflow: hidden; transition: box-shadow .25s var(--ease); }
        .speaker:hover { box-shadow: var(--shadow-md); }
        .speaker-photo { aspect-ratio: 4 / 3.4; background: linear-gradient(160deg, var(--leaf-100), var(--ocean-100)); position: relative; display: flex; align-items: center; justify-content: center; overflow: hidden; }
        .speaker-photo img { width: 100%; height: 100%; object-fit: cover; object-position: center top; }
        .speaker-photo .placeholder { font-size: 4rem; color: rgba(20,82,63,.35); }
        .speaker-country { position: absolute; left: 14px; bottom: 14px; background: rgba(255,255,255,.95); color: var(--ink-900); font-size: .78rem; font-weight: 600; padding: .3rem .7rem; border-radius: 999px; box-shadow: var(--shadow-sm); }
        .speaker-body { padding: 1.5rem; }
        .speaker-body h3 { font-size: 1.15rem; font-weight: 700; margin-bottom: .25rem; }
        .speaker-body .affil { color: var(--ocean-700); font-weight: 500; font-size: .92rem; margin-bottom: 1rem; }
        .speaker-body .meta { font-size: .88rem; color: var(--ink-500); border-top: 1px solid var(--line); padding-top: 1rem; margin: 0; }
        .speaker-country .flag { width: 20px; height: 15px; object-fit: cover; border-radius: 2px; margin-right: 6px; vertical-align: -2px; box-shadow: 0 0 0 1px rgba(17,24,39,.08); }
        .agenda-row .talk { display: block; font-size: .88rem; font-style: italic; color: var(--forest-700); margin-top: .15rem; }
        .agenda-row .talk.pending { color: var(--ink-500); }
        .agenda-row .tbc .flag { width: 16px; height: 12px; object-fit: cover; border-radius: 2px; margin-right: 4px; vertical-align: -1px; }
        .badge-soft { background: var(--leaf-100); color: var(--forest-700); font-weight: 600; font-size: .72rem; padding: .35rem .65rem; border-radius: 999px; }

        /* ---------- Carrusel de conferencistas (clases exclusivas spk-*) ---------- */
        .spk-carousel {
            --spk-gap: 1.5rem;
            position: relative;
            display: grid;
            grid-template-columns: auto auto auto 1fr;
            grid-template-areas: "track track track track" "prev status next .";
            column-gap: .75rem;
            align-items: center;
            row-gap: .75rem;
        }
        .spk-track {
            grid-area: track;
            display: flex;
            gap: var(--spk-gap);
            overflow-x: auto;
            overscroll-behavior-x: contain;
            scroll-snap-type: x mandatory;
            scroll-behavior: smooth;
            -webkit-overflow-scrolling: touch;
            scrollbar-width: none;
            padding: 6px 2px 28px;
            border-radius: 18px;
        }
        .spk-track::-webkit-scrollbar { display: none; }
        .spk-track:focus-visible { outline: 3px solid var(--gold-500); outline-offset: 4px; }
        .spk-slide {
            flex: 0 0 85%;
            scroll-snap-align: start;
            display: flex;
        }
        .spk-slide > .speaker { width: 100%; }
        .spk-nav {
            width: 44px; height: 44px;
            border-radius: 50%;
            border: 1px solid var(--line);
            background: var(--surface);
            color: var(--forest-700);
            box-shadow: var(--shadow-md);
            display: inline-flex; align-items: center; justify-content: center;
            transition: background .2s var(--ease), color .2s var(--ease), opacity .2s var(--ease), transform .2s var(--ease);
            z-index: 2;
        }
        .spk-nav:hover:not(:disabled) { background: var(--forest-700); color: #fff; transform: scale(1.05); }
        .spk-nav:disabled { opacity: .35; cursor: default; box-shadow: none; }
        .spk-prev { grid-area: prev; }
        .spk-next { grid-area: next; }
        .spk-status { grid-area: status; text-align: center; margin: 0; font-size: .88rem; font-weight: 500; color: var(--ink-500); font-variant-numeric: tabular-nums; }

        @media (min-width: 768px) {
            .spk-slide { flex-basis: calc((100% - var(--spk-gap)) / 2); }
        }
        @media (min-width: 992px) {
            .spk-slide { flex-basis: calc((100% - 2 * var(--spk-gap)) / 3); }
        }
        @media (min-width: 1200px) {
            .spk-carousel { grid-template-columns: 1fr auto 1fr; grid-template-areas: "track track track" ". status ."; }
            .spk-nav { position: absolute; grid-area: auto; top: calc(50% - 40px); transform: translateY(-50%); }
            .spk-nav:hover:not(:disabled) { transform: translateY(-50%) scale(1.05); }
            .spk-prev { left: -22px; }
            .spk-next { right: -22px; }
        }
        @media (prefers-reduced-motion: reduce) {
            .spk-track { scroll-behavior: auto; }
            .spk-nav, .spk-nav:hover:not(:disabled) { transition: none; }
        }

        /* ---------- Fechas ---------- */
        .day-card { height: 100%; background: var(--surface); border: 1px solid var(--line); border-radius: 18px; padding: 2rem; }
        .day-date { display: flex; align-items: center; gap: 1rem; margin-bottom: 1.5rem; }
        .day-date .cal { width: 64px; text-align: center; border-radius: 12px; overflow: hidden; border: 1px solid var(--line); flex-shrink: 0; }
        .day-date .cal span { display: block; background: var(--forest-700); color: #fff; font-size: .68rem; font-weight: 700; letter-spacing: .1em; padding: .2rem 0; }
        .day-date .cal strong { display: block; font-family: 'Plus Jakarta Sans', sans-serif; font-size: 1.6rem; font-weight: 800; color: var(--ink-900); padding: .25rem 0; }
        .day-date h3 { font-size: 1.15rem; font-weight: 700; margin: 0; }
        .day-date small { color: var(--ink-500); }
        .slot { display: flex; gap: .9rem; padding: .9rem 0; border-top: 1px dashed var(--line); }
        .slot:first-of-type { border-top: 0; }
        .slot .mode { font-size: .7rem; font-weight: 700; text-transform: uppercase; letter-spacing: .08em; padding: .25rem .55rem; border-radius: 6px; height: fit-content; white-space: nowrap; }
        .mode-online { background: var(--ocean-100); color: var(--ocean-700); }
        .mode-onsite { background: #FBF1DE; color: #8A5D12; }
        .slot strong { color: var(--ink-900); font-weight: 600; display: block; }
        .slot p { margin: 0; color: var(--ink-500); font-size: .9rem; }

        /* ---------- Feria ---------- */
        .fair { background: linear-gradient(160deg, var(--forest-900), var(--forest-700)); color: #fff; border-radius: 24px; overflow: hidden; }
        .fair h2, .fair h3 { color: #fff; }
        .fair .kicker { color: #8FE0B5; }
        .fair p, .fair li { color: rgba(255,255,255,.82); }
        .fair-info { display: flex; flex-wrap: wrap; gap: .6rem; margin: 1.5rem 0; }
        .fair-info span { background: rgba(255,255,255,.1); border: 1px solid rgba(255,255,255,.15); font-size: .85rem; padding: .4rem .8rem; border-radius: 999px; }
        .fair-areas { display: flex; flex-wrap: wrap; gap: .5rem; padding: 0; list-style: none; }
        .fair-areas li { background: rgba(143,224,181,.12); color: #CFF1DE; font-size: .85rem; padding: .35rem .75rem; border-radius: 8px; }
        .fair-panel { background: var(--surface); color: var(--ink-700); border-radius: 18px; padding: 2rem; height: 100%; }
        .fair-panel h3 { color: var(--ink-900); font-size: 1.25rem; font-weight: 700; }
        .fair-panel p { color: var(--ink-500); }
        .step { display: flex; gap: .9rem; margin-bottom: 1.1rem; }
        .step-n { width: 30px; height: 30px; border-radius: 50%; background: var(--leaf-100); color: var(--forest-700); font-weight: 700; font-size: .85rem; display: inline-flex; align-items: center; justify-content: center; flex-shrink: 0; }
        .step p { margin: 0; color: var(--ink-700); font-size: .93rem; }

        /* ---------- Programa ---------- */
        .program-tabs { display: inline-flex; gap: .4rem; background: var(--surface-alt); border: 1px solid var(--line); border-radius: 12px; padding: .35rem; }
        .program-tabs .nav-link { color: var(--ink-700); font-weight: 600; font-size: .92rem; border-radius: 9px; padding: .6rem 1.2rem; }
        .program-tabs .nav-link.active { background: var(--forest-700); color: #fff; }
        .agenda { border: 1px solid var(--line); border-radius: 16px; overflow: hidden; background: var(--surface); }
        .agenda-row { display: grid; grid-template-columns: 150px 1fr; gap: 1rem; padding: 1rem 1.5rem; border-top: 1px solid var(--line); align-items: center; }
        .agenda-row:first-child { border-top: 0; }
        .agenda-row time { font-variant-numeric: tabular-nums; font-weight: 600; color: var(--forest-700); font-size: .92rem; }
        .agenda-row strong { color: var(--ink-900); font-weight: 600; }
        .agenda-row .tbc { display: block; font-size: .85rem; color: var(--ink-500); }
        .agenda-row.break { background: var(--surface-alt); }
        .agenda-row.break strong { color: var(--ink-500); font-weight: 500; }
        .agenda-row.break time { color: var(--ink-500); }
        .agenda-row.key strong { color: var(--forest-700); }
        .agenda-axis { padding: 1rem 1.5rem; background: var(--leaf-100); border-top: 1px solid var(--line); border-left: 4px solid var(--forest-600); }
        .agenda-axis h4 { font-size: .82rem; font-weight: 800; letter-spacing: .08em; text-transform: uppercase; color: var(--forest-700); margin: 0 0 .15rem; }
        .agenda-axis p { font-size: .87rem; color: var(--ink-700); margin: 0; }
        .fair-info .fair-deadline { background: var(--gold-500); border-color: var(--gold-500); color: var(--forest-900); font-weight: 700; }
        .fair-deadline-note { display: flex; gap: .6rem; align-items: flex-start; background: #FBF1DE; color: #8A5D12; border-radius: 10px; padding: .75rem 1rem; font-size: .9rem; margin-bottom: 1.25rem; }
        .fair-deadline-note i { margin-top: .2rem; }
        .stream-panel { max-width: 920px; margin: 0 auto 2rem; background: var(--surface); border: 1px solid var(--line); border-left: 4px solid var(--ocean-700); border-radius: 16px; padding: 1.25rem 1.5rem; display: flex; flex-wrap: wrap; align-items: center; gap: 1rem 1.5rem; box-shadow: var(--shadow-sm); }
        .stream-icon { width: 48px; height: 48px; border-radius: 12px; background: var(--ocean-100); color: var(--ocean-700); display: inline-flex; align-items: center; justify-content: center; font-size: 1.3rem; flex-shrink: 0; }
        .stream-info { flex: 1 1 260px; min-width: 0; }
        .stream-info strong { display: block; color: var(--ink-900); font-weight: 700; }
        .stream-info a { word-break: break-all; font-weight: 600; text-decoration: none; }
        .stream-info a:hover { text-decoration: underline; }
        .stream-info small { display: block; color: var(--ink-500); }
        .stream-actions { display: flex; flex-wrap: wrap; gap: .5rem; }
        .stream-actions .btn { padding: .65rem 1.2rem; }
        .stream-actions .is-pending { opacity: .55; pointer-events: none; }
        @media (max-width: 575.98px) { .stream-actions, .stream-actions .btn { width: 100%; } }

        /* ---------- Cifras ---------- */
        .stats { background: var(--forest-900); color: #fff; padding: 72px 0; }
        .stat-number { font-family: 'Plus Jakarta Sans', sans-serif; font-size: clamp(2.4rem, 4vw, 3.2rem); font-weight: 800; color: #8FE0B5; line-height: 1; }
        .stat-label { color: rgba(255,255,255,.75); font-size: .95rem; margin-top: .5rem; }

        /* ---------- Organizadores ---------- */
        .group-title { font-size: .8rem; font-weight: 700; letter-spacing: .14em; text-transform: uppercase; color: var(--ink-500); text-align: center; margin: 3.5rem 0 1.5rem; display: flex; align-items: center; gap: 1rem; }
        .group-title::before, .group-title::after { content: ''; flex: 1; height: 1px; background: var(--line); }
        .partner { height: 100%; background: var(--surface); border: 1px solid var(--line); border-radius: var(--radius); padding: 1.5rem; text-align: center; transition: box-shadow .25s var(--ease), border-color .25s var(--ease); }
        a.partner-link { text-decoration: none; color: inherit; display: block; height: 100%; }
        a.partner-link:hover .partner { box-shadow: var(--shadow-md); border-color: rgba(27,107,80,.3); transform: translateY(-3px); }
        .partner { transition: box-shadow .25s var(--ease), border-color .25s var(--ease), transform .25s var(--ease); }
        .partner .visit { display: inline-block; margin-top: .9rem; font-size: .82rem; font-weight: 600; color: var(--forest-700); }
        a.partner-link:hover .visit { text-decoration: underline; }
        .partner-link.no-url { pointer-events: none; cursor: default; }
        .partner-link.no-url .visit { display: none; }
        .partner-logo { height: 96px; display: flex; align-items: center; justify-content: center; margin-bottom: 1rem; }
        .partner-logo img { max-width: 80%; max-height: 84px; object-fit: contain; }
        .partner-logo i { font-size: 2.2rem; color: var(--forest-600); }
        .partner h3 { font-size: 1rem; font-weight: 700; margin-bottom: .3rem; }
        .partner p { font-size: .87rem; color: var(--ink-500); margin: 0; }
        .partner.sponsor .partner-logo { height: 72px; margin-bottom: .6rem; }
        .partner.sponsor h3 { font-size: .9rem; font-weight: 600; color: var(--ink-700); margin: 0; }

        /* ---------- Contacto ---------- */
        .contact-item { display: flex; gap: 1rem; align-items: flex-start; padding: 1.1rem 0; border-top: 1px solid var(--line); }
        .contact-item:first-of-type { border-top: 0; }
        .contact-item i { width: 42px; height: 42px; border-radius: 12px; background: var(--leaf-100); color: var(--forest-700); display: inline-flex; align-items: center; justify-content: center; flex-shrink: 0; }
        .contact-item strong { color: var(--ink-900); display: block; font-weight: 600; }
        .contact-item a { text-decoration: none; word-break: break-word; }
        .contact-item a:hover { text-decoration: underline; }
        .cta-panel { background: linear-gradient(160deg, var(--forest-800), var(--ocean-700)); color: #fff; border-radius: 20px; padding: 2.5rem; height: 100%; }
        .cta-panel h3 { color: #fff; font-weight: 800; }
        .cta-panel p { color: rgba(255,255,255,.82); }

        /* ---------- Footer ---------- */
        footer { background: var(--forest-900); color: rgba(255,255,255,.7); font-size: .92rem; }
        footer h4 { color: #fff; font-size: .82rem; letter-spacing: .12em; text-transform: uppercase; font-weight: 700; margin-bottom: 1rem; }
        footer a { color: rgba(255,255,255,.7); text-decoration: none; }
        footer a:hover { color: #fff; }
        footer ul { list-style: none; padding: 0; margin: 0; }
        footer li { margin-bottom: .45rem; }
        .footer-bottom { border-top: 1px solid rgba(255,255,255,.1); font-size: .82rem; color: rgba(255,255,255,.5); }

        /* ---------- Flotantes ---------- */
        .whatsapp-float { position: fixed; right: 24px; bottom: 24px; width: 56px; height: 56px; border-radius: 50%; background: #25D366; color: #fff; display: flex; align-items: center; justify-content: center; font-size: 1.7rem; box-shadow: 0 8px 24px rgba(0,0,0,.2); z-index: 1000; text-decoration: none; transition: transform .2s var(--ease); }
        .whatsapp-float:hover { color: #fff; transform: scale(1.06); }
        .back-to-top { position: fixed; right: 30px; bottom: 92px; width: 44px; height: 44px; border-radius: 50%; background: var(--surface); color: var(--forest-700); border: 1px solid var(--line); box-shadow: var(--shadow-md); display: flex; align-items: center; justify-content: center; text-decoration: none; opacity: 0; visibility: hidden; transition: opacity .25s, visibility .25s; z-index: 999; }
        .back-to-top.show { opacity: 1; visibility: visible; }

        /* ---------- Animación de entrada (se desactiva si el usuario lo prefiere) ---------- */
        .reveal { opacity: 0; transform: translateY(16px); transition: opacity .7s var(--ease), transform .7s var(--ease); }
        .reveal.in { opacity: 1; transform: none; }
        .no-js .reveal { opacity: 1; transform: none; }
        @media (prefers-reduced-motion: reduce) {
            html { scroll-behavior: auto; }
            .reveal { opacity: 1; transform: none; transition: none; }
        }

        @media (max-width: 991.98px) {
            .site-nav .navbar-collapse { padding: 1rem 0; }
            .hero { padding: 64px 0 64px; }
            .section { padding: 72px 0; }
        }
        @media (max-width: 575.98px) {
            .agenda-row { grid-template-columns: 1fr; gap: .2rem; padding: .9rem 1rem; }
            .agenda-axis { padding: .9rem 1rem; }
            .audience { grid-template-columns: 1fr 1fr; }
            .countdown strong { font-size: 1.3rem; }
            .fair-panel, .day-card, .cta-panel { padding: 1.5rem; }
            .back-to-top { right: 30px; }
        }
    </style>
</head>
<body class="no-js">
<a class="skip-link" href="#contenido">Saltar al contenido</a>

<!-- BARRA SUPERIOR -->
<div class="top-bar">
    <div class="container d-flex justify-content-between align-items-center gap-3">
        <div><i class="fa-solid fa-graduation-cap me-2" aria-hidden="true"></i>ESPOCH Sede Morona Santiago</div>
        <div class="d-none d-md-flex gap-4">
            <a href="https://sedemacas.espoch.edu.ec/" target="_blank" rel="noopener"><i class="fa-solid fa-globe me-1" aria-hidden="true"></i>sedemacas.espoch.edu.ec</a>
            <a href="https://www.facebook.com/espochms?locale=es_LA" target="_blank" rel="noopener" aria-label="Facebook ESPOCH Sede Morona Santiago"><i class="fa-brands fa-facebook-f" aria-hidden="true"></i></a>
        </div>
    </div>
</div>

<!-- NAVEGACIÓN -->
<nav class="navbar navbar-expand-lg sticky-top site-nav" id="siteNav" aria-label="Navegación principal">
    <div class="container">
        <a class="brand" href="#inicio">SMART<span>4GREEN</span><small>2026 · ESPOCH</small></a>
        <button class="navbar-toggler border-0" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu" aria-controls="navMenu" aria-expanded="false" aria-label="Abrir menú">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navMenu">
            <ul class="navbar-nav ms-auto align-items-lg-center gap-lg-1">
                <li class="nav-item"><a class="nav-link" href="#acerca">Acerca</a></li>
                <li class="nav-item"><a class="nav-link" href="#ejes">Ejes</a></li>
                <li class="nav-item"><a class="nav-link" href="#speakers">Conferencistas</a></li>
                <li class="nav-item"><a class="nav-link" href="#fechas">Fechas</a></li>
                <li class="nav-item"><a class="nav-link" href="#emprendimiento">Feria</a></li>
                <li class="nav-item"><a class="nav-link" href="#programa">Programa</a></li>
                <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
                <li class="nav-item ms-lg-3 mt-2 mt-lg-0">
                    <a href="#emprendimiento" class="btn btn-brand py-2 px-3">Feria de emprendimientos</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<main id="contenido">

<!-- HERO -->
<header id="inicio" class="hero">
    <div class="container">
        <div class="row align-items-center g-5">
            <div class="col-lg-7">
                <span class="eyebrow"><i class="fa-solid fa-leaf" aria-hidden="true"></i>I Edición · 16 y 17 de noviembre de 2026</span>
                <h1>SMART<span class="accent">4GREEN</span> 2026</h1>
                <p class="lead mb-3">I Seminario Multidisciplinario de Innovación para el Desarrollo Sostenible</p>
                <p class="axes mb-4">Tecnología · Producción · Economía · Sociedad · Ambiente</p>
                <div class="d-flex flex-wrap gap-3">
                    <a href="https://forms.gle/oieuCepQ93R2p2tTA" target="_blank" rel="noopener noreferrer" class="btn btn-gold btn-lg">
                        Inscripción general <i class="fa-solid fa-arrow-right ms-2" aria-hidden="true"></i>
                    </a>
                    <a href="#programa" class="btn btn-ghost btn-lg">Ver programa</a>
                </div>
            </div>
            <div class="col-lg-5">
                <div class="hero-card">
                    <dl class="mb-4">
                        <div class="d-flex gap-3 mb-3">
                            <span class="icon"><i class="fa-solid fa-video" aria-hidden="true"></i></span>
                            <div><dt>Seminario online</dt><dd>16 y 17 de noviembre · 14 ponencias</dd></div>
                        </div>
                        <div class="d-flex gap-3 mb-3">
                            <span class="icon"><i class="fa-solid fa-store" aria-hidden="true"></i></span>
                            <div><dt>Feria presencial</dt><dd>Martes 17 · 09h00–13h00 · Lugar por confirmar</dd></div>
                        </div>
                        <div class="d-flex gap-3">
                            <span class="icon"><i class="fa-solid fa-location-dot" aria-hidden="true"></i></span>
                            <div><dt>Organiza</dt><dd>ESPOCH Sede Morona Santiago · Macas</dd></div>
                        </div>
                    </dl>
                    <p class="small text-uppercase fw-semibold mb-2" style="letter-spacing:.12em;color:rgba(255,255,255,.6)" id="countdownLabel">Faltan</p>
                    <div class="countdown" id="countdown" aria-live="polite">
                        <div><strong id="days">00</strong><span>Días</span></div>
                        <div><strong id="hours">00</strong><span>Horas</span></div>
                        <div><strong id="minutes">00</strong><span>Min</span></div>
                        <div><strong id="seconds">00</strong><span>Seg</span></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</header>

<!-- DATOS CLAVE -->
<section class="facts" aria-label="Datos clave">
    <div class="container">
        <div class="row">
            <div class="col-6 col-lg-3"><div class="fact"><i class="fa-regular fa-calendar" aria-hidden="true"></i><div><strong>16–17 nov. 2026</strong><small>Dos jornadas</small></div></div></div>
            <div class="col-6 col-lg-3"><div class="fact"><i class="fa-solid fa-laptop" aria-hidden="true"></i><div><strong>Modalidad híbrida</strong><small>Online + feria presencial</small></div></div></div>
            <div class="col-6 col-lg-3"><div class="fact"><i class="fa-solid fa-microchip" aria-hidden="true"></i><div><strong>IA e IoT</strong><small>Aplicados a la sostenibilidad</small></div></div></div>
            <div class="col-6 col-lg-3"><div class="fact"><i class="fa-solid fa-people-arrows" aria-hidden="true"></i><div><strong>Networking académico</strong><small>Investigación y empresa</small></div></div></div>
        </div>
    </div>
</section>

<!-- ACERCA -->
<section id="acerca" class="section">
    <div class="container">
        <div class="row g-5 align-items-start">
            <div class="col-lg-6 reveal">
                <span class="kicker">Sobre el evento</span>
                <h2 class="section-title">Investigación científica al servicio de la sostenibilidad amazónica</h2>
                <p>
                    <strong>SMART4GREEN 2026</strong> es un espacio multidisciplinario e internacional que articula la investigación académica con el desarrollo sostenible, en diálogo entre el contexto global y la realidad regional amazónica.
                </p>
                <p>
                    A lo largo de dos jornadas, investigadores, docentes, estudiantes, profesionales y emprendedores comparten avances, experiencias y propuestas en tecnología, ambiente, producción, economía y sociedad, con el propósito de generar soluciones innovadoras para el territorio.
                </p>
                <div class="project-item mt-4">
                    <i class="fa-solid fa-building-columns" aria-hidden="true"></i>
                    <div>
                        <h3>Organiza</h3>
                        <p>Escuela Superior Politécnica de Chimborazo (ESPOCH) · Sede Morona Santiago</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 reveal">
                <div class="p-4 p-md-5 rounded-4 section-alt">
                    <span class="kicker">Dirigido a</span>
                    <h3 class="h4 fw-bold mb-4">Público objetivo</h3>
                    <div class="audience">
                        <div><i class="fa-solid fa-user-graduate" aria-hidden="true"></i><strong>Investigadores y docentes</strong></div>
                        <div><i class="fa-solid fa-book-open-reader" aria-hidden="true"></i><strong>Estudiantes</strong></div>
                        <div><i class="fa-solid fa-briefcase" aria-hidden="true"></i><strong>Profesionales y empresas</strong></div>
                        <div><i class="fa-solid fa-building-columns" aria-hidden="true"></i><strong>Instituciones públicas y privadas</strong></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- EJES TEMÁTICOS -->
<section id="ejes" class="section section-alt">
    <div class="container">
        <div class="section-head center reveal">
            <span class="kicker">Áreas de investigación</span>
            <h2 class="section-title">Siete ejes temáticos</h2>
            <p class="section-intro">Las ponencias se organizan en siete líneas que conectan tecnología, territorio, economía y sociedad.</p>
        </div>
        <div class="row g-4">
            <div class="col-md-6 col-lg-4 reveal"><article class="axis-card">
                <div class="d-flex justify-content-between align-items-start"><span class="axis-icon"><i class="fa-solid fa-robot" aria-hidden="true"></i></span><span class="axis-num">EJE 01</span></div>
                <h3>Tecnología, IA y digitalización</h3>
                <p>Inteligencia artificial, Internet de las Cosas, transformación digital y Big Data aplicados al desarrollo.</p>
            </article></div>
            <div class="col-md-6 col-lg-4 reveal"><article class="axis-card">
                <div class="d-flex justify-content-between align-items-start"><span class="axis-icon"><i class="fa-solid fa-leaf" aria-hidden="true"></i></span><span class="axis-num">EJE 02</span></div>
                <h3>Ambiente y sostenibilidad</h3>
                <p>Monitoreo ambiental, conservación de la biodiversidad, cambio climático y resiliencia ecológica.</p>
            </article></div>
            <div class="col-md-6 col-lg-4 reveal"><article class="axis-card">
                <div class="d-flex justify-content-between align-items-start"><span class="axis-icon"><i class="fa-solid fa-gem" aria-hidden="true"></i></span><span class="axis-num">EJE 03</span></div>
                <h3>Recursos naturales y territorio</h3>
                <p>Minería responsable, gestión territorial sostenible y preservación de cuencas hidrográficas.</p>
            </article></div>
            <div class="col-md-6 col-lg-4 reveal"><article class="axis-card">
                <div class="d-flex justify-content-between align-items-start"><span class="axis-icon"><i class="fa-solid fa-wheat-awn" aria-hidden="true"></i></span><span class="axis-num">EJE 04</span></div>
                <h3>Producción y zootecnia</h3>
                <p>Agropecuaria de precisión y sistemas agroforestales sostenibles.</p>
            </article></div>
            <div class="col-md-6 col-lg-4 reveal"><article class="axis-card">
                <div class="d-flex justify-content-between align-items-start"><span class="axis-icon"><i class="fa-solid fa-chart-line" aria-hidden="true"></i></span><span class="axis-num">EJE 05</span></div>
                <h3>Economía y negocios sostenibles</h3>
                <p>Economía circular, contabilidad, finanzas verdes y modelos de negocio sustentables.</p>
            </article></div>
            <div class="col-md-6 col-lg-4 reveal"><article class="axis-card">
                <div class="d-flex justify-content-between align-items-start"><span class="axis-icon"><i class="fa-solid fa-scale-balanced" aria-hidden="true"></i></span><span class="axis-num">EJE 06</span></div>
                <h3>Derecho, sociedad y gobernanza</h3>
                <p>Políticas públicas, bioética, gobernanza territorial y legislación ambiental.</p>
            </article></div>
            <div class="col-12 reveal"><article class="axis-card featured">
                <div class="row align-items-center g-4">
                    <div class="col-md-8">
                        <div class="d-flex align-items-center gap-3"><span class="axis-icon"><i class="fa-solid fa-rocket" aria-hidden="true"></i></span><span class="axis-num">EJE 07</span></div>
                        <h3>Innovación y emprendimiento </h3>
                        <p>Jornada de actualización empresarial para graduados.</p>
                    </div>
                    <div class="col-md-4 text-md-end">
                        <a href="#emprendimiento" class="btn btn-gold">Conoce la feria <i class="fa-solid fa-arrow-right ms-2" aria-hidden="true"></i></a>
                    </div>
                </div>
            </article></div>
        </div>
    </div>
</section>

<!-- CONFERENCISTAS -->
<section id="speakers" class="section">
    <div class="container">
        <div class="section-head center reveal">
            <span class="kicker">Keynote speakers</span>
            <h2 class="section-title">Conferencistas invitados</h2>
            <p class="section-intro">La asignación de horarios y temas se confirmará en el programa académico.</p>
        </div>

        <!-- CARRUSEL DE PONENTES (14 tarjetas). Para completar un ponente, reemplace el contenido
             de su tarjeta con la misma estructura de la tarjeta 1 (foto en assets/, país, nombre, afiliación y especialidad). -->
        <div class="spk-carousel reveal" id="spkCarousel">
            <button type="button" class="spk-nav spk-prev" id="spkPrev" aria-controls="spkTrack" aria-label="Ponentes anteriores">
                <i class="fa-solid fa-chevron-left" aria-hidden="true"></i>
            </button>

            <div class="spk-track" id="spkTrack" tabindex="0" role="region" aria-roledescription="carrusel" aria-label="Conferencistas invitados. Use las flechas izquierda y derecha del teclado para desplazarse.">
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 1 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/ponente1.PNG" alt="Dr. Raúl Antonio Aguilar" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/mx.png" srcset="https://flagcdn.com/w80/mx.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">México</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Dr. Raúl Antonio Aguilar</h3>
                            <p class="affil">Universidad Autónoma de Yucatán</p>
                            <p class="meta"><strong>Especialidad:</strong> Ingeniería de Software e Informática Educativa.</p>
                        </div>
                    </article>
                </div>

                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 2 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/ponente2.jpg" alt="Dr. Oscar Zapata" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/ca.png" srcset="https://flagcdn.com/w80/ca.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Canadá</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Dr. Oscar Zapata </h3>
                            <p class="affil">University of Saskatchewan</p>
                            <p class="meta"><strong>Especialidad:</strong> Socio-economic impacts of energy development.</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 3 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/ponente.jpg" alt="Dr. Theofilos Toulkeridis " loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/gr.png" srcset="https://flagcdn.com/w80/gr.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Grecia</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Dr. Theofilos Toulkeridis </h3>
                            <p class="affil">Aristotle University of Thessaloniki</p>
                            <p class="meta"><strong>Especialidad:</strong> Geodinámica, Geología estructural, Volcanología, Tsunamis, Gestión de Riesgos, Geo-Arqueología, Espeleología.</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 4 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/omar.jpg" alt="Dra. Susan Ivonne Muñoz" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/cl.png" srcset="https://flagcdn.com/w80/cl.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Chile</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Dr. Susan Ivonne Muñoz</h3>
                            <p class="affil">Agencia de Sustentabilidad y Cambio Climático</p>
                            <p class="meta"><strong>Especialidad:</strong> Sustentabilidad y Cambio Climático.</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 5 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/omar.jpg" alt="Dr. Joel Morales Salas" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/cu.png" srcset="https://flagcdn.com/w80/cu.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Cuba</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Dr. Joel Morales Salas </h3>
                            <p class="affil">Universidad Tecnológica de La Habana</p>
                            <p class="meta"><strong>Especialidad:</strong> energías renovables, la eficiencia energética y la integración de fuentes limpias a la red eléctrica nacional.</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 6 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/omar.jpg" alt="Dr. Yoelkis Alexis Laborde" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/cu.png" srcset="https://flagcdn.com/w80/cu.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Cuba</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Dr. Yoelkis Alexis Laborde</h3>
                            <p class="affil">Centro de Aplicaciones Tecnológicas para el Desarrollo Sostenible CATEDES</p>
                            <p class="meta"><strong>Especialidad:</strong> ...</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 7 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/omar.jpg" alt="Ing. Wilson Zambrano" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/co.png" srcset="https://flagcdn.com/w80/co.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Colombia</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Ing. Wilson Zambrano</h3>
                            <p class="affil">Institución Universitaria Antonio José Camacho</p>
                            <p class="meta"><strong>Especialidad:</strong> ...</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 8 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/omar.jpg" alt="Dr. Ramiro Ávila Santamaría" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Ecuador</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Dr. Ramiro Ávila Santamaría </h3>
                            <p class="affil">Universidad Andina Simón Bolívar</p>
                            <p class="meta"><strong>Especialidad:</strong> ...</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 9 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/omar.jpg" alt="Ing. Carlos Samaniego Tello" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Ecuador</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Ing. Carlos Samaniego Tello</h3>
                            <p class="affil">Analista Zonal de Fortalecimiento de Actores de la EPS</p>
                            <p class="meta"><strong>Especialidad:</strong> ...</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 10 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/ponente10.jpg" alt="Ing. Víctor José Huilca" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Ecuador</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Ing. Víctor José Huilca</h3>
                            <p class="affil">ESPOCH, Sede Morona Santiago, Ecuador</p>
                            <p class="meta"><strong>Especialidad:</strong> Ingeniería Electrónica y Automatización.</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 11 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/ponente10.jfif" alt="Ing. Víctor José Huilca" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Ecuador</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Ing. Luis Arias</h3>
                            <p class="affil">ESPOCH, Sede Morona Santiago, Ecuador</p>
                            <p class="meta"><strong>Especialidad:</strong> Zootecnia.</p>
                        </div>
                    </article>
                </div>

                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 12 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/omar.jpg" alt="Ing. Edwin Lozada" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Ecuador</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Ing. Edwin Lozada</h3>
                            <p class="affil">Docente ESPOCH, Sede Morona Santiago, Ecuador</p>
                            <p class="meta"><strong>Especialidad:</strong> Zootecnia.</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 13 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/omar.jpg" alt="Ing. Jairo Andrés Becerra" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Ecuador</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Ing. Jairo Andrés Becerra</h3>
                            <p class="affil">Lowell Mineral Exploration</p>
                            <p class="meta"><strong>Especialidad:</strong> Liderazgo Empresarial.</p>
                        </div>
                    </article>
                </div>
                <div class="spk-slide" role="group" aria-roledescription="diapositiva" aria-label="Ponente 1 de 14">
                    <!-- PONENTE 14 -->
                    <article class="speaker">
                        <div class="speaker-photo">
                            <img src="assets/omar.jpg" alt="Ing. Danilo Tayupanda" loading="lazy" onerror="this.replaceWith(Object.assign(document.createElement('i'),{className:'fa-solid fa-user placeholder'}))">
                            <span class="speaker-country"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Ecuador</span>
                        </div>
                        <div class="speaker-body">
                            <h3>Ing. Danilo Tayupanda </h3>
                            <p class="affil">Fundación Atasim.</p>
                            <p class="meta"><strong>Especialidad:</strong> Emprendimiento.</p>
                        </div>
                    </article>
                </div>
            </div>

            <button type="button" class="spk-nav spk-next" id="spkNext" aria-controls="spkTrack" aria-label="Ponentes siguientes">
                <i class="fa-solid fa-chevron-right" aria-hidden="true"></i>
            </button>

            <p class="spk-status" id="spkStatus" aria-live="polite">Ponentes 1–3 de 14</p>
        </div>
    </div>
</section>

<!-- FECHAS -->
<section id="fechas" class="section section-alt">
    <div class="container">
        <div class="section-head center reveal">
            <span class="kicker">Calendario</span>
            <h2 class="section-title">Dos jornadas de intercambio académico</h2>
        </div>
        <div class="row g-4">
            <div class="col-md-6 reveal">
                <div class="day-card">
                    <div class="day-date">
                        <div class="cal"><span>NOV</span><strong>16</strong></div>
                        <div><h3>Lunes 16 de noviembre</h3><small>Jornada 1</small></div>
                    </div>
                    <div class="slot"><span class="mode mode-online">Online</span><div><strong>08h00 – 12h00 y 14h00 – 18h00</strong><p>Registro, inauguración y ponencias de los ejes 1 al 6.</p></div></div>
                </div>
            </div>
            <div class="col-md-6 reveal">
                <div class="day-card">
                    <div class="day-date">
                        <div class="cal"><span>NOV</span><strong>17</strong></div>
                        <div><h3>Martes 17 de noviembre</h3><small>Jornada 2</small></div>
                    </div>
                    <div class="slot"><span class="mode mode-onsite">Presencial</span><div><strong>09h00 – 13h00</strong><p>Feria de Emprendimientos · Lugar por confirmar.</p></div></div>
                    <div class="slot"><span class="mode mode-online">Online</span><div><strong>15h00 – 17h00</strong><p>Ponencias del eje 7, conclusiones y clausura.</p></div></div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- FERIA DE EMPRENDIMIENTOS -->
<section id="emprendimiento" class="section">
    <div class="container">
        <div class="fair p-4 p-md-5 reveal">
            <div class="row g-5 align-items-stretch">
                <div class="col-lg-6">
                    <span class="kicker">I Feria de Emprendimientos SMART4GREEN 2026</span>
                    <h2 class="section-title">Convierte una idea en una solución para el futuro</h2>
                    <p>Un espacio para presentar ideas de negocio, proyectos innovadores y soluciones con potencial de impacto, vinculadas con la sostenibilidad, la tecnología, la producción, la economía, la sociedad y el ambiente.</p>
                    <div class="fair-info">
                        <span class="fair-deadline"><i class="fa-solid fa-hourglass-half me-1" aria-hidden="true"></i>Fecha límite de propuestas: 9 de noviembre 2026</span>
                        <span><i class="fa-regular fa-calendar me-1" aria-hidden="true"></i>17 de noviembre</span>
                        <span><i class="fa-regular fa-clock me-1" aria-hidden="true"></i>09h00–13h00</span>
                        <span><i class="fa-solid fa-location-dot me-1" aria-hidden="true"></i>Presencial · lugar por confirmar</span>
                        <span><i class="fa-solid fa-users me-1" aria-hidden="true"></i>Equipos de hasta 4 integrantes</span>
                    </div>
                    <h3 class="h6 fw-bold text-uppercase mb-3" style="letter-spacing:.1em">Áreas de participación</h3>
                    <ul class="fair-areas">
                        <li>Sostenibilidad y ambiente</li>
                        <li>Tecnología e innovación</li>
                        <li>Producción y agroindustria</li>
                        <li>Minería sostenible</li>
                        <li>Economía y negocios</li>
                        <li>Innovación social y jurídica</li>
                    </ul>
                    <p class="small mt-3 mb-0">Pueden participar estudiantes, docentes, investigadores y emprendedores.</p>
                </div>
                <div class="col-lg-6">
                    <div class="fair-panel">
                        <span class="badge-soft d-inline-block mb-3" id="fairStatus"><i class="fa-solid fa-circle me-1" style="font-size:.5rem;vertical-align:middle" aria-hidden="true"></i>Inscripciones abiertas</span>
                        <p class="fair-deadline-note"><i class="fa-regular fa-calendar-check" aria-hidden="true"></i><span>Recepción de propuestas hasta el <strong>lunes 9 de noviembre de 2026</strong>.</span></p>
                        <h3 class="mb-3">¿Cómo participar?</h3>
                        <div class="step"><span class="step-n">1</span><p>Descarga el formato obligatorio y redacta tu propuesta ejecutiva.</p></div>
                        <div class="step"><span class="step-n">2</span><p>Guárdala en PDF.</p></div>
                        <div class="step"><span class="step-n">3</span><p>Completa el formulario de inscripción y adjunta el PDF. Google puede pedirte iniciar sesión para subir el archivo.</p></div>
                        <div class="d-flex flex-wrap gap-2 mt-4">
                            <a href="https://forms.gle/fv8FkEfTR3pD16yw5" target="_blank" rel="noopener noreferrer" class="btn btn-brand">
                                Inscribirme en la feria <i class="fa-solid fa-arrow-up-right-from-square ms-2" aria-hidden="true"></i>
                            </a>
                            <a href="Documentos/Plantilla_Feria_Emprendimientos_SMART4GREEN_2026.docx" class="btn btn-outline-brand" download>
                                <i class="fa-solid fa-file-word me-2" aria-hidden="true"></i>Descargar formato
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- PROGRAMA -->
<section id="programa" class="section section-alt">
    <div class="container">
        <div class="section-head center reveal">
            <span class="kicker">16 y 17 de noviembre · Hora de Ecuador (UTC−5)</span>
            <h2 class="section-title">Programa de ponencias</h2>
            <p class="section-intro">14 ponencias de 30 minutos en modalidad online, organizadas en siete ejes temáticos. Los títulos marcados como «por confirmar» se actualizarán próximamente.</p>
        </div>

        <!-- ACCESO A LA TRANSMISIÓN Y DESCARGA DE LA AGENDA
             Pegue el enlace de Google Drive de la agenda en el href de "btnAgenda" (donde dice href="").
             Mientras esté vacío, el botón se muestra como "Agenda disponible pronto". -->
        <div class="stream-panel reveal">
            <span class="stream-icon"><i class="fa-solid fa-video" aria-hidden="true"></i></span>
            <div class="stream-info">
                <strong>Transmisión en vivo por Zoom</strong>
                <a href="https://cedia.zoom.us/j/87425203248" target="_blank" rel="noopener noreferrer">cedia.zoom.us/j/87425203248</a>
                <small>ID de reunión: 874 2520 3248 · Mismo enlace para ambas jornadas</small>
            </div>
            <div class="stream-actions">
                <a href="https://cedia.zoom.us/j/87425203248" target="_blank" rel="noopener noreferrer" class="btn btn-brand">
                    <i class="fa-solid fa-right-to-bracket me-2" aria-hidden="true"></i>Unirse por Zoom
                </a>
                <a href="https://drive.google.com/file/d/181kj1yDishu8GCUaiFcAfQHyLdQdeU9v/view?usp=sharing" id="btnAgenda" target="_blank" rel="noopener noreferrer" class="btn btn-outline-brand">
                    <i class="fa-solid fa-file-arrow-down me-2" aria-hidden="true"></i>Descargar agenda
                </a>
            </div>
        </div>

        <div class="text-center mb-4">
            <ul class="nav program-tabs" role="tablist">
                <li class="nav-item" role="presentation"><button class="nav-link active" id="tab-d1" data-bs-toggle="tab" data-bs-target="#dia1" type="button" role="tab" aria-controls="dia1" aria-selected="true">Día 1 · Lun 16</button></li>
                <li class="nav-item" role="presentation"><button class="nav-link" id="tab-d2" data-bs-toggle="tab" data-bs-target="#dia2" type="button" role="tab" aria-controls="dia2" aria-selected="false">Día 2 · Mar 17</button></li>
            </ul>
        </div>

        <div class="tab-content" style="max-width: 920px; margin: 0 auto;">
            <!-- DÍA 1 -->
            <div class="tab-pane fade show active" id="dia1" role="tabpanel" aria-labelledby="tab-d1">
                <div class="agenda">
                    <div class="agenda-row key"><time>08:00 – 09:00</time><strong>Registro e inauguración del I Seminario SMART4GREEN 2026</strong></div>

                    <div class="agenda-axis"><h4>Eje 1 · Tecnología, IA y digitalización</h4><p>Inteligencia artificial, IoT, transformación digital y Big Data aplicados al desarrollo.</p></div>
                    <div class="agenda-row"><time>09:00 – 09:30</time><div><strong>Dr. Raúl Antonio Aguilar</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/mx.png" srcset="https://flagcdn.com/w80/mx.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Universidad Autónoma de Yucatán · México</span><span class="talk pending">Tema por confirmar</span></div></div>
                    <div class="agenda-row"><time>09:30 – 10:00</time><div><strong>Ing. Wilson Zambrano</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/co.png" srcset="https://flagcdn.com/w80/co.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Investigador, Institución Universitaria Antonio José Camacho · Colombia</span><span class="talk pending">Tema por confirmar</span></div></div>
                    <div class="agenda-row"><time>10:00 – 10:30</time><div><strong>Ing. Víctor José Huilca</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Docente ESPOCH, Sede Morona Santiago · Ecuador</span><span class="talk">Difusión de resultados del Proyecto de Investigación DIPI90</span></div></div>
                    <div class="agenda-row break"><time>10:30 – 11:00</time><strong><i class="fa-solid fa-mug-hot me-2" aria-hidden="true"></i>Receso</strong></div>

                    <div class="agenda-axis"><h4>Eje 2 · Ambiente y sostenibilidad</h4><p>Monitoreo ambiental, conservación de la biodiversidad, cambio climático y resiliencia ecológica.</p></div>
                    <div class="agenda-row"><time>11:00 – 11:30</time><div><strong>Dra. Susan Ivonne Muñoz</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/cl.png" srcset="https://flagcdn.com/w80/cl.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Coordinadora del área de financiamiento, Agencia de Sustentabilidad y Cambio Climático · Chile</span><span class="talk pending">Tema por confirmar</span></div></div>
                    <div class="agenda-row"><time>11:30 – 12:00</time><div><strong>Dr. Yoelkis Alexis Laborde</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/cu.png" srcset="https://flagcdn.com/w80/cu.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Subdirector científico, Centro de Aplicaciones Tecnológicas para el Desarrollo Sostenible (CATEDES) · Cuba</span><span class="talk pending">Tema por confirmar</span></div></div>
                    <div class="agenda-row break"><time>12:00 – 14:00</time><strong><i class="fa-solid fa-utensils me-2" aria-hidden="true"></i>Receso para el almuerzo</strong></div>

                    <div class="agenda-axis"><h4>Eje 3 · Recursos naturales y territorio</h4><p>Minería responsable, gestión territorial sostenible y preservación de cuencas hidrográficas.</p></div>
                    <div class="agenda-row"><time>14:00 – 14:30</time><div><strong>Dr. Joel Morales Salas</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/cu.png" srcset="https://flagcdn.com/w80/cu.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Director del Centro de Estudio de Tecnologías Energéticas Renovables, Universidad Tecnológica de La Habana · Cuba</span><span class="talk pending">Tema por confirmar</span></div></div>
                    <div class="agenda-row"><time>14:30 – 15:00</time><div><strong>Dr. Theofilos Toulkeridis</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/gr.png" srcset="https://flagcdn.com/w80/gr.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Professor, Aristotle University of Thessaloniki · Grecia</span><span class="talk">Potencial geotérmico en el Ecuador</span></div></div>

                    <div class="agenda-axis"><h4>Eje 4 · Producción y zootecnia</h4><p>Agropecuaria de precisión y sistemas agroforestales sostenibles.</p></div>
                    <div class="agenda-row"><time>15:00 – 15:30</time><div><strong>Ing. Luis Arias</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Docente ESPOCH, Sede Morona Santiago · Ecuador</span><span class="talk">Producción de pastos alternativos</span></div></div>
                    <div class="agenda-row"><time>15:30 – 16:00</time><div><strong>Ing. Edwin Lozada</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Docente ESPOCH, Sede Morona Santiago · Ecuador</span><span class="talk">Rendimientos en la ganadería Charolaise</span></div></div>
                    <div class="agenda-row break"><time>16:00 – 16:30</time><strong><i class="fa-solid fa-mug-hot me-2" aria-hidden="true"></i>Receso</strong></div>

                    <div class="agenda-axis"><h4>Eje 5 · Economía y negocios sostenibles</h4><p>Economía circular, contabilidad, finanzas verdes y modelos de negocio sustentables.</p></div>
                    <div class="agenda-row"><time>16:30 – 17:00</time><div><strong>Dr. Oscar Zapata</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/ca.png" srcset="https://flagcdn.com/w80/ca.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Assistant Professor, School of Environment and Sustainability, University of Saskatchewan · Canadá</span><span class="talk pending">Tema por confirmar</span></div></div>
                    <div class="agenda-row"><time>17:00 – 17:30</time><div><strong>Ing. Carlos Samaniego Tello</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Analista Zonal de Fortalecimiento de Actores de la EPS · Ecuador</span><span class="talk pending">Tema por confirmar</span></div></div>

                    <div class="agenda-axis"><h4>Eje 6 · Derecho, sociedad y gobernanza</h4><p>Políticas públicas, bioética, gobernanza territorial y legislación ambiental.</p></div>
                    <div class="agenda-row"><time>17:30 – 18:00</time><div><strong>Dr. Ramiro Ávila Santamaría</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Docente, Universidad Andina Simón Bolívar · Ecuador</span><span class="talk pending">Tema por confirmar</span></div></div>
                    <div class="agenda-row key"><time>18:00</time><strong>Cierre de la primera jornada</strong></div>
                </div>
            </div>

            <!-- DÍA 2 -->
            <div class="tab-pane fade" id="dia2" role="tabpanel" aria-labelledby="tab-d2">
                <div class="agenda">
                    <div class="agenda-row key"><time>09:00 – 13:00</time><div><strong>Feria de Emprendimientos SMART4GREEN 2026</strong><span class="tbc">Presencial · lugar por confirmar</span></div></div>
                    <div class="agenda-row break"><time>13:00 – 15:00</time><strong><i class="fa-solid fa-utensils me-2" aria-hidden="true"></i>Receso</strong></div>

                    <div class="agenda-axis"><h4>Eje 7 · Innovación y emprendimiento</h4><p>Jornada de actualización empresarial para graduados.</p></div>
                    <div class="agenda-row"><time>15:00 – 15:30</time><div><strong>Ing. Jairo Andrés Becerra</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Lowell Mineral Exploration · Ecuador</span><span class="talk">Liderazgo empresarial</span></div></div>
                    <div class="agenda-row"><time>15:30 – 16:00</time><div><strong>Ing. Danilo Tayupanda</strong><span class="tbc"><img class="flag" src="https://flagcdn.com/w40/ec.png" srcset="https://flagcdn.com/w80/ec.png 2x" width="20" height="15" alt="" aria-hidden="true" onerror="this.remove()">Director, Fundación Atasim · Ecuador</span><span class="talk">Emprendimientos</span></div></div>
                    <div class="agenda-row key"><time>16:00 – 16:30</time><strong>Clausura y cierre oficial del evento</strong></div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- CIFRAS -->
<section class="stats" aria-label="El evento en cifras">
    <div class="container">
        <div class="row text-center g-4">
            <div class="col-6 col-md-3"><div class="stat-number" data-target="14">14</div><div class="stat-label">Ponencias programadas</div></div>
            <div class="col-6 col-md-3"><div class="stat-number" data-target="7">7</div><div class="stat-label">Ejes temáticos</div></div>
            <div class="col-6 col-md-3"><div class="stat-number" data-target="2">2</div><div class="stat-label">Jornadas académicas</div></div>
            <div class="col-6 col-md-3"><div class="stat-number" data-target="1">1</div><div class="stat-label">Feria de emprendimientos</div></div>
        </div>
    </div>
</section>

<!-- ORGANIZADORES -->
<section id="organizadores" class="section">
    <div class="container">
        <div class="section-head center reveal">
            <span class="kicker">Respaldo institucional</span>
            <h2 class="section-title">Organizadores y redes académicas</h2>
        </div>

        <!-- Guarde los logos en assets/logos/ con los nombres indicados en cada src. -->
        <h3 class="group-title">Institución organizadora</h3>
        <div class="row g-4 justify-content-center">
            <div class="col-md-6 col-lg-5 reveal">
                <article class="partner">
                    <div class="partner-logo">
                        <img src="assets/logos/espoch.png" alt="Logo ESPOCH" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                        <i class="fa-solid fa-building-columns" aria-hidden="true"></i>
                    </div>
                    <h3>Escuela Superior Politécnica de Chimborazo</h3>
                    <p>Sede Morona Santiago</p>
                </article>
            </div>
        </div>

        <!--
            ENLACES DE PROYECTOS Y REDES
            Escriba la dirección web de cada uno en el atributo href (donde dice href="").
            Mientras un href esté vacío, la tarjeta se muestra normal pero sin enlace.
        -->
        <h3 class="group-title">Proyectos participantes</h3>
        <div class="row g-4 justify-content-center">
            <div class="col-md-6 reveal">
                <!-- URL del Proyecto de investigación -->
                <a class="partner-link" href="https://www.instagram.com/amazonaiot/" target="_blank" rel="noopener noreferrer">
                    <article class="partner">
                        <div class="partner-logo">
                            <img src="assets/logos/AMAZON AIoT FINAL.png" alt="Logo AMAZON AIoT" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-diagram-project" aria-hidden="true"></i>
                        </div>
                        <h3>Proyecto de investigación</h3>
                        <p>Desarrollo e implementación de un Sistema Inteligente de Monitoreo de la Calidad Ambiental en Ecosistemas Amazónicos mediante Tecnologías IoT e Inteligencia Artificial.</p>
                        <span class="visit">Visitar sitio <i class="fa-solid fa-arrow-up-right-from-square ms-1" aria-hidden="true"></i></span>
                    </article>
                </a>
            </div>
            <div class="col-md-6 reveal">
                <!-- URL del Proyecto de vinculación (Hidroponía Inteligente Amazónica) -->
                <a class="partner-link" href="https://www.instagram.com/amazonaiot/" target="_blank" rel="noopener noreferrer">
                    <article class="partner">
                        <div class="partner-logo">
                            <img src="assets/logos/LOGO3.png" alt="Logo Hidroponía Inteligente Amazónica" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-seedling" aria-hidden="true"></i>
                        </div>
                        <h3>Proyecto de vinculación</h3>
                        <p>Hidroponía Inteligente Amazónica.</p>
                        <span class="visit">Visitar sitio <i class="fa-solid fa-arrow-up-right-from-square ms-1" aria-hidden="true"></i></span>
                    </article>
                </a>
            </div>
        </div>

        <h3 class="group-title">Redes y grupos de investigación</h3>
        <div class="row g-4 justify-content-center">
            <div class="col-md-6 col-lg-4 reveal">
                <!-- URL de la Red RAMAI -->
                <a class="partner-link" href="" target="_blank" rel="noopener noreferrer">
                    <article class="partner">
                        <div class="partner-logo">
                            <img src="assets/logos/ramai.jpeg" alt="Logo Red RAMAI" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-network-wired" aria-hidden="true"></i>
                        </div>
                        <h3>Red RAMAI</h3>
                        <p>Red Agropecuaria, Medio Ambiente e Inteligencia Artificial</p>
                        <span class="visit">Visitar sitio <i class="fa-solid fa-arrow-up-right-from-square ms-1" aria-hidden="true"></i></span>
                    </article>
                </a>
            </div>
            <div class="col-md-6 col-lg-4 reveal">
                <!-- URL del grupo IITMS -->
                <a class="partner-link" href="" target="_blank" rel="noopener noreferrer">
                    <article class="partner">
                        <div class="partner-logo">
                            <img src="assets/logos/logo IITMS.png" alt="Logo IITMS" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-microscope" aria-hidden="true"></i>
                        </div>
                        <h3>IITMS</h3>
                        <p>Grupo de Investigación Innovación y Tecnología Morona Santiago</p>
                        <span class="visit">Visitar sitio <i class="fa-solid fa-arrow-up-right-from-square ms-1" aria-hidden="true"></i></span>
                    </article>
                </a>
            </div>
            <div class="col-md-6 col-lg-4 reveal">
                <!-- URL del grupo AMAZONAIOT -->
                <a class="partner-link" href="https://www.instagram.com/emprendimientosms2026/" target="_blank" rel="noopener noreferrer">
                    <article class="partner">
                        <div class="partner-logo">
                            <img src="assets/logos/emprendi.png" alt="Logo AMAZONAIOT" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-microchip" aria-hidden="true"></i>
                        </div>
                        <h3>Centro Consultor de Emprendimiento </h3>
                        <p>ESPOCH Sede Morona Santiago</p>
                        <span class="visit">Visitar sitio <i class="fa-solid fa-arrow-up-right-from-square ms-1" aria-hidden="true"></i></span>
                    </article>
                </a>
            </div>
        </div>

        <h3 class="group-title">Empresas patrocinadoras</h3>
        <div class="row g-4 justify-content-center">
            <!-- NEOIA: cuando tenga la web oficial, envuelva este bloque en <a class="partner-link" href="URL" target="_blank" rel="noopener noreferrer"> -->
            <div class="col-6 col-lg-3 reveal">
                <article class="partner sponsor">
                    <div class="partner-logo">
                        <img src="assets/logos/neoia.png" alt="Logo NEOIA" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                        <i class="fa-solid fa-handshake" aria-hidden="true"></i>
                    </div>
                    <h3>NEOIA</h3>
                </article>
            </div>
            <div class="col-6 col-lg-3 reveal">
                <a class="partner-link" href="https://www.grupoelectrostore.com/" target="_blank" rel="noopener noreferrer">
                    <article class="partner sponsor">
                        <div class="partner-logo">
                            <img src="assets/logos/electrostore.svg" alt="Logo Electrostore" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-handshake" aria-hidden="true"></i>
                        </div>
                        <h3>Electrostore</h3>
                    </article>
                </a>
            </div>
            <!-- DRON: cuando tenga la web oficial, envuelva este bloque en <a class="partner-link" href="URL" target="_blank" rel="noopener noreferrer"> -->
            <div class="col-6 col-lg-3 reveal">
                <article class="partner sponsor">
                    <div class="partner-logo">
                        <img src="assets/logos/dron.png" alt="Logo DRON" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                        <i class="fa-solid fa-handshake" aria-hidden="true"></i>
                    </div>
                    <h3>DRON</h3>
                </article>
            </div>
            <div class="col-6 col-lg-3 reveal">
                <a class="partner-link" href="https://www.pcbmicrocircuitos.com/en" target="_blank" rel="noopener noreferrer">
                    <article class="partner sponsor">
                        <div class="partner-logo">
                            <img src="assets/logos/Microcircuitos SAS.png" alt="Logo Microcircuitos" loading="lazy" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-handshake" aria-hidden="true"></i>
                        </div>
                        <h3>Microcircuitos</h3>
                    </article>
                </a>
            </div>
        </div>
    </div>
</section>

<!-- CONTACTO -->
<section id="contacto" class="section section-alt">
    <div class="container">
        <div class="row g-5 align-items-stretch">
            <div class="col-lg-6 reveal">
                <span class="kicker">Canales oficiales</span>
                <h2 class="section-title">Contáctanos</h2>
                <p class="mb-4">¿Tienes dudas sobre las ponencias, la inscripción al seminario o la participación en la feria? Escríbenos.</p>
                <div class="contact-item">
                    <i class="fa-solid fa-envelope" aria-hidden="true"></i>
                    <div>
                        <strong>Correo electrónico</strong>
                        <a href="mailto:macarena.flores@espoch.edu.ec">macarena.flores@espoch.edu.ec</a><br>
                        <a href="mailto:carlav.haro@espoch.edu.ec">carlav.haro@espoch.edu.ec</a><br>
                        <a href="mailto:juanpablo.haro@espoch.edu.ec">juanpablo.haro@espoch.edu.ec</a>
                    </div>
                </div>
                <div class="contact-item">
                    <i class="fa-brands fa-whatsapp" aria-hidden="true"></i>
                    <div>
                        <strong>WhatsApp</strong>
                        <a href="https://wa.me/593996381808?text=Hola,%20deseo%20información%20sobre%20SMART4GREEN%202026" target="_blank" rel="noopener">+593 99 638 1808</a>
                    </div>
                </div>
                <div class="contact-item">
                    <i class="fa-brands fa-facebook-f" aria-hidden="true"></i>
                    <div>
                        <strong>Facebook</strong>
                        <a href="https://www.facebook.com/espochms?locale=es_LA" target="_blank" rel="noopener">ESPOCH Sede Morona Santiago</a>
                    </div>
                </div>
                <div class="contact-item">
                    <i class="fa-solid fa-location-dot" aria-hidden="true"></i>
                    <div>
                        <strong>Sede</strong>
                        <span>Macas, Morona Santiago, Ecuador — Escuela Superior Politécnica de Chimborazo</span>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 reveal">
                <div class="cta-panel d-flex flex-column justify-content-center">
                    <span class="kicker" style="color:#8FE0B5">Participación gratuita online</span>
                    <h3 class="h2 mb-3">Inscríbete al seminario</h3>
                    <p class="mb-4">Asegura tu lugar en las 14 ponencias online de SMART4GREEN 2026 completando el formulario de inscripción general.</p>
                    <div class="d-flex flex-wrap gap-2">
                        <a href="https://forms.gle/oieuCepQ93R2p2tTA" target="_blank" rel="noopener noreferrer" class="btn btn-gold btn-lg">Inscribirme al seminario</a>
                        <a href="#emprendimiento" class="btn btn-ghost btn-lg">Participar en la feria</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

</main>

<!-- FOOTER -->
<footer class="pt-5">
    <div class="container">
        <div class="row g-4 pb-4">
            <div class="col-lg-5">
                <a class="brand d-inline-block mb-3" href="#inicio" style="color:#8FE0B5">SMART<span style="color:#fff">4GREEN</span></a>
                <p class="mb-0" style="max-width:26rem">I Seminario Multidisciplinario de Innovación para el Desarrollo Sostenible. Organizado por la ESPOCH Sede Morona Santiago.</p>
            </div>
            <div class="col-6 col-lg-3">
                <h4>Navegación</h4>
                <ul>
                    <li><a href="#ejes">Ejes temáticos</a></li>
                    <li><a href="#speakers">Conferencistas</a></li>
                    <li><a href="#programa">Programa</a></li>
                    <li><a href="#emprendimiento">Feria de emprendimientos</a></li>
                </ul>
            </div>
            <div class="col-6 col-lg-4">
                <h4>Fechas</h4>
                <ul>
                    <li>Seminario online · 16 y 17 de noviembre de 2026</li>
                    <li>Feria presencial · 17 de noviembre · 09h00–13h00</li>
                    <li><a href="https://sedemacas.espoch.edu.ec/" target="_blank" rel="noopener">sedemacas.espoch.edu.ec</a></li>
                </ul>
            </div>
        </div>
        <div class="footer-bottom py-3 d-flex flex-wrap justify-content-between gap-2">
            <span>&copy; 2026 SMART4GREEN · Escuela Superior Politécnica de Chimborazo.</span>
            <span>Macas, Morona Santiago, Ecuador</span>
        </div>
    </div>
</footer>

<!-- FLOTANTES -->
<a href="https://wa.me/593996381808?text=Hola,%20deseo%20información%20sobre%20SMART4GREEN%202026" class="whatsapp-float" target="_blank" rel="noopener" aria-label="Contacto por WhatsApp">
    <i class="fa-brands fa-whatsapp" aria-hidden="true"></i>
</a>
<a href="#inicio" class="back-to-top" id="backToTop" aria-label="Volver arriba"><i class="fa-solid fa-arrow-up" aria-hidden="true"></i></a>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
<script>
    document.body.classList.remove('no-js');

    // Tarjetas de proyectos/redes sin URL: se muestran sin enlace
    document.querySelectorAll('a.partner-link').forEach(a => {
        const href = (a.getAttribute('href') || '').trim();
        if (!href || href === '#') {
            a.classList.add('no-url');
            a.removeAttribute('href');
            a.setAttribute('tabindex', '-1');
        }
    });

    // Cuenta regresiva
    (function () {
        const target = new Date('2026-11-16T08:00:00-05:00').getTime();
        const end = new Date('2026-11-17T17:00:00-05:00').getTime();
        const pad = n => String(n).padStart(2, '0');
        const el = id => document.getElementById(id);
        function tick() {
            const now = Date.now();
            const diff = target - now;
            if (diff <= 0) {
                el('countdownLabel').textContent = now < end ? '¡El evento está en curso!' : 'Gracias por acompañarnos';
                el('countdown').hidden = true;
                clearInterval(timer);
                return;
            }
            el('days').textContent = pad(Math.floor(diff / 864e5));
            el('hours').textContent = pad(Math.floor(diff % 864e5 / 36e5));
            el('minutes').textContent = pad(Math.floor(diff % 36e5 / 6e4));
            el('seconds').textContent = pad(Math.floor(diff % 6e4 / 1e3));
        }
        const timer = setInterval(tick, 1000);
        tick();
    })();

    // Animación de entrada y contadores
    (function () {
        const reveals = document.querySelectorAll('.reveal');
        if (!('IntersectionObserver' in window)) { reveals.forEach(r => r.classList.add('in')); return; }
        const io = new IntersectionObserver(entries => {
            entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('in'); io.unobserve(e.target); } });
        }, { threshold: 0.12 });
        reveals.forEach(r => io.observe(r));

        const counters = document.querySelectorAll('.stat-number');
        const co = new IntersectionObserver(entries => {
            entries.forEach(e => {
                if (!e.isIntersecting) return;
                const node = e.target, goal = +node.dataset.target, t0 = performance.now(), dur = 1200;
                const step = t => {
                    const p = Math.min((t - t0) / dur, 1);
                    node.textContent = Math.round(goal * (1 - Math.pow(1 - p, 3)));
                    if (p < 1) requestAnimationFrame(step);
                };
                requestAnimationFrame(step);
                co.unobserve(node);
            });
        }, { threshold: 0.5 });
        counters.forEach(c => co.observe(c));
    })();

    // Carrusel de conferencistas: flechas, teclado, táctil e indicador de posición
    (function () {
        const track = document.getElementById('spkTrack');
        if (!track) return;
        const prev = document.getElementById('spkPrev');
        const next = document.getElementById('spkNext');
        const status = document.getElementById('spkStatus');
        const slides = [...track.querySelectorAll('.spk-slide')];
        const total = slides.length;
        const reduce = window.matchMedia('(prefers-reduced-motion: reduce)');

        const step = () => slides.length > 1 ? slides[1].offsetLeft - slides[0].offsetLeft : track.clientWidth;
        const visible = () => Math.max(1, Math.round(track.clientWidth / step()));
        const current = () => Math.round(track.scrollLeft / step());

        function goTo(index) {
            const i = Math.max(0, Math.min(index, total - 1));
            track.scrollTo({ left: slides[i].offsetLeft - slides[0].offsetLeft, behavior: reduce.matches ? 'auto' : 'smooth' });
        }

        function update() {
            const max = track.scrollWidth - track.clientWidth;
            prev.disabled = track.scrollLeft <= 2;
            next.disabled = track.scrollLeft >= max - 2;
            const first = Math.min(current() + 1, total);
            const last = Math.min(first + visible() - 1, total);
            status.textContent = first === last ? `Ponente ${first} de ${total}` : `Ponentes ${first}–${last} de ${total}`;
        }

        prev.addEventListener('click', () => goTo(current() - 1));
        next.addEventListener('click', () => goTo(current() + 1));

        track.addEventListener('keydown', e => {
            const keys = { ArrowLeft: current() - 1, ArrowRight: current() + 1, Home: 0, End: total - 1 };
            if (e.key in keys) { e.preventDefault(); goTo(keys[e.key]); }
        });

        let raf = null;
        track.addEventListener('scroll', () => {
            if (raf) return;
            raf = requestAnimationFrame(() => { raf = null; update(); });
        }, { passive: true });
        window.addEventListener('resize', update);
        update();
    })();

    // Botón de agenda: si aún no tiene enlace de Drive, se muestra como pendiente
    (function () {
        const btn = document.getElementById('btnAgenda');
        if (!btn) return;
        const href = (btn.getAttribute('href') || '').trim();
        if (!href || href === '#') {
            btn.removeAttribute('href');
            btn.classList.add('is-pending');
            btn.setAttribute('aria-disabled', 'true');
            btn.innerHTML = '<i class="fa-regular fa-clock me-2" aria-hidden="true"></i>Agenda disponible';
        }
    })();

    // Feria: al vencer la fecha límite (9 de noviembre, 23:59 hora de Ecuador) cambia el estado
    (function () {
        const badge = document.getElementById('fairStatus');
        if (!badge) return;
        if (Date.now() > new Date('2026-11-09T23:59:59-05:00').getTime()) {
            badge.innerHTML = '<i class="fa-solid fa-circle me-1" style="font-size:.5rem;vertical-align:middle" aria-hidden="true"></i>Recepción de propuestas cerrada';
        }
    })();

    // Navegación: sombra al desplazar, enlace activo, botón volver arriba, cierre del menú móvil
    (function () {
        const nav = document.getElementById('siteNav');
        const toTop = document.getElementById('backToTop');
        const links = [...document.querySelectorAll('#navMenu .nav-link[href^="#"]')];
        const sections = links.map(l => document.querySelector(l.getAttribute('href'))).filter(Boolean);
        function onScroll() {
            const y = window.scrollY;
            nav.classList.toggle('scrolled', y > 8);
            toTop.classList.toggle('show', y > 500);
            let current = null;
            sections.forEach(s => { if (s.getBoundingClientRect().top <= 120) current = s.id; });
            links.forEach(l => l.classList.toggle('active', l.getAttribute('href') === '#' + current));
        }
        window.addEventListener('scroll', onScroll, { passive: true });
        onScroll();

        const menu = document.getElementById('navMenu');
        menu.querySelectorAll('a').forEach(a => a.addEventListener('click', () => {
            if (menu.classList.contains('show')) bootstrap.Collapse.getOrCreateInstance(menu).hide();
        }));
    })();
</script>
</body>
</html>

