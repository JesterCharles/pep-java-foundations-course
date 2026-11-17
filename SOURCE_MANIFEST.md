# Source manifest

Source repository: `JesterCharles/pep-technology-content`

Source commit: `1814ba7d884177bb941d1d5ebe038c132f3dcc03`

Scope: the `java-foundations/` course only - its 8 modules, its assessments, and its `authoring/catalog/` and `authoring/evidence/` trees. 689 source files.

## Path mapping

| Source | Destination | Files |
| --- | --- | --- |
| `java-foundations/<module>/<topic>/artifact.<ext>` | `modules/<module>/<topic>.<ext>` | 159 |
| `java-foundations/<module>/<topic>/<other file>` | `modules/<module>/<topic>/<other file>` | 7 |
| `java-foundations/java-basics/coding-lab/` | `modules/java-basics/coding-lab/` | 6 |
| `java-foundations/assessments/` | `course-material/java-foundations/assessments/` | 2 |
| `authoring/catalog/java-foundations/` | `authoring/catalog/java-foundations/` | 73 |
| `authoring/evidence/java-foundations/` | `authoring/evidence/java-foundations/` | 442 |

## Topics

| Module | Topics | `.md` | `.html` | `.gift` | `.pdf` |
| --- | --- | --- | --- | --- | --- |
| `java-basics` | 7 | 7 | 7 | 7 | 0 |
| `methods-and-recursion` | 9 | 9 | 9 | 9 | 0 |
| `arrays-lists-and-maps` | 4 | 4 | 4 | 4 | 0 |
| `classes-and-objects` | 9 | 9 | 9 | 9 | 0 |
| `inheritance-and-design` | 9 | 9 | 9 | 9 | 0 |
| `exceptions-and-logging` | 5 | 5 | 5 | 5 | 1 |
| `http-and-javalin` | 4 | 4 | 4 | 4 | 0 |
| `testing-and-java-review` | 6 | 6 | 6 | 4 | 1 |

The catalog also lists two project briefs, `classes-and-objects/classes-in-practice-project` and `http-and-javalin/repository-wiring-and-errors-project`. The source commit holds no lesson files for them, so they have no file under `modules/`.

## Changed bytes

680 of the 689 copied files are byte-identical to the source. The other 9 differ only in one "Next topic" link each, rewritten because the lesson files moved up one directory:

| File | Source link | Link here |
| --- | --- | --- |
| `modules/arrays-lists-and-maps/arraylist-basics.html` | `href="../hashmap-basics/artifact.html"` | `href="hashmap-basics.html"` |
| `modules/arrays-lists-and-maps/declaring-and-looping-over-arrays.html` | `href="../linear-and-binary-search/artifact.html"` | `href="linear-and-binary-search.html"` |
| `modules/arrays-lists-and-maps/linear-and-binary-search.html` | `href="../arraylist-basics/artifact.html"` | `href="arraylist-basics.html"` |
| `modules/java-basics/arithmetic-comparison-and-logical-operators.html` | `href="../if-else-and-switch/artifact.html"` | `href="if-else-and-switch.html"` |
| `modules/java-basics/if-else-and-switch.html` | `href="../for-while-and-do-while-loops/artifact.html"` | `href="for-while-and-do-while-loops.html"` |
| `modules/java-basics/installing-java-and-the-ide.html` | `href="../running-a-first-program/artifact.html"` | `href="running-a-first-program.html"` |
| `modules/java-basics/primitive-types-and-variables.html` | `href="../strings-and-string-methods/artifact.html"` | `href="strings-and-string-methods.html"` |
| `modules/java-basics/running-a-first-program.html` | `href="../primitive-types-and-variables/artifact.html"` | `href="primitive-types-and-variables.html"` |
| `modules/java-basics/strings-and-string-methods.html` | `href="../arithmetic-comparison-and-logical-operators/artifact.html"` | `href="arithmetic-comparison-and-logical-operators.html"` |

Path strings inside `authoring/` files still name the source layout (`java-foundations/<module>/<topic>/artifact.<ext>`). They are provenance records and were left unchanged.

## Deliberately outside this repository

- The other three Foundation courses: `git-linux-ai-foundations/`, `sql-jdbc-foundations/` and `collections-streams/`, with their assessments, labs, course reviews, catalogs and evidence.
- Every other course in the source repository, the curriculum snapshots, and the source repository's tooling.
