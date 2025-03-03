import pyautogui 
import time

#sleeptime for mouse movement
time.sleep(9)

currentMouseX, currentMouseY = pyautogui.position()
print(f"Current mouse position: X={currentMouseX}, Y={currentMouseY}")

#Move mouse code
pyautogui.moveTo(348, 787)

time.sleep(7)
#Click code 
pyautogui.click(348, 787) 

#typescript in Safari
pyautogui.typewrite('https://www.youtube.com', interval=0.45)
#press enter to search
pyautogui.press('enter')

#-------------------------------

#time.sleep(4)
#Mouse cordiantes for search engine

currentMouseX, currentMouseY = pyautogui.position()
print(f"Current mouse position: X={currentMouseX}, Y={currentMouseY}")

#Click to search engine
pyautogui.moveTo(305,93)
pyautogui.click(294,87)

time.sleep(2)
#search for video
pyautogui.typewrite('Nathaniel Bassey', interval=0.55)
pyautogui.press('enter')

time.sleep(6)
currentMouseX, currentMouseY = pyautogui.position()
print(f"Current mouse position: X={currentMouseX}, Y={currentMouseY}")

#click video to play
time.sleep(4)
pyautogui.moveTo(225,478)
pyautogui.click(225,478)
#time.sleep(6)

#CREATED AND DEVELOPED BY Azane Azariah Kofi.
