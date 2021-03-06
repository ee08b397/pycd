====
pycd
====
| Simple command line tool to change directory for Python packages.
| You can now easily read the codes of the modules.

Installation
============
pycd officially supports bash and zsh.

.. code-block:: sh

  $ pip install pycd

  $ pypkg install_pycd
  Please add below to your shell config file
  >   source /usr/local/lib/python2.7/dist-packages/pycd/pycd.sh
  add to /home/wkentaro/.zshrc? [y/N]: y

  $ cat ~/.zshrc
  # this line is added by pycd
  source /usr/local/lib/python2.7/dist-packages/pycd/pycd.sh

Usage
=====
.. code-block:: sh

  $ pycd
  Usage: pycd <module_name>
  $ pycd numpy
  $ pwd
  /usr/local/lib/python2.7/dist-packages/numpy
  # read the code!

  # handling python package utils
  $ pypkg find numpy
  /usr/local/lib/python2.7/dist-packages/numpy
  $ pypkg list
  numpy
  sklearn
  scipy
  ...

License
=======
| Copyright (C) 2015 Kentaro Wada
| Released under the MIT license
| https://github.com/wkentaro/pycd/blob/master/LICENSE
