.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

An encrypted data bag item is decrypted with a |knife| command similar to:

.. code-block:: bash

   $ knife data bag show --secret-file /tmp/my_data_bag_key passwords mysql

that will return |json| output similar to:

.. code-block:: javascript

   {
     "id": "mysql",
     "pass": "thesecret123",
      "user": "fred"
   }