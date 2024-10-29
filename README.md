# Pipeline-processor
Processor using pipeline microarchitecture based on the RISC-V architecture in SystemVerilog.

This processor is capabable of execute the following instructions: 
```asm
lw
sw
sll, slli, srl, srli, sra, srai
add, addi, sub
xor, xori, or, ori, and, andi
beq, bne, blt, bge
slt, slti, sltu, sltui
jal, jalr
```

This implementation takes into account the hazards that appears in this type of multicycle Pipepline, using: hazard detection, fordwarding, and the 'always taken' strategy for those control hazards. 

