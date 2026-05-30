<div align="center">
  <table border="0" cellpadding="0" cellspacing="0">
    <tr>
      <td>
        <img width="180" alt="PhytoMito logo" src="https://github.com/user-attachments/assets/1bf8fc1f-d2e2-4519-ba7f-b666161e7bd4" />
      </td>
      <td valign="middle" align="left" style="padding-left: 20px;">
        <h1><i>PhytoMito</i></h1>
        <p><b>Plant Organelle Genome Analysis Platform</b></p>
      </td>
    </tr>
  </table>
</div>

---

**PhytoMito** is a desktop platform for comprehensive analysis of plant organelle genomes, with a particular focus on **plant mitochondrial genomes**. It integrates multiple analytical modules into a unified graphical interface, enabling researchers to perform multi-dimensional genomic analyses without command-line expertise.

Plant mitochondrial genomes are among the largest and most structurally complex organelle genomes in the plant kingdom, often harboring extensive repetitive content that drives genome recombination and structural rearrangement. PhytoMito provides an accessible, integrated solution for characterizing these features, supporting downstream studies in genome assembly, comparative genomics, and evolutionary biology.

## Features

| Module | Tool | Description |
|--------|------|-------------|
| 🔁 SSR Analysis | MISA | Detects microsatellites (1–6 bp motifs) with customizable thresholds and interactive visualization |
| 🔀 Tandem Repeats | TRF | Identifies tandem repeats and renders a genome-wide AT content map |
| 🔄 Dispersed Repeats | ROUSFinder + BLASTN | Locates direct and inverted dispersed repeats, key drivers of mitogenome recombination |

## Input & Compatibility

- Accepts **FASTA** and **GenBank** format input
- Supports both **circular** and **linear** genome topologies
- Designed for plant **mitochondrial** and **chloroplast** genomes
- All computations run **locally** — no internet connection required

## Dependencies

`Python 3` · `Perl` · `MISA` · `TRF` · `BLASTN` · `ROUSFinder` · `Biopython` · `Matplotlib` · `BeautifulSoup4`
