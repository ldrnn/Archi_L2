# Y86 Architecture Project

A second year university project in computer architecture, using the Y86 instruction set and control logic.  
The goal of the project was to extend the Y86 processor by adding new instructions, modifying the control logic, and writing assembly programs to test the behavior of these extensions.

## Author

- Tran Minh Chau DO

- Léa DRION

## List of Exercises

### **Ex 1 — Factorization of rrmovl and irmovl**
- Merge both instructions under a single icode
- Use ifun to differentiate their behavior
- Update ALU and memory logic accordingly

### **Ex 2 — Adding incl and decl**
- Implement unary increment and decrement
- Reuse ALU addition with +1 or –1
- Write a first version of strncpy using repeated incl to move pointers

### **Ex 3 — Adding the loop instruction**
- Automatically decrement %ecx
- Jump to a label while %ecx != 0
- Test with a simple counter loop

### **Ex 4 — Adding loope and loopne**
- Extend loop with conditional behavior based on the Zero Flag (ZF)
- Implement loope (loop while equal) and loopne (loop while not equal)
- Write an improved version of strncpy using loopne
