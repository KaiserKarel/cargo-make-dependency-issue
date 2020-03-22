cargo make does not effectively schedule dependencies within a workspace, between extended Makefile. Running 
```
cargo make two
```

Will result in two builds, while running

```cargo make three```

results in three total builds.