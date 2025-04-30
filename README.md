# rinderknecht.github.io

## String rewriting

<div style="text-align: justify; text-justify: inter-word;">
Let us assume that we own a string of white and black beads, like

$$
\circ \bullet \bullet \bullet \circ \circ \bullet
$$

and the game consists in removing two adjacent beads and replace them
with only one according to some rules, for example

$$
\bullet \\; \circ \xrightarrow{\smash{\alpha}} \bullet \qquad\qquad
\circ \\; \bullet \xrightarrow{\smash{\beta}} \bullet \qquad\qquad
\bullet \\; \bullet \xrightarrow{\smash{\gamma}} \circ
$$

The rules $\alpha$, $\beta$ and $\gamma$ make up a simple string-rewriting system. Rules $\alpha$ and $\beta$ can be conceived as `A black bead absorbs the white bead next to it.' The goal of this game is to end up with as few beads as possible, so our example may lead to the following rewrites:

$$
\circ \bullet \bullet \\, \fbox{$\bullet\\; \circ$} \circ \bullet
\xrightarrow{\smash{\alpha}} \circ \bullet \bullet \\,
\fbox{$\bullet\\; \circ$} \\; \bullet \xrightarrow{\smash{\alpha}}
\fbox{$\circ \\; \bullet$} \\; \bullet \bullet \\,\bullet
\xrightarrow{\smash{\beta}} \bullet \bullet \\, \fbox{$\bullet \\;
  \bullet$} \xrightarrow{\smash{\gamma}} \bullet \\, \fbox{$\bullet
  \\; \circ$} \xrightarrow{\smash{\alpha}} \fbox{$\bullet \\;
  \bullet$} \xrightarrow{\smash{\gamma}} \circ
$$

where the part of the string to be rewritten next is framed.

</div>
