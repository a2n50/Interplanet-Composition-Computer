# Interplanet-Composition-Computer

Jupiter = {"atm_press": "1 atm (at defined cloud level)", "H₂": "89.8%", "He": "10.2%"}
Mercury = {"atm_press": "1 x 10⁻¹² atm", "O₂": "42%", "Na": "29%", "H₂": "22%", "He": "6%"}
Venus = {"atm_press": "92 atm", "CO₂": "96.5%", "N₂": "3.5%"}
Earth = {"atm_press": "1 atm", "N₂": "78%", "O₂": "21%", "CO₂": "1%"}
Mars = {"atm_press": "0.006 atm", "CO₂": "95%", "N₂": "2.8%", "Ar": "2%"}
Saturn = {"atm_press": "1 atm (at defined cloud level)", "H₂": "96.3%", "He": "3.2%"}
Uranus = {"atm_press": "1 atm (at defined cloud level)", "H₂": "82.5%", "He": "15.2%", "CH₄": "2.3%"}
Neptune = {"atm_press": "1 atm (at defined cloud level)", "H₂": "80%", "He": "19%", "CH₄": "1.5%"}

def test():
  planet = input("Enter a planet name:")
  testing_planet = planet.lower()
  if testing_planet == "mercury":
    return f"Planet composition: {Mercury}"
  elif testing_planet == "venus":
    return f"Planet composition: {Venus}"
  elif testing_planet == "earth":
    return f"Planet composition: {Earth}"
  elif testing_planet == "mars":
    return f"Planet composition: {Mars}"
  elif testing_planet == "jupiter":
    return f"Planet composition: {Jupiter}"
  elif testing_planet == "saturn":
    return f"Planet composition: {Saturn}"
  elif testing_planet == "uranus":
    return f"Planet composition: {Uranus}"
  elif testing_planet == "neptune":
    return f"Planet composition: {Neptune}"
  else:
    return "Invalid, please enter a valid planet name."

print(test())