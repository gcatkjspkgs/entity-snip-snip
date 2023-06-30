# Custom shear interactions

[![kjspkg-available](https://github-production-user-asset-6210df.s3.amazonaws.com/79367505/250114674-fb848719-d52e-471b-a6cf-2c0ea6729f1c.svg)](https://kjspkglookup.modernmodpacks.site/#entity-snip-snip)

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
