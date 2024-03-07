# Examples
![An example of tokens made by this utility](example.jpg)
This is an example of what the [botc_tokens](https://github.com/Tsubashi/botc_tokens) utility can do. After populating 
the `inputs` directory with roles of my own creation, the remaining directories were created using the following 
commands:

```bash
botc_tokens create example/inputs example/tokens --component-dir example/components
botc_tokens group example/example_script.json --token-dir example/tokens --output-dir example/printables
```

Yes, these roles are silly. No, I wouldn't advise using them in a game. Still, they demonstrate what you can expect
when using the utility with your own roles.
