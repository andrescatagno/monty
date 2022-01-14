******************************************
*  0x19. C - Stacks, Queues - LIFO, FIFO *

******************************************
<h1>The Monty language<h1>

<p>Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it; The goal of this project is to create an interpreter for Monty ByteCodes files.<p>

<h2>Monty byte code files<h2>

<p>Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument<p>

<p>Monty byte code files can contain blank lines (empty or made of spaces only, and any additional text after the opcode or its required argument is not taken into account<p>