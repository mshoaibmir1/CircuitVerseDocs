# Standard Gates

> This guide will teach you how to use the standard gates in CircuitVerse. It will also explain the way the gates work. The guide will explain how to customize an 'AND' gate in detail. Other gates have a similar customization.

Contributing Authors: [@satu0king](https://github.com/satu0king/)
                      [@brahmakulkarni](https://github.com/brahmakulkarni)

## AND Gate

This gate gives a HIGH output only if all input values are HIGH.

Two-input AND Gate Truth Table

| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0       | 0       | 0      |
| 0       | 1       | 0      |
| 1       | 0       | 0      |
| 1       | 1       | 1      |

Simple two-input AND Gate
<iframe width="300px" height="200px" src="https://circuitverse.org/simulator/embed/734" id="projectPreview" scrolling="no" webkitAllowFullScreen mozAllowFullScreen allowFullScreen> </iframe>

Multi Input AND Gate
You can change the number of inputs in the Property Menu.

<iframe width="300px" height="200px" src="https://circuitverse.org/simulator/embed/735" id="projectPreview" scrolling="no" webkitAllowFullScreen mozAllowFullScreen allowFullScreen> </iframe>

Multi-bitwidth AND Gate
You can change the bitwidth in the Property Menu.

<iframe width="300px" height="200px" src="https://circuitverse.org/simulator/embed/736" id="projectPreview" scrolling="no" webkitAllowFullScreen mozAllowFullScreen allowFullScreen> </iframe>

## OR Gate

This gate gives a HIGH output only if any of the input values are HIGH.

Two-input OR Gate Truth Table

| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0       | 0       | 0      |
| 0       | 1       | 1      |
| 1       | 0       | 1      |
| 1       | 1       | 1      |

Simple two-input OR Gate
<iframe width="300px" height="200px" src="https://circuitverse.org/simulator/embed/737" id="projectPreview" scrolling="no" webkitAllowFullScreen mozAllowFullScreen allowFullScreen> </iframe>

## NOT Gate

This gate simply inverts the input. It is also known as an inverter.

NOT Gate Truth Table

| Input   | Output |
|---------|--------|
| 0       | 1      |
| 1       | 0      |

Simple Not Gate
<iframe width="300px" height="200px" src="https://circuitverse.org/simulator/embed/738" id="projectPreview" scrolling="no" webkitAllowFullScreen mozAllowFullScreen allowFullScreen> </iframe>

## XOR Gate

This gate gives a HIGH output only if both inputs aren't the same.

Two-input XOR Gate Truth Table

| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0       | 0       | 0      |
| 0       | 1       | 1      |
| 1       | 0       | 1      |
| 1       | 1       | 0      |

Simple two-input XOR Gate
<iframe width="300px" height="200px" src="https://circuitverse.org/simulator/embed/740" id="projectPreview" scrolling="no" webkitAllowFullScreen mozAllowFullScreen allowFullScreen> </iframe>

## NAND Gate

This gate gives the inverted output of an And gate. In other words, it only gives a LOW output when all inputs are HIGH.

Two-input NAND Gate Truth table

| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0       | 0       | 1      |
| 0       | 1       | 1      |
| 1       | 0       | 1      |
| 1       | 1       | 0      |

Simple two-input NAND Gate
<iframe width="300px" height="200px" src="https://circuitverse.org/simulator/embed/741" id="projectPreview" scrolling="no" webkitAllowFullScreen mozAllowFullScreen allowFullScreen> </iframe>

## NOR Gate

This gate gives the inverted output of an Or gate. In other words, it only gives a HIGH output when all the inputs are LOW.

Two-input NOR Gate Truth Table

| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0       | 0       | 1      |
| 0       | 1       | 0      |
| 1       | 0       | 0      |
| 1       | 1       | 0      |

Simple two-input NOR Gate
<iframe width="300px" height="200px" src="https://circuitverse.org/simulator/embed/742" id="projectPreview" scrolling="no" webkitAllowFullScreen mozAllowFullScreen allowFullScreen> </iframe>

## XNOR Gate

This gate gives the inverted output of an Xor gate. In other words, it only gives a HIGH output if both the inputs are the same.

Two-input XNOR Gate Truth Table

| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0       | 0       | 1      |
| 0       | 1       | 0      |
| 1       | 0       | 0      |
| 1       | 1       | 1      |

Simple two-input XNOR Gate

<iframe width="300px" height="200px" src="https://circuitverse.org/simulator/embed/743" id="projectPreview" scrolling="no" webkitAllowFullScreen mozAllowFullScreen allowFullScreen> </iframe>
