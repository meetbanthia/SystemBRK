#Basic gates and small size composites which can be used further for formation of RAMs, CPUs etc

1. We will be using Nand gates, as it is considered primitive gate, and will be forming other basic gates using Nand gate.
2. Nand gates can be used off-the-shelf, obviously we will not go one level down, it's literally physics now! - For more info on how a primitive logic gateis formed I would recommend this youtube video which explains about the working of transistors in a beutiful way.
3. Other basic gates created are and, or, xor, not, Mux, Dmux, Not16, And16, Or16, Mux16, Or8Way, Mux4Way16, Mux8Way16, DMux4Way, Dmux8Way.
4. Keep in point that inorder for alu to use already created gates, they should lie in the same directory which is not the case here. Make sure to bring every gates to same directory for using these files in hardware simulator.
5. ALU used add16 gate which in turn uses full adder which in turn uses half adder. All these gates have also been created in alu sub-directory.
6. We've create ALU HACK(note alu designs can be different!), although key principles remains the same.