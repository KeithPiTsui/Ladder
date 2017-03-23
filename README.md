# Ladder
A Type Generic Function to access first object of particular type in a tree-like architecture from a specific node.

For instance, access the first ancestor of specific type in View tree-like architecture.

```
/// aView is a UIView in the View tree
let tableView = UIView.firstAncestor(UITableView.self)(aView)
```
