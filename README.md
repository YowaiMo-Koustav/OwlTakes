# OwlTakes

I have developed an software which can bypass the Active Palm Rejection which is based on Hardware. 
The implented logic for the backend is that the tip of a stylus has a small surface area, while the palm has a much larger one. Using this logic, we can create backend code that distinguishes between inputs. When both the stylus and the palm touch the screen, the input from the larger area (the palm) will be disregarded, and only the input from the smaller area (the stylus) will be registered.
The Satement for the Backend Logic is: 'IF THERE ARE MULTIPLE AREAS GIVING INPUT TO THE SCREEN, TAKE THE INPUT ONLY FROM THE SMALLEST ONE BY USING A THRESHOLD VALUE OF AREA'

# Installtion
Follow the all process of installing Flutter SDK mentioned in Official Docs: https://docs.flutter.dev/
then use the main.dart code provided in the repo.
