# Parse-Large-JSON-Files
This sample it would be better to use plain CSV, or imagine the fields being sparse or the records having a more complex structure.

The snippet show the file can be read using a combination of stream and tree-model parsing. Each individual record is read in a tree structure, but the file is never read in its entirety into memory to process JSON files gigabytes in size while using minimal memory.
