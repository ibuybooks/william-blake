## William Blake and the Mysticisms of Sense and Non-Sense

#### A Master of Arts Thesis, University of Oregon, 1960

A LuaLaTeX Remaster of Dr. Raymond F. Peat's Master Thesis, presented to the University of Oregon in June of 1960.

## Downloads

You can download the latest pre-built PDF release here: https://github.com/ibuybooks/william-blake/releases/latest

## Compiling
#### Requirements
- LaTeX Distribution (e.g., TeX Live, MikTeX)
- Required Packages: `memoir`, `babel`, `csquotes`, `microtype`, `fontspec`, `perpage`, `footmisc`, `pdfpages`, `hyperref`, `biblatex`, `adjustbox`, `tikz`, `xparse`, `varwidth`

#### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ibuybooks/william-blake.git
   ```
2. Navigate to the Repository Directory:
   ```bash
   cd william-blake
   ```
4. Run the Following (in Sequence):
   ```bash
   lualatex WilliamBlake
   biber WilliamBlake
   lualatex WilliamBlake
   ```


