# cs50-01
#week 0

yaser = input(" :")
if yaser[:5].lower() == 'hello':
    print("$0")
elif yaser.strip().lower()[:5] == "hello":
    print("$0")
elif yaser[:3].lower().strip() == "hey" or yaser[:3].lower().strip() == "how":
    print("$20")
else:
    print("$100")
