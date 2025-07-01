class SimpleCalculator:
   def_init_(self, num1:float, num2: float, operation: str):
     self.num1=num1
     self.num2=num2
operation.lower()
   def perform_operation(self):
     if self.operation == 'add':
        return self.num1 + self.num2
     elif self.operation == 'subtract':
        return self.num1 - self.num2
     elif self.operation == 'multiply':
        return self.num1 * self.num2
     elif self.operation == 'divide':
         if self.num2!=0;
             return self.num1/self.num2
         else:
            return "Error: Unsupported operation"
 
