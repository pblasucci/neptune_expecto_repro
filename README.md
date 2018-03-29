neptune_expecto_repro
===

A minimal reproduction of a few issues integrating Neptune with Expecto

### Issues

1. Test cases which contain "spriti emoji" fail to have their state updated (i.e. icon colors don't change, test explorer doesn't recategorize)
    + Work-around: don't use stupid "spirit emoji" in test case names
2. Test cases which contain certain "test helpers" (e.g. `skipTest`, `failTest`) display a gutter icon 
    + Note: this might not be a _bug_, per se...  but it's a bit confusing when "scanning" a file
    + Work-around: none
3. Tests constructed using the `test "name" {}` computation expression syntax are NOT detected
    + Work-around: none
    