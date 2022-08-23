# family-tree-cli

## Define a family tree:

Design a command line tool (family-tree) that has the following options:

```sh
family-tree add person <name>
```

eg: family-tree add Amit Dhakad

```sh
family-tree add relationship <name>
```

eg: family-tree add relationship father

eg: family-tree add relationship son

```sh
family-tree connect <name 1> as <relationship> of <name 2>
```

eg: family-tree connect Amit Dhakad as son of KK Dhakad

## Queries:

Based on relations created, we should be able to make following queries:

```sh
family-tree count sons of <name>
```

This should count sons

```sh
family-tree count daughters of <name>
```

This should count of all daughters

```sh
family-tree count wives of <name>
```

This should count wives

```sh
family-tree father of <name>
```

This should return father name

Our Family Tree:

Please ignore the DoB

Pink = Females
