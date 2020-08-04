```@meta
CurrentModule = JuDGE
DocTestSetup = quote
    using JuDGE
end
```
## JuDGE functions
```@docs
JuDGE.JuDGEModel
JuDGE.solve
JuDGE.resolve_subproblems
```

## JuDGE macros for subproblems
```@docs
JuDGE.@expansion
JuDGE.@shutdown
JuDGE.@expansioncosts
JuDGE.@maintenancecosts
JuDGE.@sp_objective
```

## Defining Trees
```@docs
JuDGE.narytree
JuDGE.tree_from_file
JuDGE.tree_from_leaves
JuDGE.print_tree
```

## Nodes of Trees
```@docs
Base.collect
JuDGE.get_leafnodes
JuDGE.get_node
```

## Tree Probabilities
```@docs
JuDGE.convert_probabilities
JuDGE.ConditionallyUniformProbabilities
JuDGE.UniformLeafProbabilities
```

## Other Tree functions
```@docs
JuDGE.depth
JuDGE.history
JuDGE.parent_builder
```