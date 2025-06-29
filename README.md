# SCRIB custom scripting language framework
This tool is meant to provide a simple framework to develop custom scripting languages for PATRICIAN's microservices.

## Related Quests (chronological order)
- [ ] Alphabetize the Arachnids

  - [ ] Scribing Lessons
  
    Develop a customizable dictionary, tokenizer and a parser for an arbitrary set of commands. The Dictionary should provide the ability to define commands using an universal token architecture, probably with the use of function pointers. The Tokenizer will then create an instruction tree for any arbitrary input and Dictionary, and The Parser will execute the functions as instructed. This collection of tools will be called SCRIB.

    - [ ] Define a basic Token object.
    - [ ] Carve out the Dictionary object.
    - [ ] Decide about and implement Node objects that set the relations between Tokens.
    - [ ] Implement the Tokenizer.
    - [ ] Carve out the Parser and the instruction tree.
