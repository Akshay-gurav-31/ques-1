<svg viewBox="0 0 800 900" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:1" />
    </linearGradient>
    <filter id="shadow">
      <feDropShadow dx="0" dy="2" stdDeviation="4" flood-opacity="0.15"/>
    </filter>
  </defs>
  
  <!-- Background -->
  <rect width="800" height="900" fill="#f8f9fa" rx="12"/>
  
  <!-- Header Section -->
  <rect width="800" height="120" fill="url(#headerGrad)" rx="12"/>
  <text x="40" y="50" font-family="Arial, sans-serif" font-size="28" font-weight="bold" fill="white">Quest Details</text>
  <text x="40" y="85" font-family="Arial, sans-serif" font-size="14" fill="rgba(255,255,255,0.9)">Quest ID: e3694732-3ffc-4c56-8880-716cf66de538</text>
  
  <!-- Status Badge -->
  <rect x="650" y="35" width="120" height="35" fill="#fbbf24" rx="17.5" filter="url(#shadow)"/>
  <text x="710" y="58" font-family="Arial, sans-serif" font-size="14" font-weight="600" fill="#1f2937" text-anchor="middle">In Progress</text>
  
  <!-- About Section -->
  <g transform="translate(40, 160)">
    <!-- Book Icon -->
    <rect x="0" y="0" width="40" height="32" fill="#667eea" rx="3"/>
    <rect x="5" y="5" width="30" height="22" fill="white" rx="2"/>
    <line x1="10" y1="12" x2="30" y2="12" stroke="#667eea" stroke-width="2"/>
    <line x1="10" y1="18" x2="25" y2="18" stroke="#667eea" stroke-width="2"/>
    
    <text x="50" y="22" font-family="Arial, sans-serif" font-size="20" font-weight="bold" fill="#1f2937">About This Quest</text>
    <text x="0" y="60" font-family="Arial, sans-serif" font-size="16" fill="#4b5563">Hello World!! hellow quest</text>
  </g>
  
  <!-- Key Objectives Section -->
  <g transform="translate(40, 260)">
    <!-- Target Icon -->
    <circle cx="20" cy="16" r="16" fill="#10b981" opacity="0.2"/>
    <circle cx="20" cy="16" r="12" fill="#10b981" opacity="0.4"/>
    <circle cx="20" cy="16" r="8" fill="#10b981" opacity="0.6"/>
    <circle cx="20" cy="16" r="4" fill="#10b981"/>
    
    <text x="50" y="22" font-family="Arial, sans-serif" font-size="20" font-weight="bold" fill="#1f2937">Key Objectives</text>
    
    <!-- Checkbox -->
    <rect x="0" y="50" width="20" height="20" fill="white" stroke="#d1d5db" stroke-width="2" rx="3"/>
    <text x="30" y="66" font-family="Arial, sans-serif" font-size="16" fill="#4b5563">why need</text>
  </g>
  
  <!-- Deliverables Section -->
  <g transform="translate(40, 370)">
    <!-- Package Icon -->
    <rect x="4" y="8" width="32" height="24" fill="none" stroke="#8b5cf6" stroke-width="2.5" rx="2"/>
    <line x1="4" y1="20" x2="36" y2="20" stroke="#8b5cf6" stroke-width="2.5"/>
    <line x1="20" y1="8" x2="20" y2="32" stroke="#8b5cf6" stroke-width="2.5"/>
    <polyline points="12,8 20,2 28,8" fill="none" stroke="#8b5cf6" stroke-width="2.5"/>
    
    <text x="50" y="22" font-family="Arial, sans-serif" font-size="20" font-weight="bold" fill="#1f2937">Deliverables</text>
    <text x="0" y="60" font-family="Arial, sans-serif" font-size="16" fill="#4b5563">none why</text>
  </g>
  
  <!-- Evaluation Criteria Section -->
  <g transform="translate(40, 470)">
    <!-- Scale Icon -->
    <path d="M 20 5 L 10 25 L 30 25 Z" fill="#ef4444" opacity="0.8"/>
    <path d="M 20 5 L 30 25 L 10 25 Z" fill="#ef4444" opacity="0.4"/>
    <rect x="18" y="25" width="4" height="10" fill="#6b7280"/>
    <rect x="10" y="35" width="20" height="3" fill="#6b7280"/>
    
    <text x="50" y="22" font-family="Arial, sans-serif" font-size="20" font-weight="bold" fill="#1f2937">Evaluation Criteria</text>
    <text x="0" y="60" font-family="Arial, sans-serif" font-size="16" fill="#4b5563">doen</text>
  </g>
  
  <!-- How to Submit Section -->
  <g transform="translate(40, 570)">
    <!-- Rocket Icon -->
    <path d="M 15 35 L 20 10 L 25 35 Z" fill="#f59e0b"/>
    <ellipse cx="20" cy="35" rx="6" ry="3" fill="#dc2626"/>
    <circle cx="20" cy="20" r="3" fill="#fef3c7"/>
    <path d="M 12 25 L 8 30 L 12 28 Z" fill="#f59e0b"/>
    <path d="M 28 25 L 32 30 L 28 28 Z" fill="#f59e0b"/>
    
    <text x="50" y="22" font-family="Arial, sans-serif" font-size="20" font-weight="bold" fill="#1f2937">How to Submit</text>
    
    <text x="0" y="60" font-family="Arial, sans-serif" font-size="15" font-weight="600" fill="#374151">1. Clone</text>
    <text x="0" y="80" font-family="Arial, sans-serif" font-size="14" fill="#6b7280">   this repository to your local machine.</text>
    
    <text x="0" y="110" font-family="Arial, sans-serif" font-size="15" font-weight="600" fill="#374151">2. Implement</text>
    <text x="0" y="130" font-family="Arial, sans-serif" font-size="14" fill="#6b7280">   the required features.</text>
    
    <text x="0" y="160" font-family="Arial, sans-serif" font-size="15" font-weight="600" fill="#374151">3. Commit</text>
    <text x="0" y="180" font-family="Arial, sans-serif" font-size="14" fill="#6b7280">   your changes with meaningful messages.</text>
    
    <text x="0" y="210" font-family="Arial, sans-serif" font-size="15" font-weight="600" fill="#374151">4. Push</text>
    <text x="0" y="230" font-family="Arial, sans-serif" font-size="14" fill="#6b7280">   your code to the main branch.</text>
    
    <text x="0" y="260" font-family="Arial, sans-serif" font-size="15" font-weight="600" fill="#374151">5. Submit</text>
    <text x="0" y="280" font-family="Arial, sans-serif" font-size="14" fill="#6b7280">   the repository link on the Meta LMS platform.</text>
  </g>
  
  <!-- Footer -->
  <line x1="40" y1="870" x2="760" y2="870" stroke="#e5e7eb" stroke-width="2"/>
  <text x="400" y="892" font-family="Arial, sans-serif" font-size="12" fill="#9ca3af" text-anchor="middle">Generated automatically by Meta LMS — Empowering Developers</text>
</svg>
