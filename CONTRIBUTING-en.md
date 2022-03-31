How to contribute
=================

We love pull requests. Here's a quick guide:

Getting Started
---------------

-  Make sure you have a GitHub account <a href="https://github.com/signup/free/" target="_blank">Github</a>
-  Submit a ticket for your issue, assuming one does not already exist.
-  Clearly describe the issue including steps to reproduce when it is a bug. If your prospective contribution concerns an idea rather than an error, describe it in full detail using the respective template for guidance.
-  Make sure you fill in the earliest version that you know has the issue, using commit hashes if possible.
-  Fork the repository on GitHub.

Making Changes
--------------

-  Create a topic branch from where you want to base your work (this is usually the master branch.)
-  Only target release branches if you are certain your fix must be on
   that branch.
-  To quickly create a topic branch based on master;
   ``git branch fix/master/my_contribution master`` then checkout
   the new branch with ``git checkout fix/master/my_contribution``.
   Please avoid working directly on the ``master`` branch.
-  Make commits of logical units.
-  Follow our `coding style`.
-  Check again your code to assure nothing else was accidentally broken.

Submitting Changes
------------------

-  Push your changes to a topic branch in your fork of the repository.
-  Submit a pull request to the repository.

Contribution Tips
-----------------

-  If contributing content to the guide, please make sure that your contribution conforms with [Google's guidelines on writing accessible documentation](https://developers.google.com/style/accessibility) where relevant.
-  If adding a new Markdown file, it may be worth checking out whether it should also appear on the [website version of the guide](https://e-panourgia.github.io/cosmos-tour/). If so, it should be included in the `nav` section of [mkdocs.yml](https://github.com/zkotti/cosmos-tour/blob/main/mkdocs/mkdocs.yml).

Additional Resources
--------------------

-  General GitHub documentation for help <a href="https://docs.github.com/en/" target="_blank">Help</a>
-  GitHub pull request
   documentation <a href="https://help.github.com/articles/about-pull-requests/" target="_blank">Pull Request</a>
