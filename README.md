# Shawn Ludmer

I build data platforms and the systems that decide whether you can trust what comes out of them.

Most of my work has been enterprise data architecture in regulated financial institutions, at JPMorgan, Citigroup and DTCC, where I owned the architecture of a risk data warehouse at roughly 600 tables and 12,000 columns and authored the modeling standards other teams built against. I am now founder and CTO of Revenue Pulse 360, a daily operating intelligence platform for multi-unit restaurant groups.

The repositories here share one idea. A system that quietly guesses is worse than one that stops and tells you.

## Projects

### [mapspec](https://github.com/shawntxus2/mapspec)

A declarative source-to-target mapping format that generates dbt models together with the tests that assert what the generated SQL actually claims. Anything the validator cannot express as typed SQL is reported as unconverted rather than approximated. The output is verified by running it on two database engines rather than by inspection.

### [rag-eval-harness](https://github.com/shawntxus2/rag-eval-harness)

Compares five retrieval strategies on one question set, scoring recall, mean reciprocal rank and latency with significance testing. The README reports which findings do not survive multiple-comparison correction, including the ones that went against what I expected going in.

## Elsewhere

- [Revenue Pulse 360](https://revenuepulse360.ai)
- [Risk Maps, a case study](https://shawnludmer.com)
- [LinkedIn](https://linkedin.com/in/shawnludmer)
