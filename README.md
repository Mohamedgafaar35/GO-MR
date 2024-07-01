```python
# from enum import Enum

# class SimpleComputer:
    """
 

    #  class Register:
        def __init__(self, name, value=0):
            self.name = name
            self.value = value

    #  class Memory:
        def __init__(self, size=100):
            self.size = size
    self.data = [0] * size

    # class Opcode(Enum):
        ADD = "ADD"
        SUB = "SUB"
        JMP = "JMP"
   def __init__(self):
     # 
        self.registers = {
            "A": self.Register("A"),
            "B": self.Register("B"),
            "C": self.Register("C"),
            "PC": self.Register("PC", 0),
        }
self.memory = self.Memory()
        # 
        self.instructions = []
    #
    def load_instructions(self, instructions):
        for instruction in instructions:
            self.memory.data[instruction.PC] = instruction
   # 
    def execute_instructions(self):
        while True:
