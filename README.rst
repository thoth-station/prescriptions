Prescriptions for Thoth's adviser
---------------------------------

⚕️💊⚕️
----

Prescriptions to heal your applications and application dependencies.

What are prescriptions?
=======================

This repository keeps a database of known issues in Python open-source
projects as well as suggestions for Python libraries and runtime
environments they can run in. The database is used in
`Thoth <https://thoth-station.ninja/>`__ to resolve high quality Python
software stacks.

When using OpenShift or Kubernetes, one provides manifest files that state
how the desired state of a cluster should look like. Prescriptions might
be seen analogous to this - prescriptions provide a way to declaratively
state how the desired dependency resolution should look like considering
the prescribed rules. Then, it’s up to the reinforcement learning algorithm
implemented in `Thoth's adviser <https://github.com/thoth-station/adviser>`__
to find a solution in the form of a lockfile respecting the prescribed rules,
requirements for the application and other inputs to the Thoth's cloud
resolver.

See `the linked presentation
<https://docs.google.com/viewer?url=https://github.com/thoth-station/talks/raw/master/2021-09-03-devconf-us/thoth_healing_python_applications.pdf>`__
or `YouTube video <https://www.youtube.com/watch?v=SQO2yTQ_OD4>`__ for more info.

How to write a prescription?
============================

If you would like to write a prescription for resolver, check the `following
docs
<https://thoth-station.ninja/docs/developers/adviser/prescription.html>`__.

Need help with a prescription?
==============================

If you spotted an issue in Python dependencies or Python ecosystem, just let us
know by openning an issue and we will help you with writing a prescription.

Licensing
=========

The prescription database is released under the terms of `GNU Affero General
Public License v3.0 or later
<https://www.gnu.org/licenses/agpl-3.0.en.html>`__. See the LICENSE file for
more info.

Copyright © 2021 AICoE Project `Thoth
<https://thoth-station.ninja/>`__; Red Hat Inc.
