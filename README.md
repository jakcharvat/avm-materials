# AVM course build mirror

Build mirror for [jmarecek/variational-algorithms](https://github.com/jmarecek/variational-algorithms),
the *Variational Methods in Quantum Optimization* course. The course is included as a submodule;
CI builds the handouts and slides (full course and per chapter) as workflow artifacts. The submodule is
bumped by an outside bot whenever the course sources change (or by hand via the **Update course
submodule** workflow), and each new version is published as a GitHub release with the PDFs attached.
