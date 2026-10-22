# Variable lineage

One entry per variable that reaches the paper, whether through a table, a
figure, a summary statistic, an estimate or a counterfactual. Each entry gives
the raw file and field the variable starts from, each transformation in order
with the script that does it, its level and units in final form, and the code
files it appears in. Scripts are named without line numbers; functions are named
where the work happens inside one. Variables built by one rule from a set of
inputs (a family of interactions, a set of indicators) are documented as one
entry listing every member.

Sections follow the pipeline: identifiers and weights, then the variables of
each analysis block in the order the driver runs them. The final section covers
the tables, figures and paper macros each script writes.

Raw inputs referred to below (all under `data/input/`):

| File | Contents |
|---|---|
| `<file>` | <what it holds, one line> |

---

## 1. <Block name>

<!-- One entry per variable, added as variables reach the paper. -->

