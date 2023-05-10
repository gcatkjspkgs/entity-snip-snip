# Custom shear interactions

## Usage

```js
ItemEvents.entityInteracted(event =>{
    entitySnipSnip(event, entity.id, item, output, minimumAmount, maximumAmount)
})
```

## Example

```js
ItemEvents.entityInteracted(event =>{
    entitySnipSnip(event, 'minecraft:zombie', 'minecraft:shears', 'minecraft:rotten_flesh', 1, 3, 3)
    entitySnipSnip(event, 'minecraft:villager', 'minecraft:shears', 'minecraft:emerald', 1, 1, 99)
})
```
