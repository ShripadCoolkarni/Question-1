##Topic: Django Signals
  # Question-1
  Ans- By default  django signals are executed synchronously
  # Question-2 
  Ans- django signals run in the same thread as the caller
  # Question-3
  Ans-Django signals do not run within the same database transaction as the caller

##Topic: Custom Classes in Python
  class Rectangle:
    def __init__(self, length: int, width: int):
        self.length = length
        self.width = width

    def __iter__(self):
        return iter([{'length': self.length}, {'width': self.width}])


rect = Rectangle(10, 5)
for attribute in rect:
    print(attribute)
