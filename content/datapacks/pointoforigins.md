---
title: Adding Point Of Origins
type: docs
---

{{< callout type="warning" >}}
  You need to learn how datapacks works!
{{< /callout >}}

---

## Create a Datapack
- Follow the tutorial on the [Minecraft Wiki on datapacks](https://minecraft.wiki/w/Data_pack) on how to set one up, use the namespace from earlier


- Create a new **.json** file in the path

> `data/stargate/point_of_origin/dimension_name.json`

- Inside this new .json file, paste

> ```json
>{
>  "dimension": "mod_id:dimension_name",
>  "glyph": "CHARACTER"
>}
> ```

- Replace **mod_id** with the mods id, **dimension_name** with the name of the dimension

- Replace **CHARACTER** With any letter / symbol listed bellow ( DO NOT USE: `W`, `F`, `Q` as the mod already uses these letters)

- You can use something like this [HERE](https://lingojam.com/StandardGalacticAlphabet) to translate the letter you chose so you can see what symbol to press on the DHD in game.

- Also you can look [HERE](https://github.com/amblelabs/stargate/tree/main/src/main/resources/data/stargate/point_of_origin) for an example on what the completed `json` should look like!