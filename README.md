fbuy-dev-scripts
================

These are scripts that assist me in my development efforts. The `git-*` files
are git plugins that, when dropped into your PATH somewhere, will be available
from any git repository.

git-add-non-wsgi
----------------

Performs a `git add` on all modified files that are not run_*.py files.

git-change-interfaces
---------------------

Changes all `127.0.0.1` references in the run_*.py files to `0.0.0.0`.

git-clean-tmp
-------------

Removes all *.pyc files in the git repository from which it is run.

git-reset-interfaces
--------------------

Changes all `0.0.0.0` references in the run_*.py files back to `127.0.0.1`
references.

