# tsc-references-bug
a bug repo for tsc references

## Get Started

```
npm install
```

then run tsc commandline in watch mode 

```
npx tsc --build ./tsconfig.json -w
```

remove the `references` field of root tsconfig.json, save, and then undo this operation. 
