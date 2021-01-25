### Keys
`type`: Must be `"tconstruct:part_builder"`.  
`pattern`: [[ResourceLocation|Common-JSON-Value-Types#resourcelocation]]. The location of the pattern.  
`cost`: Integer. How many baseline "ingots" are needed to make one part.
`result`: [[IMaterialItem|Common-JSON-Value-Types#imaterialitem]]. The output part.

### Example
    {
      "type": "tconstruct:part_builder",
      "pattern": "tconstruct:axe_head",
      "cost": 2,
      "output": {
        "item": "tconstruct:axe_head"
      }
    }