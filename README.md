print("Welcome to Tondo Manila.")
print("Your mission is to go to brgy. hall.")

choice_1 = input("You are at the arco, where do you want to go? Type 'left' or 'right'\n").lower()
if choice_1 == "left":
    choice2 = input("Kausap mo ngayon ang tambay magtatanong ka o lalakad? Type 'usap' or 'lakad'\n").lower()
    if choice2 == "lakad":
        choice3 = input("Malapit ka na mamili ka ngayon ng daanan: SB, OB, 63rd?\n").lower()
        if choice3 == "OB":
            print("Nakarating ka na sa brgy. hall ng buhya. Welcome ule sa Tondo.")
        elif choice3 == "SB":
                  print("ginulpi ka ng mga tao sa SB(sblock). Game over.")
        elif choice3 == "63rd":
                  print("ginulpi ka ng mga tao sa 63rd(third). Game over.")
        else:
            print("Nawala ka. Hindi mo nakita ang brgy. hall.")
    else:
        print("Patay ka na nasaksak ka ng tambay.")
else:
    print("Patay ka na nasaksak ka ng tambay.")
  
