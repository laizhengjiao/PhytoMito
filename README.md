<div align="center">

<img width="180" alt="PhytoMito logo" src="https://github.com/user-attachments/assets/1bf8fc1f-d2e2-4519-ba7f-b666161e7bd4" />

# *PhytoMito*

### <font color="#2c7a3f">Plant Organelle Genome & Synteny Toolkit</font>

</div>

---

**PhytoMito** is a desktop platform for comprehensive analysis of plant organelle genomes, with a particular focus on **plant mitochondrial and chloroplast genomes**. It integrates multiple analytical modules into a unified graphical interface, enabling researchers to perform multi-dimensional genomic analyses without command-line expertise.

Plant mitochondrial genomes are among the largest and most structurally complex organelle genomes in the plant kingdom, often harboring extensive repetitive content that drives genome recombination and structural rearrangement. PhytoMito provides an accessible, integrated solution for characterizing these features, supporting downstream studies in genome annotation, comparative genomics, and evolutionary biology.

## <font color="#2c7a3f">✦ Core Features</font>

**Circular Linker Map** — Visualizes structural relationships and synteny between Mitochondrial (MT) and Chloroplast (CP) genomes. It uses an integrated BLASTN engine to map cross-organelle insertions and generates highly customizable, publication-ready circular plots.

**Linear Multi-FASTA Synteny** — Performs multi-species linear synteny analysis. Users can input multiple FASTA files, automatically run pair-wise BLAST alignments, and generate linear synteny track visualizations with customizable blocks and link curves.

**GeSeq Annotation Integration** — Provides direct, seamless access to the GeSeq web server (via embedded PyWebView or system browser) for rapid and highly accurate organellar genome annotation.

**Genome Composition Analysis** — Computes base composition (A/T/G/C%) and AT/GC skews. Automatically extracts and calculates statistics for the whole genome as well as specific functional regions (CDS, tRNA, rRNA).

**Comprehensive Repeats Analysis** — Provides a three-in-one suite for repeat detection, essential for understanding genome recombination:
* **SSR Analysis:** Detects microsatellites (1–6 bp motifs) via MISA with customizable repeat thresholds and interactive nested donut chart visualization.
* **Tandem Repeats:** Identifies tandem repeats via TRF and renders a genome-wide AT content track map for both circular and linear topologies.
* **Dispersed Repeats:** Locates direct and inverted dispersed repeats via ROUSFinder, classifying forward/reverse repeats with customizable length and scoring parameters.

**RSCU & AA Usage** — Calculates Relative Synonymous Codon Usage (RSCU) and Amino Acid (AA) frequencies directly from annotated GenBank files. Supports standard and alternative genetic codes, generating detailed stacked bar plots and frequency charts.

**Ka/Ks Evolutionary Analysis** — Automates evolutionary rate calculations. Integrates a MACSE alignment pipeline and KaKs_Calculator (supporting methods like MA, NG, YN, LWL, etc.) to compute non-synonymous/synonymous substitution rates, generating highly customizable boxplot visualizations per gene.

## <font color="#2c7a3f">✦ Input & Compatibility</font>

* **Supported Input Formats:** * **GenBank (`.gb`, `.gbk`):** Required for Genome Composition and RSCU/AA Usage modules.
    * **FASTA (`.fa`, `.fasta`):** Required for Linear Synteny, Circular Maps, Repeats (SSR/TRF/Dispersed), and Ka/Ks analyses.
* **Cross-platform Execution:** Built on Python 3 (`tkinter`, `matplotlib`, `biopython`, `pandas`).
* **Embedded Dependencies:** Seamlessly bundles backend bioinformatics tools including BLAST+, TRF, MISA (Perl), ROUSFinder, MACSE (Java), and KaKs_Calculator to eliminate complex environment configuration for users.

## <font color="#2c7a3f">✦ Output & Export</font>

* **Publication-Ready Graphics:** Export high-resolution plots in raster (PNG) and vector (PDF, SVG) formats with full DPI control (up to 900 DPI).
* **Tabular Data:** One-click export of analysis tables and BLAST hit results to Excel (`.xlsx`) or CSV formats.
* **Batch Export:** Automatically packages analysis tables and corresponding visualization plots into structured `.zip` archives for easy sharing and reporting.
