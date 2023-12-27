def solve_quadratic(a, b, c, x):
  result=a*x**2+b*x+c
  return result
def main():
  num_sets=int(input("Enter the number of sets of coefficients: "))
  x =float(input("Enter the value of x: "))
  for _i in range(num_sets):
      a = float(input("Enter coefficient a: "))
      b = float(input("Enter coefficient b: "))
      c = float(input("Enter coefficient c: "))
      result = solve_quadratic(a, b, c, x)
      print({result})
if __name__ == "__main__":
   main()# software-engineering
