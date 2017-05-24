import RPi.GPIO as GPIO
import time

GPIO.setmode(GPIO.BCM)

GPIO.setup(18, GPIO.IN, pull_up_down=GPIO.PUD_UP)
GPIO.setup(21, GPIO.IN, pull_up_down=GPIO.PUD_UP)
GPIO.setup(24, GPIO.IN, pull_up_down=GPIO.PUD_UP)
GPIO.setup(23, GPIO.IN, pull_up_down=GPIO.PUD_UP)
while True:
    input_state = GPIO.input(18)
    if input_state == False:
        print('a')
        time.sleep(0.2)
    input_state = GPIO.input(21)
    if input_state == False:
        print('b')
        time.sleep(0.2)
    input_state = GPIO.input(24)
    if input_state == False:
        print('c')
        time.sleep(0.2)

    input_state = GPIO.input(23)
    if input_state == False:
        print('d')
        time.sleep(0.2)
