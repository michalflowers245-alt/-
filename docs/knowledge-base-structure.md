# Knowledge Base Structure

The knowledge layer is organized as four linked stores:

## 1. Classic Case Library

Stores:

- source book
- representative case
- short retelling
- why the case matters

Question answered:

> Which story should we reach for first?

## 2. Underlying Principle Library

Stores:

- core variable
- mechanism
- transferable principle
- boundaries

Question answered:

> What does this case really explain?

## 3. Real-World Mapping Library

Stores:

- suitable domains
- unsuitable domains
- modern parallels
- risk notes

Question answered:

> Where can this principle travel without breaking?

## 4. Writing Conversion Library

Stores:

- hook angles
- opening lines
- argument structures
- title patterns
- memorable lines

Question answered:

> How does this become a stronger piece of writing?

## Recommended Future Expansion

If the project grows, split the current learning cards into per-book files:

```text
skill/references/books/
├── a-brief-history-of-time.md
├── sapiens.md
├── thinking-fast-and-slow.md
└── ...
```

Then add machine-friendly metadata later, for example:

```yaml
book: "Sapiens"
case: "money as shared fiction"
domains:
  - brands
  - institutions
  - communities
risk: "weak fit for purely technical causality"
```
