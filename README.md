🏙️ Living 3D City (Pure CSS)

Just a late-night experiment to see how far I could push modern CSS. It’s a fully interactive 3D city block built in a single HTML file—zero JavaScript, zero SVGs, zero images.
🛠 The "How-To"

    Isometric View: Manual rotateX(60deg) rotateZ(45deg) on the container. No heavy libraries here.

    1-Div Buildings: Each building is just one <div>. I used ::before and ::after for the walls and CSS gradients to proceduraly generate the windows.

    No-JS Toggle: Used the classic Checkbox Hack (input:checked ~ .scene) to swap CSS variables for Day/Night modes.

    Animations: Traffic and hover effects are handled entirely via @keyframes and transition on the Z-axis.

 Quick Start

    Download 3d_city.html.

    Open it in a browser.

    That’s it.

🎨 Themes

    Solarpunk: Default day mode.

    Cyberpunk: Hit the checkbox to toggle the neon night glow.
    
was a bit stressful (took me all day LOL)

Want me to help you draft a "Known Issues" or "Browser Support" section (like why Firefox handles 3D transforms differently than Chrome)?
