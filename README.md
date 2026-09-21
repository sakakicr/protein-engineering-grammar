# Protein Engineering Grammar

**Protein Engineering Grammar: From Molecular Formats to Programmable Medicines**

Koichiro Saka (Independent Researcher, Tokyo, Japan)

Protein therapeutics are conventionally classified by structural format: monoclonal, bispecific, conjugate, fusion. This scheme describes what a molecule is built from, not the functional logic it implements. The Protein Engineering Grammar is a complementary vocabulary that describes an engineered protein as a modular information-processing system made of four primitives:

- **Sensor**: reads a biological or chemical input
- **Gate**: evaluates a permission condition
- **Processor**: converts that decision into a physical molecular event
- **Actuator**: produces the application-level output

The manuscript also describes a Compiler formalism, a pipeline from a biological problem to a molecular architecture, and maps protein engineering technologies onto the Grammar.

## Contents

| File | Description |
|---|---|
| [`manuscript.pdf`](manuscript.pdf) | The manuscript |
| [`table_s1.csv`](table_s1.csv) | Table S1: the Grammar mapping of all 154 technologies, with primary references |
| [`CITATION.cff`](CITATION.cff) | Citation metadata |
| [`LICENSE`](LICENSE) | CC BY 4.0 |

### Columns of `table_s1.csv`

| Column | Meaning |
|---|---|
| `technology_id`, `technology` | Identifier and name of the technology |
| `sensor`, `relation`, `gate`, `processor`, `actuator` | The Grammar assignment. Each value is condensed to its leading term. `relation` is the Sensor relation axis (how two or more Sensor instances combine) |
| `evidence_status` | `evidence-backed`, `incomplete`, or `uncertain` |
| `evidence_qualifier` | Optional short note on the depth of evidence, for example `full-text confirmed` |
| `assignment_confidence` | `low` < `medium` < `medium-high` < `high`, or `n/a` when no assignment was attempted. When the primitives differ in confidence, the weakest level among the assigned primitives is given |
| `references` | The primary literature the assignment rests on. A blank entry means no literature was registered |
| `reference_dois` | DOIs of those references |

## How to cite

Until the Zenodo record exists, please cite the manuscript by its title and author, with the URL of this repository. This section will be updated with the DOI.

## Status

The manuscript has not been peer reviewed. This is independent work by the author, based on published literature; it does not represent the views of any organization.

## License

[CC BY 4.0](LICENSE). Reuse is welcome with attribution.

## Feedback

Disagreements with an assignment, missing technologies, and corrections are welcome as GitHub issues.
