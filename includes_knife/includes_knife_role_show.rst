.. The contents of this file are included in multiple topics.
.. This file describes a command or a sub-command for Knife.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


The ``show`` argument is used to view the details of a role. 

This argument has the following syntax::

   knife role show ROLE_NAME

This argument has the following options:

``-a ATTR``, ``--attribute ATTR``
   |attribute|

**Examples**

For example:

.. code-block:: bash

   $ knife role show devops

To view information in |json| format, use the ``-F`` common option as part of the command like this:

.. code-block:: bash

   $ knife role show devops -F json

Other formats available include ``text``, ``yaml``, and ``pp``.

