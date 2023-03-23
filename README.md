# Typescript Design Patterns

## 1. Builder
The Builder pattern can be recognized in a class, which has a single creation method and several methods to configure the resulting object. Builder methods often support chaining 
(Eg. someBuilder.setValueA(1).setValueB(2).create()).
See `/builder/builder.ts` for a conceptual example of the pattern