Anupama Singh · Personal Website

Live site: anupama1395.github.io

Personal research website of Anupama Singh, a Machine Learning Engineer working in applied ML, computer vision and NLP, and an M.S. Computer Science student at California State Polytechnic University, Pomona (expected December 2026).

The site presents my research, publications, projects, experience, technical skills and education in one place.

Contents
Section	What it covers
Overview	Role, current position, research focus, publication and contact links
Research	Real-time strawberry plant health detection from UAV imagery and proximal sensor data, with an interactive precision–recall demo
Publications & Research	SPIE 2026 paper; lunar landing site and terrain hazard analysis; synthetic clinical data generation across 27 MIMIC-III tables
AI Projects	Retrieval-augmented question answering; minLLaMA transformer language model; public repositories
Experience	Research roles at Cal Poly Pomona and the AI & MLX Lab; industry roles at FreightCrate, Goal Teller and BYJU'S
Technical Skills	Languages, ML, computer vision, deployment, NLP and cloud, evaluation and data synthesis
Education & Service	M.S. Computer Science, M.B.A. Marketing, B.Sc. Information Technology; teaching and service
Publication

Singh, A., Bhandari, S., Raheja, A., & Kosaraju, S. C. Deep learning models with a hierarchical method using RGB images from UAV and proximal sensor data for real-time detection of strawberry plant health. Proceedings of SPIE, Vol. 14045, June 2026. DOI: 10.1117/12.3095124

Interactive features
3D Transformer background. A WebGL particle scene (about 22,000 particles) shows token embeddings, five stacked layers, self-attention arcs, positional encoding and a softmax readout. Signals flow upward through the attention connections.
Forward pass on click. Clicking the opening section sends a wave of signals from the input tokens through every layer.
Morphing scene. As you scroll, the particles move from the Transformer into a strawberry plant inside a 3D detection box, and then into a spiral galaxy at the contact section.
Detection threshold demo. A simulated drone sweep over a field grid, with a threshold slider showing how flagged plants, missed plants and false alarms trade off.
Scroll interactions. Section reveals, a progress bar, side navigation, an animated experience timeline, and expandable abstracts and responsibilities.
Technology
Single self-contained index.html file: HTML, CSS and JavaScript, with no build step
three.js r160 for the WebGL particle scene, loaded from cdnjs
Fonts from Google Fonts: Instrument Serif, Space Grotesk and JetBrains Mono
Hosted on GitHub Pages
Responsive layout for desktop and mobile; honours the system "reduce motion" setting
Repository structure
.
├── index.html   # the entire website
└── README.md
Running locally

Clone the repository and open index.html in a browser:

bash
git clone https://github.com/Anupama1395/Anupama1395.github.io.git
cd Anupama1395.github.io
open index.html          # macOS
# or start a local server:
python3 -m http.server 8000   # then visit http://localhost:8000

An internet connection is needed for the fonts and three.js to load.

Updating the site
Edit index.html. All text content sits in the HTML between <main> and </main>.
Commit and push to the main branch, or use Add file → Upload files on GitHub.
GitHub Pages republishes automatically within a few minutes.
Acknowledgements

The layout and interaction style were inspired by Jingwei Zuo's personal site. All code and content in this repository were written for this site.

Contact
Website: anupama1395.github.io
LinkedIn: linkedin.com/in/anupama-singh
GitHub: github.com/Anupama1395
Email: anupamasingh47 [at] gmail [dot] com

© 2026 Anupama Singh. All rights reserved.
