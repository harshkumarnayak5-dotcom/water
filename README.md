# water
Hi
Ideas about Water Conservation and Management
body {
    margin: 0;
    font-family: "Poppins", sans-serif;
    background: #e3f5ff;
    color: #034f84;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 40px;
    background: rgba(255, 255, 255, 0.78);
    backdrop-filter: blur(10px);
    position: sticky;
    top: 0;
    z-index: 2000;
}

nav a {
    margin-left: 25px;
    text-decoration: none;
    font-weight: 600;
    color: #01579b;
}
nav a:hover { color: #0288d1; }

header {
    text-align: center;
    padding: 130px 30px 220px;
    background: linear-gradient(to bottom, #0277bd, #4fc3f7);
    color: white;
    position: relative;
    overflow: hidden;
}

.wave-container {
    position: absolute;
    bottom: 0;
    width: 100%;
}

.wave {
    width: 200%;
    height: 180px;
    background: url('../img/waves.svg');
    background-size: 50% 180px;
    animation: moveWave 14s linear infinite;
    opacity: 0.75;
}
.wave2 { animation-duration: 20s; opacity: 0.45; }
.wave3 { animation-duration: 26s; opacity: 0.28; }

@keyframes moveWave {
    from { transform: translateX(0); }
    to { transform: translateX(-50%); }
}

.section {
    max-width: 1000px;
    margin: 50px auto;
    background: white;
    padding: 40px;
    border-radius: 16px;
    box-shadow: 0 6px 25px rgba(0,0,0,0.18);
}

.icon {
    width: 48px;
    margin-right: 12px;
    vertical-align: middle;
}

footer {
    text-align: center;
    padding: 25px;
    background: #0277bd;
    color: white;
    margin-top: 50px;
}

/* SEARCH BAR */
.search-bar {
    width: 80%;
    padding: 14px;
    margin: 20px auto;
    display: block;
    border-radius: 10px;
    border: 2px solid #0288d1;
    font-size: 1.1rem;
}
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
  <path fill="#fff" fill-opacity="1" d="M0,224L60,197C120,171,240,117,360,90C480,64,600,64,720,74C840,85,960,107,1080,138C1200,171,1320,213,1380,234L1440,256V320H0Z"></path>
</svg>



           
