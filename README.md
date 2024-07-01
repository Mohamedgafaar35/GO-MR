````python
# from enum import En 
# class SimpleComputer:=

# class Register:def __init__(self, name, value=0):self.name = nameself.value = value
# class Memory:def __init__(self, size=100):self.size = size  self.data = [0] * size
 # class Opcode(Enum):ADD = "ADD"SUB = "SUB"JMP = "JMP"def __init__(self):
# self.registers = {"A": self.Register("A"),"B": self.Register("B"),"C": self.Register("C"),"PC": self.Register("PC", 0),}self.memory = self.Memory()
 #self.instructions = []
#def load_instructions(self, instructions):for instruction in instructions:self.memory.data[instruction.PC] = instruction
# def execute_instructions(self):while True:
#instruction = self.memory.data[self.registers["PC"].value]
#if instruction.opcode == self.Opcode.ADD:self.registers["A"].value+= instruction.operandelif instruction.opcode = self.Opcode.SUB:self.registers["A"].value -= instruction.operandelif instruction.opcode == self.Opcode.JMP:self.registers["PC"].value = instruction.operandelse:raise ValueError(" ")
 #self.registers["PC"].value += 1
# if self.registers["PC"].value >= self.memory.size:break
#if __name__ == "__main__":
 # computer = BigComputer()
# instructions = [computer.Instruction(computer.Opcode.ADD, 10),computer.Instruction(computer.Opcode.SUB, 5),computer.Instruction(computer.Opcode.JMP, 2),]computer.load_instructions(instructions)
# computer.execute_instructions()
# print()for register in computer.registers.values():print(f"{register.name}: {register.value}")
```
