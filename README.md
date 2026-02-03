modXNA: a modular approach to parameterization of modified nucleic acids for use with Amber force fields

modXNA is a BASH based script designed to enable molecular simulations of modified nucleic acids within the AMBER ecosystem. It allows tha rapid construction of chemically modified nucleic acids, which are used extensively in antisense oligonucleotides (ASOs), siRNA, and other XNAs that incorporate backbone, sugar, or base modifications. modXNA provides a curated and continuously expanding library of fragments (backbones, sugars and bases) that integrate seamlessly with standard AMBER workflows.

The project is built around modularity and quickly generation of initial structures - modXNA is not a force field. Parameters are derived using established quantum-mechanical protocols and validated against structural, energetic, and dynamical benchmarks to ensure compatibility with modern AMBER force fields. modXNA is intentionally designed to support combinatorial modification patterns—such as phosphorothioate chirality, 2′-sugar substitutions (e.g., MOE, OMe, LNA), and base analogs—allowing users to construct heterogeneous oligonucleotides that closely match experimental systems. This makes it particularly well suited for structure–function studies, binding free-energy calculations, and mechanistic investigations of protein–nucleic acid interactions.

Requirements:
– Make sure you have the latest AmberTools installed.
– Make sure you have the latest version of CPPTRAJ installed.

Learn more: 
https://pubs.acs.org/doi/10.1021/acs.jctc.4c01164
https://livecomsjournal.org/index.php/livecoms/article/view/v6i1e4545
