/* ========================================================================== */
/* Thème KNI (Kelipat Nogah Initiative) - Style Ésotérique & Industriel        */
/* ========================================================================== */

:root {
    --kni-bg: #0f1115;
    --kni-panel: #161a22;
    --kni-text: #c9d1d9;
    --kni-accent: #2ea043; /* Vert mystique/lumineux */
    --kni-warning: #d29922;
    --kni-border: #30363d;
}

body {
    background-color: var(--kni-bg) !important;
    color: var(--kni-text) !important;
}

/* Conteneur principal de la KNI */
.kni-container {
    background-color: var(--kni-panel);
    border: 1px solid var(--kni-border);
    border-left: 4px solid var(--kni-accent);
    padding: 15px;
    margin: 20px 0;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
}

/* En-têtes de dossiers classifiés KNI */
.kni-header {
    font-family: 'Courier New', monospace;
    color: var(--kni-accent);
    text-transform: uppercase;
    letter-spacing: 1px;
    border-bottom: 1px solid var(--kni-border);
    padding-bottom: 5px;
    margin-bottom: 10px;
}