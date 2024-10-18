[Uploadidef calculate_motion():
    # Input for calculating motion
    try:
        x = float(input("Initial position (x in meters): "))
        v = float(input("Initial velocity (v in meters/second): "))
        t = float(input("Time elapsed (t in seconds): "))
        a = float(input("Acceleration (a in meters/second^2): "))
        
        # Calculations
        xf = x0 + v0 * t + 0.5 * a * t**2  
        vf = v0 + a * t                     
        
        # Results
        print(f"\nFinal position (xf): {xf:.2f} meters")
        print(f"Final velocity (vf): {vf:.2f} meters/second")
        print(f"Acceleration (a): {a:.2f} meters/second^2")
    
    except ValueError:
        print("Invalid input. Please enter numerical values.")

# Execute the program
calculate_motion()ng Tarea 111.py…]()
