Keep the for up to date
=======================

Fetch the branches and their respective commits from the upstream repository. Commits to master will be stored in a local branch, upstream/master.

.. code-block:: bash

    git fetch upstream


Check out your fork's local master branch.

.. code-block:: bash

    git checkout master

Merge the changes from upstream/master into your local master branch. This brings your fork's master branch into sync with the upstream repository, without losing your local changes.

.. code-block:: bash

    git merge upstream/master

If your local branch didn't have any unique commits, Git will instead perform a "fast-forward":

.. code-block:: bash

    git merge upstream/master
