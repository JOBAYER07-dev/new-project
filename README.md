Project Overview

The Bodyshape Landing Page is a sleek, responsive fitness website built using HTML and Tailwind CSS. It’s crafted to inspire users toward a healthier lifestyle through a modern dark interface accented with vibrant orange tones. 
The design emphasizes visual energy and motivation, creating a premium feel that aligns with modern fitness brands. The page features multiple interactive sections, including a hero banner, fitness program highlights, subscription plans, trainer showcase, benefits section, and a professional footer. Each element is structured with reusable Tailwind components, ensuring clean responsiveness across devices.

Technologies Used:

HTML
Tailwind CSS
Font Awesome
GitHub Pages

Problem & Solution:

While developing the hero banner, the background image loaded correctly in the local environment; however, it failed after deployment on GitHub Pages. This issue occurred due to incorrect relative path handling in Tailwind’s bg-[url()] utility.
To resolve this, the background image was defined using external CSS with relative paths, ensuring proper rendering both locally and on the live server. This fix enhanced deployment stability and maintained the responsive design integrity.

Result:

The final website successfully delivers a visually striking, mobile-friendly fitness landing page that combines clean UI with smooth functionality — ideal for promoting fitness programs, showcasing trainers, and attracting new members.
