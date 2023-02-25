# Hilbert

A little script that transform a tex equation into a svg/png

## Installation

You can either, run install.sh, or move the hilbert script to your $PATH,
and move ./template.tex to $XDG_DATA_HOME/hilbert/template.tex

## Usage

execute the _hilbert_ script with the equation file (on a tex f
ormat), as the argument:

``
hilbert ./equation.tex
``
as an example of the equation file

``
\begin{align*}
A = \begin{bmatrix}
  a_1 & a_2
\end{bmatrix}
\end{align*}
``
