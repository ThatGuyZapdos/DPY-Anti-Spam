AntiSpamHandler
===============

**Note, this is the main entrance to this entire package.
As such this should be the only thing you interact with.**

This handler propagation method also returns the following dictionary for you to use:

.. code-block:: python
    :linenos:

    {
        "was_punished_this_message": boolean,
        "was_warned": boolean,
        "was_kicked": boolean,
        "was_banned": boolean,
        "status": string,
        "warn_count": integer,
        "kick_count": integer,
        "duplicate_counter": integer
    }

.. automodule:: AntiSpam.AntiSpamHandler
    :members:
    :special-members: __init__
