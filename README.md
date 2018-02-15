# git-cases

this shows a problem with checking out a repo into a case-insensitive filesystem (like macos's default) that was created on one that was case-sensitive.

when you check this out, you will end up with one file (foo) and you will have a dirty repo - FOO and Foo will be missing.
