---
title: Fangwen Zhao
---

<style>
:root{
  --fg:#1f2937;         /* slate-800 */
  --muted:#6b7280;      /* slate-500 */
  --accent:#0f766e;     /* teal-700 */
  --bg:#ffffff;
  --panel:#f8fafc;      /* slate-50 */
  --border:#e5e7eb;     /* gray-200 */
  --codebg:#0b1020;
}

.page-wrap{
  max-width: 1040px;
  margin: 0 auto;
  padding: 1.75rem 1rem 2.5rem;
  color: var(--fg);
}

.header{
  display:flex;
  flex-wrap:wrap;
  align-items:baseline;
  justify-content:space-between;
  gap: .75rem;
  padding-bottom: .75rem;
  border-bottom: 1px solid var(--border);
  margin-bottom: 1.25rem;
}

.name{
  font-size: 2.0rem;
  line-height: 1.1;
  margin: 0;
  letter-spacing: .2px;
}
.tagline{
  margin: .15rem 0 0;
  color: var(--muted);
  font-size: 1.0rem;
}

.meta{
  text-align:right;
  color: var(--muted);
  font-size: .95rem;
  min-width: 240px;
}
.meta a{ color: var(--accent); text-decoration:none; }
.meta a:hover{ text-decoration:underline; }

.grid{
  display:grid;
  grid-template-columns: 1.55fr .85fr; /* main / side */
  gap: 1.25rem;
}
@media (max-width: 900px){
  .grid{ grid-template-columns: 1fr; }
  .meta{ text-align:left; }
}

.card{
  background: var(--bg);
  border: 1px solid var(--border);
  border-radius: 14px;
  padding: 1rem 1.05rem;
}
.side{
  background: var(--panel);
}

h2{
  font-size: 1.05rem;
  margin: 0 0 .6rem;
  padding-bottom: .35rem;
  border-bottom: 1px solid var(--border);
  letter-spacing: .2px;
}
h3{
  font-size: .98rem;
  margin: 1rem 0 .35rem;
}
p{ margin: .5rem 0; color: var(--fg); }
.muted{ color: var(--muted); }

.badges{
  display:flex;
  flex-wrap:wrap;
  gap: .45rem;
  margin-top: .45rem;
}
.badge{
  display:inline-block;
  padding: .22rem .5rem;
  border-radius: 999px;
  border: 1px solid var(--border);
  background: #fff;
  font-size: .86rem;
  color: #111827;
}
.badge strong{ color: var(--accent); font-weight: 600; }

ul{
  margin: .45rem 0 .15rem 1.05rem;
  padding: 0;
}
li{ margin: .25rem 0; }

.kwd{
  font-weight: 650;
  color: var(--accent);
}

.pub{
  margin: .55rem 0;
}
.pub .title{ font-weight: 650; }
.pub .venue{ color: var(--muted); }
.pub .authors{ color: var(--muted); font-size: .95rem; }

.hr{
  height: 1px;
  background: var(--border);
  border: 0;
  margin: .9rem 0;
}

.small{
  font-size: .92rem;
  color: var(--muted);
}
</style>

<div class="page-wrap">

  <div class="header">
    <div>
      <h1 class="name">Fangwen Zhao</h1>
      <div class="tagline">
        <span class="kwd">Systems immunology</span> ·
        <span class="kwd">Immune disease states</span> ·
        <span class="kwd">Biomedical data science</span> ·
        <span class="kwd">Computational biology</span>
      </div>
    </div>

    <div class="meta">
      <!-- Replace placeholders as you like -->
      <div><a href="https://github.com/YOUR_GITHUB_USERNAME">GitHub</a> · <a href="https://www.linkedin.com/in/YOUR_LINKEDIN/">LinkedIn</a></div>
      <div><a href="mailto:YOUR_EMAIL">YOUR_EMAIL</a></div>
      <div class="small">Vienna, Austria</div>
    </div>
  </div>

  <div class="grid">

    <!-- MAIN COLUMN -->
    <div class="card">

      <h2>About</h2>
      <p>
        I am a <strong>data-capable immunologist</strong> passionate about leveraging
        <strong>-omics data</strong> to unravel the complexity of <strong>immune-relevant disease states</strong>.
        During my PhD, I paired an immunology foundation with strong bioinformatics practice to become a
        <strong>full-fledged bioinformatician</strong> focused on systematic disease biology.
      </p>

      <h3>Current focus</h3>
      <ul>
        <li><strong>Systematic characterization</strong> of <span class="kwd">epigenetic dysregulation</span> in <strong>rare monogenic inborn errors of immunity</strong>.</li>
        <li>Led end-to-end project execution: <strong>cohort assembly</strong>, <strong>wet-lab</strong>, <strong>funding</strong>, and <strong>analysis/data integration</strong>.</li>
        <li>Additional contributions across <strong>bioinformatics</strong>, <strong>cancer epigenomics</strong>, and <strong>rare disease cohorts</strong>.</li>
      </ul>

      <hr class="hr" />

      <h2>Selected publications</h2>

      <div class="pub">
        <div class="title">Chromatin mapping uncovers convergent epigenetic dysregulation underlying diverse monogenic inborn errors of immunity</div>
        <div class="venue">In preparation for resubmission</div>
        <div class="authors">Zhao F, Imrichova H*, Bal SK*, … Bock C.</div>
      </div>

      <div class="pub">
        <div class="title">MrBiomics: Modules &amp; Recipes Augment Bioinformatics for Multi-Omic Analyses</div>
        <div class="venue">In preparation</div>
        <div class="authors">Reichl S*, Bednarsky R*, … Zhao F, … Bock C.</div>
      </div>

      <div class="pub">
        <div class="title">Multi-omics analysis of naïve B cells of patients harboring the C104R mutation in TACI</div>
        <div class="venue">Frontiers in Immunology · Aug 2022</div>
        <div class="authors">Ramirez N, … Zhao F, …</div>
      </div>

      <div class="pub">
        <div class="title">Chromatin mapping and single-cell immune profiling define the temporal dynamics of ibrutinib response in CLL</div>
        <div class="venue">Nature Communications · Jan 2020</div>
        <div class="authors">Rendeiro AF, … Zhao F, … Bock C.</div>
      </div>

      <p class="small muted">
        Tip: link titles to DOI/preprints once available.
      </p>

      <hr class="hr" />

      <h2>Talks &amp; posters</h2>
      <h3>Oral talks</h3>
      <ul>
        <li><strong>Keystone Symposium for Systems Immunology &amp; Immunoengineering</strong>, Vancouver (2026)</li>
        <li>EMBL PhD Symposium – Zooming into life, Virtual (2021)</li>
        <li>The Meeting of the European Society for Immunodeficiencies, Edinburgh (2017)</li>
      </ul>

      <h3>Poster presentations</h3>
      <ul>
        <li>Harald von Boehmer Midwinter Conference – Advances in Immunobiology, Seefeld in Tirol (2026)</li>
        <li>The Biology of Genomes, Cold Spring Harbor (2022)</li>
        <li>Summer Symposium Systems Immunology, Würzburg (2022)</li>
        <li>The Meeting of the European Society for Immunodeficiencies, Lisbon (2018)</li>
      </ul>

      <hr class="hr" />

      <h2>Funding, awards</h2>

      <h3>Grant acquisition</h3>
      <ul>
        <li>
          <strong>Integrative Multi-Omics Analysis of Primary Antibody Deficiency (PAD) Patients</strong>
          for stratification by cellular pathways
          <div class="small">ERA-NET E-RARE 2018 (awarded to Dr. Christoph Bock + consortium); major contributions to direction, grant writing, and initial results</div>
        </li>
      </ul>

      <h3>Awards</h3>
      <div class="badges">
        <span class="badge"><strong>Keystone</strong> Future of Science (2026)</span>
        <span class="badge">UBC Chancellor’s Scholar (2016)</span>
        <span class="badge">SURE Award (2015)</span>
        <span class="badge">NSERC USRA (2014)</span>
        <span class="badge">Dean’s Honour Roll (2012)</span>
        <span class="badge">SFU Alumni Scholarship (2011)</span>
      </div>

    </div>

    <!-- SIDE COLUMN -->
    <aside class="card side">
      <h2>Skills</h2>

      <h3>Computational</h3>
      <ul>
        <li><strong>Python</strong>, <strong>R</strong>, Bash</li>
        <li><strong>Snakemake</strong>, Conda, VS Code, Copilot</li>
        <li>Git / GitHub</li>
      </ul>

      <h3>Systems</h3>
      <ul>
        <li>Slurm HPC</li>
        <li>Linux, macOS, Windows</li>
      </ul>

      <h3>NGS &amp; -omics</h3>
      <ul>
        <li><strong>bulk ATAC-seq</strong>, <strong>bulk RNA-seq</strong></li>
        <li><strong>scRNA-seq</strong></li>
        <li>NGS library preparation</li>
      </ul>

      <h3>Experimental</h3>
      <ul>
        <li>Flow cytometry &amp; cell sorting</li>
        <li>Cell culture</li>
        <li>Basic lab techniques</li>
      </ul>

      <h3>Software</h3>
      <ul>
        <li>FlowJo</li>
        <li>Cytoscape</li>
        <li>Inkscape</li>
        <li>MS Office Suite</li>
      </ul>

      <h3>Research &amp; people</h3>
      <ul>
        <li><strong>Story-telling</strong>, <strong>visual design</strong></li>
        <li><strong>Grant writing</strong>, recruitment</li>
        <li>Mentorship, collaboration</li>
        <li>Public speaking, event organization</li>
        <li>Project management, troubleshooting</li>
      </ul>
    </aside>

  </div>

  <p class="small muted" style="margin-top:1rem;">
    (This page intentionally omits a full education/career timeline.)
  </p>

</div>
