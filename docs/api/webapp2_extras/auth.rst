.. _api.webapp2_extras.auth:

Auth
====
.. module:: webapp2_extras.auth

.. warning::
   This is an experimental module. The API is subject to changes.

.. autodata:: default_config

.. autoclass:: AuthStore
   :members: __init__

.. autoclass:: Auth
   :members: __init__,
             get_user_by_session, get_user_by_token, get_user_by_password,
             set_session, unset_session

.. autofunction:: get_store
.. autofunction:: set_store
.. autofunction:: get_auth
.. autofunction:: set_auth
