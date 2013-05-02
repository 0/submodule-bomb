If your Git is at least 1.8.2.1, after cloning this repository, run:

    git submodule update --init --recursive --remote

Enjoy!

---

To generate your own, run the generator script (in an existing repo) with the message of your choice:

    ./generator root 'Wit spewing everywhere!'

where `root` will be used as the parent commit for all the branches.

Be mindful that some characters will be sanitized away, and that cleaning this up might not be pretty.
