# Describe the purpose and structure of HTML and CSS in building basic webpages.
## Purpose: Boba milk tea shop webpage
This is a homepage of a boba milk shop "Boba"
## Structure of HTML and CSS:
1. Head: link to eacy section of home page and new webpage of menu
   
2. Boba intro : image with our shop mission, sering great boba.<br>
CSS style: padding / grid with flex<br>
   a. section: Hero<br>
   link of **[phone call]**  **[menu]** **[map]**<p>
   `.hero { padding: 64px 0 34px; }
.hero-inner { display:grid; grid-template-columns: 1.1fr 0.9fr; gap: 30px; align-items: center; }
.hero h1 { font-family: Poppins, Inter, system-ui; font-size: clamp(2rem, 3.6vw + 1rem, 3.4rem); line-height: 1.05; margin: 0 0 12px; }
.hero p { font-size: clamp(1rem, 1vw + .8rem, 1.15rem); color: var(--muted); margin: 0 0 22px; }
.btns { display:flex; gap: 12px; flex-wrap: wrap; }
.btn-outline { border: 2px solid color-mix(in oklab, var(--ink), transparent 70%); padding: 10px 14px; border-radius: 12px; text-decoration:none; font-weight: 700; }
`</p>
  b. section: Sections<br><p>
  `section { padding: 60px 0; }
.section-title { font-family: Poppins, Inter, system-ui; font-size: clamp(1.4rem, 1.8vw + .9rem, 2rem); margin: 0 0 14px; }
.section-lead { color: var(--muted); margin: 0 0 22px; }`</p>
c.section: Specials<br><p>
`.features { display:grid; grid-template-columns: repeat(3, 1fr); gap: 18px; }
.feature { background: var(--card); padding: 18px; border-radius: var(--radius); box-shadow: var(--shadow); display:grid; grid-template-columns: 56px 1fr; gap: 14px; align-items:center; }
.feature i { display:grid; place-items:center; width:56px; height:56px; border-radius: 14px; background: color-mix(in oklab, var(--brand), transparent 80%); }`</p>
d.section: Location<br><p>
`.location { display:grid; grid-template-columns: 1.2fr .8fr; gap: 20px; align-items: start; }
.card { background: var(--card); border-radius: var(--radius); padding: 18px; box-shadow: var(--shadow); }
.hours { margin: 0; padding: 0; list-style: none; display:grid; grid-template-columns: 1fr 1fr; gap:10px; }
.hours li { display:flex; justify-content: space-between; gap: 8px; }
.hours-title { margin-top: 0; }`</p>
e.section: Footer<br><p>
`footer { padding: 36px 0; border-top: 1px solid color-mix(in oklab, var(--muted), transparent 70%); }
.footer-title { margin: 0 0 6px; }`</p>
## Responsive Webpage:<br>
   `@media (max-width: 920px) {
  .hero-inner { grid-template-columns: 1fr; }
  .features { grid-template-columns: 1fr 1fr; }
  .location { grid-template-columns: 1fr; }
}
@media (max-width: 620px) {
  nav a { margin-left: 12px; }
  .features { grid-template-columns: 1fr; }
  .menu-grid { grid-template-columns: 1fr; }
  .hours { grid-template-columns: 1fr; }
}
`
# Construct simple web pages using HTML to create content and CSS to style it.
URL:
