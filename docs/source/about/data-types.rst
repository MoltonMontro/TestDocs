Data types
==========

.. list-table::
   :widths: 20 80
   :header-rows: 1

   * - Data type
     - Description
   * - :ref:`GUID <doc_assets_guid>`
     - Globally unique identifiers (GUIDs) are 32 hexadecimal digits used to identify assets. They are preferable to file names because the files can be moved without redirectors.
   * - flag
     - Flags are true if the property is present, and false if they are absent. Many of the older properties for asset v1 content uses flags, instead of booleans.
   * - :ref:`master bundle pointer <doc_assets_masterbundleptr>`
     - Identifies a Unity asset such as a prefab, material, or audio clip within a master bundle.
   * - :ref:`asset pointer <doc_assets_assetptr>`
     - When one asset refers to another asset, it does so using an asset pointer. These identify the target asset by their GUID.
   * - :ref:`u32 mask <doc_assets_bitmask>`
     - A mask or bitmask is data used for bitwise operations.

.. toctree::
   :hidden:
   :maxdepth: 1

   assets/AssetPtr
   assets/Bitmask
   assets/GUID
   assets/MasterBundlePtr
