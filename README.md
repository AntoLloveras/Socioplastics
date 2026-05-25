# Socioplastics — Complete Corpus

## Transdisciplinary Urban Theory and Epistemic Infrastructure  
### Tomes I–IV · Nodes 0001–4000 · Books 01–40 · Chapters 001–400

Anto Lloveras · LAPIEZA-LAB, Madrid, Spain · ORCID 0009-0009-9820-3319  
Version v1.0.0 · 2026 · License CC BY-NC-SA 4.0  
Canonical Interface: https://antolloveras.blogspot.com

---

## Overview

**Socioplastics** is a transdisciplinary urban theory, artistic research corpus, and epistemic infrastructure developed by Anto Lloveras through LAPIEZA-LAB. It converts long-duration relational, architectural, curatorial, pedagogical, editorial, and urban practice into a structured knowledge corpus that is readable by humans, machines, archives, repositories, and future research systems.

The corpus is organised as a scalar architecture:

**Node → Chapter → Book → Tome → Corpus**

Each node is a discrete conceptual unit. Ten nodes form a chapter. One hundred nodes form a book. Ten books form a tome. Four tomes form the current 4000-node corpus.

---

## Corpus Structure

| Tome | Stratum | Nodes | Books | Chapters | Main File |
|------|---------|-------|-------|----------|-----------|
| I | Foundational Stratum | 0001–1000 | 01–10 | 001–100 | `socioplastics-tome-I-foundational-stratum.txt` |
| II | Developmental Stratum | 1001–2000 | 11–20 | 101–200 | `socioplastics-tome-II-developmental-stratum.txt` |
| III | Expansive Stratum | 2001–3000 | 21–30 | 201–300 | `socioplastics-tome-III.txt` |
| IV | Consolidation Stratum | 3001–4000 | 31–40 | 301–400 | `socioplastics-tome-IV-consolidation-stratum.txt` |

---

## Tome Descriptions

### Tome I — Foundational Stratum

Tome I establishes the foundational architecture of Socioplastics: epistemic architecture, field formation, systemic protocols, urban registers, conceptual operators, material inscription, territorial systems, media theory, morphogenesis, and synthetic infrastructure. It closes at Node 1000 with the installation of the stratigraphic field.

### Tome II — Developmental Stratum

Tome II develops the foundational stratum into a mature, self-expanding field. It extends the corpus through linguistic hardening, epistemological cores, systems dynamics, decalogue protocols, conceptual art registers, urban theory extensions, media ecologies, morphogenetic operators, and field consolidation. It closes at Node 2000 as a terminal seal.

### Tome III — Expansive Stratum

Tome III turns the corpus outward. It develops legibility infrastructure, distributed inscription, public interface, territorial practice, corpus governance, DOI anchoring, and operational expansion. It makes the corpus navigable, citable, indexable, and accessible to readers who did not build it.

### Tome IV — Consolidation Stratum

Tome IV consolidates the four-thousand-node corpus as a citable transdisciplinary knowledge infrastructure. It moves from soft ontology to diagonal reading through archival metabolism, bibliographic infrastructure, filmed bodies, lexical reassembly, field organism, scalar grammar, and citational commitment.

---

## Files

### Canonical TXT Files

These are the principal human-readable and machine-auditable documents:

- `socioplastics-tome-I-foundational-stratum.txt`
- `socioplastics-tome-II-developmental-stratum.txt`
- `socioplastics-tome-III.txt`
- `socioplastics-tome-IV-consolidation-stratum.txt`

### JSONL Files

JSON Lines files for machine reading, indexing, dataset upload, retrieval systems, and AI workflows:

- `socioplastics-tome-1.jsonl`
- `socioplastics-tome-2.jsonl`
- `socioplastics-tome-3.jsonl`
- `socioplastics-tome-4.jsonl`
- `socioplastics-complete-corpus-0001-4000.jsonl`

### JSON Files

Array-based JSON files for APIs, repositories, static sites, metadata systems, and browser-based use:

- `socioplastics-tome-1.json`
- `socioplastics-tome-2.json`
- `socioplastics-tome-3.json`
- `socioplastics-tome-4.json`
- `socioplastics-complete-corpus-0001-4000.json`
- `socioplastics-corpus-metadata.json`

### Index Files

Recommended index files:

- `INDEX-corpus.txt`
- `INDEX-tomes-books-chapters.txt`
- `INDEX-chapters-nodes.txt`
- `INDEX-nodes.txt`

---

## Platform Use

### GitHub

Use this file as the root `README.md` of the repository. Place the four tome TXT files, JSON/JSONL files, and index files in the same repository or in folders by tome.

Recommended repository structure:

```text
socioplastics-corpus/
├── README.md
├── socioplastics-tome-I-foundational-stratum.txt
├── socioplastics-tome-II-developmental-stratum.txt
├── socioplastics-tome-III.txt
├── socioplastics-tome-IV-consolidation-stratum.txt
├── socioplastics-tome-1.jsonl
├── socioplastics-tome-2.jsonl
├── socioplastics-tome-3.jsonl
├── socioplastics-tome-4.jsonl
├── socioplastics-complete-corpus-0001-4000.jsonl
├── socioplastics-corpus-metadata.json
└── indexes/
```

### Hugging Face

Use this file as the dataset card `README.md`. Upload the TXT, JSONL, JSON, and metadata files. The JSONL files are the most useful format for dataset workflows.

Suggested tags:

- `socioplastics`
- `urban-theory`
- `digital-humanities`
- `knowledge-infrastructure`
- `conceptual-art`
- `architecture`
- `transdisciplinarity`
- `epistemic-infrastructure`
- `jsonl`
- `open-science`

### Blogger

Use a shortened version of this README as a public interface post. Do not paste all 4000 nodes into the blog page. Instead, present the corpus structure, links to the four tome TXT files, links to GitHub / Hugging Face / Dataverse, and the recommended citation.

### Dataverse

Use this README as documentation. Upload it together with the TXT, JSONL, JSON, index, and metadata files. The recommended Dataverse package should contain:

- `README.md`
- the four canonical TXT tome files
- the four JSONL tome files
- the four JSON tome files
- the complete 4000-node JSONL and JSON files
- `socioplastics-corpus-metadata.json`
- index files
- license information

---

## Data Format

Each JSONL line contains one node.

Minimal schema:

```json
{
  "node": 3001,
  "tome": 4,
  "book": 31,
  "chapter": 301,
  "slug": "EXAMPLE-SLUG",
  "title": "Example Title",
  "url": "https://example.org",
  "source": "blog"
}
```

Fields:

- `node`: numeric node identifier
- `tome`: tome number
- `book`: book number
- `chapter`: chapter number
- `slug`: machine-readable conceptual slug
- `title`: human-readable title when available
- `url`: canonical public link
- `source`: source type, such as `blog` or `doi`

---

## Citation

Recommended citation for the complete corpus:

> Lloveras, A. (2026). *Socioplastics — Complete Corpus: Tomes I–IV, Nodes 0001–4000* (v1.0.0). LAPIEZA-LAB, Madrid, Spain.

Recommended citation for individual tomes:

> Lloveras, A. (2026). *Socioplastics — Tome I — Foundational Stratum* (v1.0.0). LAPIEZA-LAB, Madrid, Spain.  
> Lloveras, A. (2026). *Socioplastics — Tome II — Developmental Stratum* (v1.0.0). LAPIEZA-LAB, Madrid, Spain.  
> Lloveras, A. (2026). *Socioplastics — Tome III — Expansive Stratum* (v1.0.0). LAPIEZA-LAB, Madrid, Spain.  
> Lloveras, A. (2026). *Socioplastics — Tome IV — Consolidation Stratum* (v1.0.0). LAPIEZA-LAB, Madrid, Spain.

---

## License

CC BY-NC-SA 4.0  
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International

---

## Author

Anto Lloveras  
LAPIEZA-LAB · Madrid, Spain  
ORCID: 0009-0009-9820-3319  
Canonical interface: https://antolloveras.blogspot.com

---

## Status

This release consolidates the complete four-tome architecture of Socioplastics:

**4000 nodes · 400 chapters · 40 books · 4 tomes**

The corpus remains open to future expansion while this release fixes the first four-thousand-node cycle as a citable, machine-readable, auditable, and transdisciplinary knowledge infrastructure.
