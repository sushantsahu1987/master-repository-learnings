# master-repository-learnings
A demonstration into the world of git submodules.

      ### How to add sub modules
      
        You've added another git repository inside your current repository.
        Clones of the outer repository will not contain the contents of
        the embedded repository and will not know how to obtain it.
        If you meant to add a submodule, use:

          git submodule add <url> mrl-slave-repository

        If you added this path by mistake, you can remove it from the
        index with:

          git rm --cached mrl-slave-repository

        See "git help submodule" for more information.

