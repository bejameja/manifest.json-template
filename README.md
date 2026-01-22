# manifest.json-template
Use this template to create texture packs for Minecraft Bedrock Edition
replace "UUID1" and "UUID2" wirh the [UUID generator](https://www.uuidgenerator.net/)



```json
{
  "format_version": 2,
  "header": {
    "name": "YOUR PACK NAME",
    "description": "YOUR PACK DESCRIPTION",
    "uuid": "UUID 1",
    "version": [0, 6, 4],
    "min_engine_version": [1, 16, 0]
  },
  "modules": [
    {
      "type": "resources",
      "uuid": "UUID 2",
      "version": [0, 6, 4]
    }
  ],
  "subpacks": [
    {
      "folder_name": "YOUR FOLDER NAME",
      "name": "NAME",
      "memory_tier": 1
    }
  ]
}