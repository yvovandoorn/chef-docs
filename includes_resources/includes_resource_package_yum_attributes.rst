.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

|description resource_attributes_intro|

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Attribute
     - Description
   * - ``allow_downgrade``
     - |allow_downgrade|
   * - ``arch``
     - |architecture package|
   * - ``flush_cache``
     - |flush_cache| Default value: ``{ :before => false, :after => false }``.
   * - ``options``
     - |command options|
   * - ``package_name``
     - |name package_yum| Default value: the ``name`` of the resource block (see Syntax section above).
   * - ``provider``
     - Optional. |provider resource_parameter|
   * - ``response_file``
     - Optional. |response_file|
   * - ``source``
     - Optional. |source resource package|
   * - ``version``
     - |version package|

