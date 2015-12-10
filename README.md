# bower-git
Replaces bower component folders with their git-repository counterpart

```
→ bower-git

  Usage: bower-git [options] <path>

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
    -v, --verbose
```

Pass it a folder to a bower component and bower-git will clone the repository and replace the bower component folder with its git repository counterpart.

```
→ bower-git vendor/headjs
  Replacing bower component with git repository...
  Bower component "headjs" has been replaced by its git repository
```
