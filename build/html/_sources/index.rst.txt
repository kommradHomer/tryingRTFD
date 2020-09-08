.. tryingrtfd documentation master file, created by
   sphinx-quickstart on Tue Sep  8 18:39:16 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to tryingrtfd's documentation!
======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:


========



Accounts
========

.. http:get:: /api/account/verify_credentials.json

  Test if supplied user credentials are valid.

  :reqheader Authorization: |auth|

  **Example response**: :ref:`user_object`



Workspaces
========

.. http:get:: /v1/rindap-rest-gw/Workspaces

  list all your workspaces



Tasks
========

.. http:get:: /v1/rindap-rest-gw/Workspaces/{WorkspaceSID}/Tasks

   list all your tasks



.. http:post:: /v1/rindap-rest-gw/Workspaces/{WorkspaceSID}/Tasks

   create new task


