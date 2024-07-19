# Calik0.1-Python
def calculator(expression):
  try:
      result = eval(expression)
      return f"Answer: {result}"
  except Exception as e:
      return f"Error: {e}"

while True:
  example = input("Example: ")
  if example.lower() == 'exit':
      break
  print(calculator(example))
