<svg width="1200" height="180" viewBox="0 0 1200 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg2" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0a0a0a"/>
      <stop offset="50%" stop-color="#14110a"/>
      <stop offset="100%" stop-color="#0a0a0a"/>
    </linearGradient>
    <linearGradient id="shimmer2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#8a6d1f"/>
      <stop offset="45%" stop-color="#f5e1a4"/>
      <stop offset="55%" stop-color="#f5e1a4"/>
      <stop offset="100%" stop-color="#8a6d1f"/>
      <animateTransform attributeName="gradientTransform" type="translate" values="-1.4 0;1.4 0;-1.4 0" dur="5s" repeatCount="indefinite"/>
    </linearGradient>
  </defs>

  <rect width="1200" height="180" fill="url(#bg2)"/>

  <line x1="600" y1="55" x2="600" y2="55" stroke="#D4AF37" stroke-width="1" opacity="0.6">
    <animate attributeName="x1" values="600;430;430" dur="1.6s" fill="freeze"/>
    <animate attributeName="x2" values="600;770;770" dur="1.6s" fill="freeze"/>
  </line>

  <text x="600" y="98" text-anchor="middle" font-family="Georgia, serif" font-size="26" letter-spacing="2" fill="url(#shimmer2)">
    Let&#8217;s build something timeless
  </text>

  <text x="600" y="132" text-anchor="middle" font-family="Georgia, serif" font-size="13" letter-spacing="3" fill="#8b7a55">
    OPEN TO OPPORTUNITIES &#183; COLLABORATIONS &#183; OPEN SOURCE
  </text>
</svg>
