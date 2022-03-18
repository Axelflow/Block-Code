while True:
    def volume_cube():
        l = float(input("Please enter the length of the cube: "))
        result = (l * l * l)
        return(result)

    def volume_cone():
        r = float(input("Please enter the cone's radius: "))
        h = float(input("Please enter the cone's height: "))
        pi = 3.142
        result = pi * r *r * (h/3)
        return(result)

    def volume_cylinder():
      r = float(input("Please enter the cylinder's radius: "))
      h = float(input("Please enter the cylinder's height: "))
      pi = 3.142
      result = (pi * r * r *h)
      return(result)


    print()
    print("Choose a shape to calculae the volume of")
    print("1. Volume of a Cone")
    print("2. Volume of a Cube")
    print("3. Volume of a Cylinder")
    user_choice = input("Enter the name of the shape from the options above: ")

    if(user_choice == "Cube"):
        total = volume_cube()
    elif(user_choice == "Cylinder"):
        total = volume_cylinder()
    elif(user_choice == "Cone"):
        total = volume_cone()
    elif(user_choice == "cube"):
        total = volume_cube()
    elif(user_choice == "cylinder"):
        total = volume_cylinder()
    elif(user_choice == "cone"):
        total = volume_cone()
    else:
        print("Invalid data type.")
        
       
