---
layout: default
---

# GPL Cooperation Commitment for Projects (GPL-CC-1.0)

A project may wish to adopt the GPL Cooperation Commitment for all
contributions going forward. Simply put the [COMMITMENT]
(https://raw.githubusercontent.com/gplcc/gplcc/master/Project/COMMITMENT)
file in the same directory in your source repository as the GPLv2, LGPLv2
or LGPLv2.1 license file.

## How does this work "for all contributions going forward"?

Typically, all contributions to open source/free software projects are
licensed under the project's outbound license, a practice sometimes
known as "inbound=outbound". The Projects version of the GPL
Cooperation Commitment (SPDX short identifier GPL-CC-1.0) applies to
"each contributor to this repository as of the date of inclusion of
this file, including subsidiaries of a corporate contributor".  For an
inbound=outbound project, this means that anyone who contributes after
the project adopts GPL-CC-1.0 agrees to license their contributions
under the outbound license along with the additional permission
embodied in GPL-CC-1.0.

On the other hand, if a contributor to the project prior to the date
of the project's inclusion of GPL-CC-1.0 never contributes further to
the project after that date, then the additional permission embodied
in GPL-CC-1.0 does not apply to that contributor.

## Can I use GPL-CC-1.0 with a new project?

Yes. In this case, GPL-CC-1.0 applies from inception to all
contributors to the project. 

Following best practices for license identification, we recommend that
new projects adopting GPL-CC-1.0 use the appropriate SPDX license
expression in source files. For example:

    SPDX-License-Identifier: GPL-2.0-or-later WITH GPL-CC-1.0

We encourage new projects adopting SPDX license expressions in source
files to do so in conjunction with the [Developer Certificate of
Origin](https://developercertificate.org/) (DCO).

