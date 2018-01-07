---
layout: page-fullwidth
title: "Particle physics explained! \n (well, what I used to do)"
subheadline: "Portfolio"
teaser: A bit of description of my past life.
image:
    thumb: cern_collision_1_resize.jpg
#teaser: "With <em>Feeling Responsive</em> you don't need a special portfolio template. Just check out the great possibilities of the <a href='http://foundation.zurb.com/docs/components/grid.html'>foundation grid</a> and experiment with it."
categories:
    - design
---

<!-- # Physics -->

### General Description of Past Research in Collider Physics

Data analysis is an important part of doing science in high energy particle physics.
This field of physics studies the makeup of atoms and interactions of their
constituents by smashing particles together (such as pairs or protons, the building blocks of atoms) in a particle collider. Particle colliders are among the most complex machines humans have ever built, and they
produce a tremendous amount of data because the collisions produce many different
particles, and this gets very messy!  This data is processed and slimmed down quite a bit based on careful selection criteria, so that in the end there is a manageable, though still sizeable, amount of data to be processed.

<div class="row">
    <div class="medium-4 columns t30">
    <img src="{{ site.urlimg }}figure__atom.png" alt="">
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns t30">
      <img src="{{ site.urlimg }}figure__collision.png" alt="">
    </div><!-- /.medium-4.columns -->

</div>

High-energy theorists often hypothesize the existence of new, previously unknown 
particles that may be created in the collisions.  Instead of real data, they will
simulate the various production processes via Monte Carlo simulations.  By understanding the "normal" processes, a collision "background" can be simulated.  And, with a new theory, the "signal" for a new  particle can be simulated as well.  If the signal is different enough from the background, that is, if a small signal can be seen above a background by using the right type and the right amount of data, a new particle may be discovered!



##### Exploratory Data Analysis

Analysis requires exploratory data analysis of possibly 100s of parameters in
a model.  The parameters of large models are constained in the two
following ways.
  * Constraints from physical laws and observations.  For example,from special relativity, we know particles should not travel faster 
    than the speed of light, *i.e.*, tachyonic particles.  Should the model have any regions of the parameter space that predict such particles, those regions must be excluded.

  * Models parameter spaces may also be simplified by 
    theoretically motivated restrictions, *e.g.*, relating two parameters 
    by a yet unrealized physical mechanism can reduce two parameters to
    just a single one.  String theory models, for example, are badly in need of
    constraints like these, as there is not enough data to begin to 
    constrain the models.

There either has to be enough observations to constrain the 
parameter space, or the models have simplifying assumptions to reduce the 
effective parameter space.

##### Cascade Decay Patterns

Usually, once heavy particles are produced in a collision, they travel away from
the collision site for some time and then decay into lighter 
particles (unless there is a theoretically-motivated symmetry to prevent this).   In
particle phenomenology, studying the decay channels, *i.e.*, the various
particles produced in the decay and their kinematic distribution, is 
essential for determining how the produced particles will be detected
in an experiment.  This tells an experimenter what they are looking for
in huge messy collision.  For example, if there are more electrons being 
produced than expected, then it could be a sign that an exotic heavy parent
particle was created, even though the parent was never detected directly.
This information that allows to infer the production of a heavy 
particle is called a "signature."

##### Predictions

Once the signatures have been determined (not a simple task), computerized 
simulations of experiments are valuable tools for determining the prospect
of finding a signature in a real experiment.

<!-- ## Description of Research in Dark Matter

Through cosmological and particle-physics measurements, the composition of the
visible universe is understood.  It is roughly broken down as 
\begin{itemize}
\item 70\% Dark Energy,

\item 4\% Normal (Baryonic) Matter, and 

\item 25\% Dark Matter (DM).
\end{itemize}
\begin{figure}[htbp]
\centering
\includegraphics[scale=.5]{figure__dark_matter_pie_chart.pdf}
\end{figure}

The last of these, the particle-physics dark matter problem, requires that the DM particle be massive enough to account for the relic dark matter abundance as well as cold enough to allow for structure formation on small scales in the early universe.
 -->

<!--more-->


