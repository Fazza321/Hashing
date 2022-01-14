correctHash = 'bc2aa993f3552bd3e152e0fa5e3e136af56751dc319e0a9e87f209e621832b37'

inputtedPassword = input('Enter Your Password: ')

if correctHash != sha256(inputtedPassword.encode('utf-8')).hexdigest():
  print('Wrong')
else:
  print('Correct')
  screen = pygame.display.set_mode((0, 0), pygame.FULLSCREEN)
  Menu()
