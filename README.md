# RC Phase-Shift Oscillator Calculator

print("RC PHASE-SHIFT OSCILLATOR")
print("-------------------------")

# Input values
R = float(input("Enter resistance R (ohms): "))
C = float(input("Enter capacitance C (farads): "))

# Frequency calculation
f = 1 / (2 * 3.14159 * R * C)

# Display result
print("\n--- Results ---")
print(f"Resistance      = {R:.2f} ohms")
print(f"Capacitance     = {C:.8f} F")
print(f"Oscillator Frequency = {f:.2f} Hz")

# Convert frequency to kHz
print(f"Frequency       = {f / 1000:.4f} kHz")# oscillators-