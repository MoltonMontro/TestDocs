Welcome to Molt's test documentation!
=====================================

.. note::

   This project is under active development.

.. warning::

   This project is under active development.

Examples
--------

.. attention:: Attention! Words here!
   So many, many, many words.
   
   Words.

.. caution::

   Caution! This is a content block.

.. danger:: Danger! This documentation is deadly. Reading required ahead.

.. error:: What does the error say?
.. hint:: This is a hint.
.. important:: Important: please read!
.. note:: If you don't use your server often, your GSLT will expire and you will need to generate a new one.
.. seealso:: See also: GSLT.rst.
.. deprecated:: 3.23.0.1
.. versionadded:: 3.22.15.0
.. versionchanged:: 3.22.16.2

.. math:: 50/(2 + 3x) * damage_multiplier + (a + b)^2 = a^2 + 2ab + b^2

.. math::

   (a + b)^2  &=  (a + b)(a + b) \\
              &=  a^2 + 2ab + b^2

.. math::
   :nowrap:

   \begin{eqnarray}
      y    & = & ax^2 + bx + c \\
      f(x) & = & x^2 + 2xy + y^2
   \end{eqnarray}

.. Below is the table-of-content tree for the website,
   which is hidden from the page but appears in the sidebar.

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Getting started

   about/introduction
   about/troubleshooting
   about/data-types
   servers/CommandLine
   about/getting-started

.. First section has articles on assets (in general).
   Second section lists asset types, alphabetically.
.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Asset Manual
   
   assets/AssetBundleCustomData
   assets/AssetBundles
   assets/AssetsV1
   assets/AssetsV2
   assets/AssetValidation

   assets/AirdropAsset
   assets/AnimalAsset
   assets/Animation
   assets/CharacterMeshReplacement
   assets/CraftingBlacklistAsset
   assets/Currency
   assets/EffectAsset
   assets/Foliage
   assets/ItemAsset/index
   assets/ItemData
   assets/Layers
   assets/LevelAsset
   assets/ModHooks
   assets/NPCAsset/index
   assets/PhysicsMaterialAsset
   assets/SpawnAsset
   assets/StereoSongAsset
   assets/Unity2018
   assets/Unity2019
   assets/VehiclePhysicsProfile
   assets/WeatherAsset
   assets/ZombieDifficultyAsset

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Mapping

   mapping/CuratedMaps
   mapping/EditorAssetRedirectors
   mapping/FavoriteSearches
   mapping/Landscape
   mapping/LevelBatching
   mapping/LevelConfig
   mapping/ManualObjectCulling

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Servers & Programming

   servers/CommandIO
   servers/DedicatedWorkshopUpdateMonitor
   servers/GameServerLoginTokens
   servers/Glazier
   servers/OpenMod
   servers/PortForwarding
   servers/Rocket
   servers/RocketMod
   servers/ServerHosting
   servers/ServerHostingRules
   servers/ServerUpdateNotifications
