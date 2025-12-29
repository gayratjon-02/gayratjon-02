<div align="center">

<!-- Animated header (blob behind the title) -->
<svg width="720" height="170" viewBox="0 0 720 170" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Hi, I'm Gayratjon">
  <defs>
    <linearGradient id="blobGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%">
        <animate attributeName="stop-color" dur="8s" repeatCount="indefinite"
          values="#7F7CFF;#9B8CFF;#6F6DFF;#7F7CFF"/>
      </stop>
      <stop offset="100%">
        <animate attributeName="stop-color" dur="8s" repeatCount="indefinite"
          values="#5A58E8;#6B6AF0;#4F4DE3;#5A58E8"/>
      </stop>
    </linearGradient>
  </defs>

  <!-- Blob -->
  <path fill="url(#blobGradient)" opacity="0.95">
    <animate attributeName="d" dur="7s" repeatCount="indefinite"
      values="
        M210,45 Q360,10 510,45 Q560,85 510,125 Q360,155 210,125 Q160,85 210,45 Z;
        M225,40 Q360,0 495,40 Q585,85 495,130 Q360,170 225,130 Q135,85 225,40 Z;
        M205,50 Q360,20 515,50 Q555,85 515,120 Q360,150 205,120 Q165,85 205,50 Z;
        M210,45 Q360,10 510,45 Q560,85 510,125 Q360,155 210,125 Q160,85 210,45 Z
      "/>
    <animateTransform attributeName="transform" type="translate" dur="6s" repeatCount="indefinite"
      values="0 0; 6 2; 0 0"/>
  </path>

  <!-- Title -->
  <text x="360" y="103" text-anchor="middle"
        font-size="52" font-weight="800"
        fill="#FFFFFF"
        font-family="Inter, Segoe UI, Arial, sans-serif">
    Hi, I’m Gayratjon
  </text>
</svg>

<p><strong>Full-Stack Developer</strong> — Node.js · NestJS · Next.js</p>

<p>
  📍 South Korea &nbsp;·&nbsp;
  <a href="https://www.upwork.com/freelancers/~01719c3ae301384b5f?mp_source=share">Upwork</a>
</p>

<!-- Tech icons (minimal, clean) -->
<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,nestjs,graphql,mongodb,postgres,redis,docker,nginx,aws,linux&perline=7" />
</p>

<!-- Optional: small visitor badge (remove if you don't want it) -->
<p>
  <img src="https://komarev.com/ghpvc/?username=gayratjon-02&style=flat&label=visitors" alt="visitors"/>
</p>

</div>
