# IBlockActivated

This class was added by a mod with mod-id `contenttweaker`. 因此，如果要使用此功能，则需要安装此mod。

## 导入相关包

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import mods.contenttweaker.functions.IBlockActivated;
```


## 方法

:::group{name=apply}

Return Type: [ActionResultType](/vanilla/api/util/ActionResultType)

```zenscript
IBlockActivated.apply(state as MCBlockState, world as MCWorld, pos as BlockPos, player as MCPlayerEntity, hand as MCHand) as ActionResultType
```

| 参数     | 类型                                                           | 描述                      |
| ------ | ------------------------------------------------------------ | ----------------------- |
| state  | [MCBlockState #MC方块状态](/vanilla/api/block/MCBlockState)      | No Description Provided |
| world  | [MCWorld](/vanilla/api/world/MCWorld)                        | No Description Provided |
| 点      | [BlockPos](/vanilla/api/util/BlockPos)                       | No Description Provided |
| player | [MCPlayerEntity #MC玩家实体](/vanilla/api/entity/MCPlayerEntity) | No Description Provided |
| hand   | [MCHand](/vanilla/api/util/MCHand)                           | No Description Provided |


:::

