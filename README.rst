**WARNING**: This repository is obsolete. The content will continue to be
maintained under the `dwave-examples <https://github.com/dwave-examples>`_
account.

Demos
=====
A collection of demos using the D-Wave Ocean SDK.

**NOTE** Each demo is stored in its own submodule and may have its own
set of package requirements (e.g. `antenna-selection/requirements.txt
<https://github.com/dwave-examples/antenna-selection/blob/master/requirements.txt>`_).

Setup Instructions
------------------
As each demo may have a different set of package requirements, you may
want to set up a `virtual environment <https://docs.ocean.dwavesys.com/en/latest/overview/install.html#python-virtual-environment>`_
to contain said packages and run your demo within that environment.

Package Installation
~~~~~~~~~~~~~~~~~~~~
::

  git clone --recursive https://github.com/dwavesystems/demos.git
  cd demos/<desired-demo>
  pip install -r requirements.txt

To pull the latest updates from each submodule, please run `git submodule
foreach git pull origin master` after cloning.

Please note that to run demos that access a D-Wave system, you must:

* Sign up for `D-Wave Leap <https://cloud.dwavesys.com/leap/signup/>`_ in order
  to get an authentication token
* Create a `configuration file <https://docs.ocean.dwavesys.com/en/latest/overview/dwavesys.html#configuring-a-d-wave-system-as-a-solver>`_ or set up `environment variables
  <https://docs.ocean.dwavesys.com/projects/cloud-client/en/latest/reference/configuration.html>`_,
  so that you can easily submit your problems to a D-Wave system without
  storing your authentication token in your code

Now you're ready to run your demo!

