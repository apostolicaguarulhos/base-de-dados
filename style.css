:root {
  --navy-950: #061725;
  --navy-900: #0a2438;
  --navy-800: #103753;
  --blue-700: #164b73;
  --gold-500: #c99a35;
  --gold-400: #dfb85a;
  --gold-100: #fff3cf;
  --bg: #f4f6f8;
  --surface: #ffffff;
  --surface-soft: #f8fafc;
  --text: #1f2937;
  --muted: #667085;
  --line: #e5e7eb;
  --shadow: 0 18px 50px rgba(6, 23, 37, 0.12);
  --radius-xl: 28px;
  --radius-lg: 22px;
  --radius-md: 16px;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  font-family: "Montserrat", Arial, sans-serif;
  color: var(--text);
  background:
    radial-gradient(circle at 8% 0%, rgba(223, 184, 90, 0.22), transparent 30%),
    linear-gradient(180deg, #ffffff 0%, var(--bg) 42%, #eef2f6 100%);
}

.app-bg {
  position: fixed;
  inset: 0;
  pointer-events: none;
  background:
    linear-gradient(90deg, rgba(6,23,37,0.04) 1px, transparent 1px),
    linear-gradient(rgba(6,23,37,0.035) 1px, transparent 1px);
  background-size: 44px 44px;
  mask-image: linear-gradient(to bottom, rgba(0,0,0,0.65), transparent 72%);
}

.layout {
  position: relative;
  width: min(1280px, calc(100% - 32px));
  min-height: calc(100vh - 64px);
  margin: 32px auto;
  display: grid;
  grid-template-columns: 360px 1fr;
  gap: 22px;
}

.sidebar {
  padding: 26px;
  border-radius: var(--radius-xl);
  color: #fff;
  background:
    linear-gradient(160deg, rgba(223,184,90,0.12), transparent 38%),
    linear-gradient(180deg, var(--navy-900), var(--navy-950));
  box-shadow: var(--shadow);
  display: flex;
  flex-direction: column;
  gap: 26px;
  overflow: hidden;
  position: relative;
}

.sidebar::after {
  content: "";
  position: absolute;
  width: 210px;
  height: 210px;
  right: -80px;
  top: -70px;
  border-radius: 50%;
  background: rgba(223,184,90,0.15);
  filter: blur(2px);
}

.brand {
  position: relative;
  z-index: 1;
  display: flex;
  align-items: center;
  gap: 14px;
}

.brand-logo {
  width: 62px;
  height: 62px;
  object-fit: contain;
  padding: 9px;
  border-radius: 20px;
  background: #fff;
  box-shadow: 0 14px 30px rgba(0,0,0,0.18);
}

.brand span {
  display: block;
  margin-bottom: 4px;
  color: rgba(255,255,255,0.68);
  font-size: 0.74rem;
  font-weight: 600;
}

.brand strong {
  display: block;
  font-size: 1.04rem;
  font-weight: 800;
}

.section-label {
  margin: 0 0 8px;
  color: var(--gold-500);
  text-transform: uppercase;
  letter-spacing: 0.12em;
  font-size: 0.72rem;
  font-weight: 800;
}

.sidebar .section-label {
  color: var(--gold-400);
}

.sidebar-hero {
  position: relative;
  z-index: 1;
  padding: 24px;
  border: 1px solid rgba(255,255,255,0.12);
  border-radius: 24px;
  background: rgba(255,255,255,0.07);
}

.sidebar-hero h1 {
  margin: 0;
  font-size: 2.3rem;
  line-height: 1.02;
  letter-spacing: -0.055em;
}

.sidebar-hero p {
  margin: 18px 0 0;
  color: rgba(255,255,255,0.72);
  line-height: 1.65;
  font-size: 0.93rem;
}

.mini-dashboard {
  position: relative;
  z-index: 1;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
}

.dash-card {
  padding: 16px;
  border-radius: 18px;
  background: rgba(255,255,255,0.08);
  border: 1px solid rgba(255,255,255,0.1);
}

.dash-card.active {
  background: linear-gradient(135deg, rgba(223,184,90,0.26), rgba(201,154,53,0.12));
  border-color: rgba(223,184,90,0.34);
}

.dash-card small {
  display: block;
  margin-bottom: 8px;
  color: rgba(255,255,255,0.58);
  font-size: 0.7rem;
  font-weight: 700;
}

.dash-card strong {
  font-size: 0.92rem;
}

footer {
  position: relative;
  z-index: 1;
  margin-top: auto;
  color: rgba(255,255,255,0.62);
  font-size: 0.78rem;
  font-weight: 600;
}

.workspace {
  display: flex;
  flex-direction: column;
  gap: 18px;
}

.topbar {
  padding: 22px 24px;
  border-radius: var(--radius-xl);
  background: rgba(255,255,255,0.92);
  border: 1px solid rgba(229,231,235,0.9);
  box-shadow: var(--shadow);
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.topbar h2 {
  margin: 0;
  color: var(--navy-900);
  font-size: clamp(1.25rem, 3vw, 1.65rem);
}

.status {
  display: inline-flex;
  align-items: center;
  gap: 9px;
  padding: 10px 14px;
  border-radius: 999px;
  background: #f0fdf4;
  color: #166534;
  font-size: 0.78rem;
  font-weight: 800;
}

.status span {
  width: 9px;
  height: 9px;
  border-radius: 999px;
  background: #22c55e;
  box-shadow: 0 0 0 6px rgba(34,197,94,0.13);
}

.summary-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 14px;
}

.summary-grid article {
  padding: 18px;
  border-radius: var(--radius-lg);
  background: rgba(255,255,255,0.92);
  border: 1px solid rgba(229,231,235,0.95);
  box-shadow: 0 10px 32px rgba(6,23,37,0.07);
}

.summary-grid small {
  display: block;
  margin-bottom: 8px;
  color: var(--muted);
  font-weight: 700;
  font-size: 0.72rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
}

.summary-grid strong {
  display: block;
  color: var(--navy-900);
  font-size: 1.1rem;
  margin-bottom: 7px;
}

.summary-grid p {
  margin: 0;
  color: var(--muted);
  line-height: 1.45;
  font-size: 0.86rem;
}

.form-panel {
  padding: 20px;
  border-radius: var(--radius-xl);
  background: rgba(255,255,255,0.96);
  border: 1px solid rgba(229,231,235,0.96);
  box-shadow: var(--shadow);
  overflow: hidden;
}

.panel-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 18px;
  padding: 8px 8px 20px;
  border-bottom: 1px solid var(--line);
  margin-bottom: 14px;
}

.panel-header h3 {
  margin: 0;
  color: var(--navy-900);
  font-size: 1.35rem;
}

.panel-header img {
  width: 42px;
  height: 42px;
  object-fit: contain;
}

iframe {
  width: 100%;
  display: block;
  border-radius: 18px;
  background: transparent;
}

@media (max-width: 980px) {
  .layout {
    grid-template-columns: 1fr;
    margin: 16px auto;
    width: min(100% - 20px, 780px);
  }

  .summary-grid {
    grid-template-columns: 1fr;
  }

  .sidebar-hero h1 {
    font-size: 2rem;
  }
}

@media (max-width: 560px) {
  .sidebar,
  .topbar,
  .form-panel {
    border-radius: 22px;
  }

  .topbar {
    align-items: flex-start;
    flex-direction: column;
  }

  .mini-dashboard {
    grid-template-columns: 1fr;
  }
}
