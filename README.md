A sleek, responsive, single-page application (SPA) acting as a comprehensive mathematics study guide. Built with a futuristic dark theme, it features dynamic fuzzy searching, smooth section navigation, and fully-rendered LaTeX math equations using MathJax.


✨ Features⚡ Real-Time Fuzzy Search: Instantly filter formula cards and whole sections by topics, keywords, or theorem names (e.g., "AM-GM", "Euler", "CRT").📐 Beautiful Math Typesetting: Fully supports complex mathematical notation, formulas, and inline variables rendered crystal-clear via MathJax 3. Responsive & Fluid Layout: Mobile-friendly design featuring a sliding toggle sidebar, overlay menu, and CSS grid fallback. Interactive Sidebar: Dynamic Intersection Observer updates active states on the sidebar navigation as you scroll through topics. Tech StackFrontend: Semantic HTML5, Vanilla JavaScript (ES6+)Styling: Modern CSS3 with custom CSS Variables (:root), Flexbox, and CSS GridMath Rendering: MathJax v3 (SVG output)Typography: Inter (prose) and JetBrains Mono (formula blocks)📂 Project StructureBash├── index.html   # Main markup, search logic, and responsive menu behaviors
styles.css   # Global variables, layout grid, cards, and dark theme palette



📚 Topics Covered: SectionKey Concepts & TheoremsGeometry & Number TheoryArea ratios, Fermat's Little Theorem (FLT), Euler's Totient Theorem (ETT)Trigonometry & Graph TheoryLaws of Sines/Cosines, Eulerian Paths & Cycles, Chinese Remainder Theorem (CRT)Analytic & Complex GeometryPoint-to-line distance, Shoelace Formula, Roots of Unity, Cyclotomic PolynomialsSystems & InequalitiesVieta's formulas, Generating Functions, Weighted AM-GM, Cauchy-SchwarzAdvanced Counting & GroupsRoots of Unity filter, Burnside's Lemma, Group Axioms, Chicken McNugget Theorem, LTE
