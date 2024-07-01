# davidctinescu/penguinmod-cpu

windowsbuild3r CPU v1.6 Documentation

## ISA OP-Codes
- **rvga**: Test raw VGA
- **add**: Add 2 numbers and store result in accumulator
- **sub**: Subtract 2 numbers and store result in accumulator
- **mul**: Multiply 2 numbers and store result in accumulator
- **div**: Divide 2 numbers and store result in accumulator
- **lshift**: Bit-wise shift left on accumulator
- **rshift**: Bit-wise shift right on accumulator
- **jmp**: Jump to decimal address
- **dmp**: Dump stack to raw VGA, RAM, and clear stack
- **hlt**: Halt program counter
- **clr**: Clear accumulator
- **mov**: Move data between registers
- **nop**: No operation
- **wvga**: Write character/characters to raw VGA, this includes registers!
- **cvga**: Clear raw VGA
- **svga**: Set VGA settings
- **set**: Set value at RAM address (only decimal values)
- **get**: Get value at RAM address (only decimal values)

## System Responses (sysr)
- **1**: Failed
- **0**: Succeeded
- **-255**: Jumped
- **-1**: Halted

## Registers
- **acc**: Accumulator (decimal)
- **ir**: Instruction register
- **mra**: Memory read address (decimal)
- **mwa**: Memory write address (decimal)
- **pc**: Program counter (decimal)
- **sysr**: System response (decimal)

## General Purpose Registers
- **gpr0**, **gpr1**, **gpr2**, **gpr3**: General purpose registers

## Functions
- None implemented yet

## Variables
- None implemented yet

## Arguments
- Listed with white-space, not commas!

## Manipulation of Registers in Arguments
- Use `r:` to specify the use-case of a register

## Comments
- None yet, planning to add ones like `;`

## Publication
- Public Domain - Uni-license
