# manifest.json-template
Use this template to create texture packs for Minecraft Bedrock Edition




{
  "format_version": 2,
  "header": {
    "description": "YOUR PACK DESCRIPTION",
    "name": "YOUR PACK NAME",
    "uuid": "UUID 1",
    "version": [ 0, 6, 4 ],
    "min_engine_version": [1,16,0]
  },
  "modules": [
    {
      "description": "YOUR PACK DESCRIPTION",
      "type": "resources",
      "uuid": "UUID2",
      "version": [ 0, 6, 4 ]
    }
  ],
  "subpacks": [
    {
      "folder_name":"YOUR FOLDER NAME",
      "name": "NAME",
      "memory_tier": 1
    },
    {
      "folder_name": "FOLDER NAME",
      "name": "NAME",
      "memory_tier": 1
    }
  ]
}
