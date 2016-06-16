Plain NTriple graph data for use with the Cayley graph database.

The `normalize-graph-data` script converts the `madeup-raw.nt` file to `madeup.nt`, surrounds text labels with quotation marks, enforces some domain-specific properties (such as reflexivity) on graph edges and ends all lines with a period.  This makes `madeup-raw.nt` much easier to alter.
