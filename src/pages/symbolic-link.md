---
title:
---

A symbolic link, often called a \'symlink\', is a file that serves as a
reference/pointer to another file or directory.

With [Unix](unix.html)-based systems the `ln` (link) command with the
`-s` (soft) flag can be used to create symbolic link:

```sh
ln -s {target_path} {link_path}
```

-   `{target_path}`{is:raw=""} is the path to the file or directory to
    link to.
-   `{link_path}`{is:raw=""} the desired path for the (new) symbolic
    link.
