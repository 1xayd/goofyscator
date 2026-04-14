# goofyscator
free public lua 5.1/luau obfuscator.
https://goofyscator.lua.cz/
# Features:
 - encryptStrings
 - built in antitamper
 - proxifyLocals - rewrites local declarations through proxy metatables
 - proxifyFunctions - rewrites local function declarations through callable proxies
 - control flow flattening - flattens the control flow graph of the bytecode with constant jump opcodes and shuffled blocks between protos and main proto.
