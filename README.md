# CSE 185 Pipeline Map

A left-to-right map of the dry-lab pipeline taught in CSE 185 (UCSD,
Advanced Bioinformatics Lab). Each box is a step; the pills on the
lines are the file formats that pass between them. Click a box for
the step's goal, inputs/outputs, and tools; click a pill for what
the file holds and a sample snippet. Pan with click-drag, zoom with
wheel or trackpad. Scope is Labs 1–9 (assembly, mapping,
consensus/variants, MSA, phylogeny, tree dating, molecular
clustering, RNA-seq) plus NGS as the upstream anchor. The RNA-seq
branch runs end-to-end into a standard downstream pipeline (counting
→ normalization → QC → differential expression → enrichment); nodes
past the labs are marked "beyond the CSE 185 labs" in their details.

Open it at <https://ayjz.github.io/cse185-map/>.

## Data

Everything on the map comes from `data/pipeline.yaml` — that file is
the single source of truth. To add a step or tool, edit the YAML; the
schema is documented at the top of the file.

Vanilla HTML / JS / SVG. js-yaml from a CDN. No build step.
