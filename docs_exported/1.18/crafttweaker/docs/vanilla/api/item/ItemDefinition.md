# ItemDefinition

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.item.ItemDefinition;
```


## Casters

|                Result Type                 | Is Implicit |
|--------------------------------------------|-------------|
| [IItemStack](/vanilla/api/item/IItemStack) | true        |

## Methods

:::group{name=getCommandString}

Return Type: string

```zenscript
// ItemDefinition.getCommandString() as string

myItemDefinition.getCommandString();
```

:::

:::group{name=getDefaultInstance}

Return Type: [IItemStack](/vanilla/api/item/IItemStack)

```zenscript
// ItemDefinition.getDefaultInstance() as IItemStack

myItemDefinition.getDefaultInstance();
```

:::


## Properties

|      Name       |                    Type                    | Has Getter | Has Setter |
|-----------------|--------------------------------------------|------------|------------|
| commandString   | string                                     | true       | false      |
| defaultInstance | [IItemStack](/vanilla/api/item/IItemStack) | true       | false      |

