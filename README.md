The Noble Quran - Kinetic Timeline Experience

A sophisticated, single-page interactive experience that visualizes the summary of all 114 Surahs of the Quran. This project features a dual-view timeline allowing users to explore the Surahs in both their chronological Revelation order and the traditional Mushaf order, wrapped in a deep "Midnight & Gold" aesthetic.

✨ Features

Dual-Mode Timeline:

Revelation Mode: Sorts Surahs chronologically based on the standard Egyptian chronology (Al-Alaq first).

Mushaf Mode: Sorts Surahs in the traditional compiled order (Al-Fatiha to An-Nas).

Kinetic Typography & Scrolling:

Powered by Lenis for buttery smooth inertia scrolling.

GSAP ScrollTrigger integration for velocity-based animations and parallax effects.

Auto-Pilot Mode: A smooth auto-scroll feature allowing for a hands-free reading experience.

Dynamic Asset Generation:

OG Image Generator: Instantly renders a downloadable social media poster using the HTML5 Canvas API based on the current view.

Dynamic Favicon: Generates an SVG favicon on the fly.

Responsive Design: A central timeline axis that adapts gracefully from desktop (alternating split view) to mobile (stacked view).

Zero-Build: Completely self-contained in a single index.html file.

🛠️ Tech Stack

Core: HTML5, JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

Animation: GSAP + ScrollTrigger

Smooth Scroll: Lenis

Fonts: Google Fonts (Cinzel, Inter, Amiri)

🚀 Usage

Download: Save the index.html file to your local machine.

Run: Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).

Interact:

Scroll: Use your mouse wheel or trackpad.

Toggle View: Use the switch in the bottom-right corner to change between "Revelation" and "Mushaf".

Auto Scroll: Click the play button (bottom-right) to start/stop auto-scrolling.

Download Poster: Click "Download Poster" in the top navigation to generate a PNG cover art of the current timeline state.

📂 Project Structure

The project is a Single File Application.

CSS: Contains custom keyframes for noise overlays, glassmorphism (.card-glass), and kinetic typography.

Data: The surahsDB array contains the metadata (Number, Name, Meaning, Summary) for all 114 chapters.

Logic: The renderTimeline() function handles sorting and DOM injection, while initAnimations() handles the GSAP triggers.

🎨 Customization

To modify the content, open index.html in a code editor:

Edit Summaries: Locate the const surahsDB = [...] array (~line 200).

Change Colors: Modify the CSS variables in the <style> block (--bg-color, --gold, etc.).

Adjust Speed: Change duration in the Lenis configuration or the pixel value in window.scrollBy(0, 2) within the autoScrollLoop.

📄 License

Open source. Feel free to use, modify, and distribute for educational or personal projects.
