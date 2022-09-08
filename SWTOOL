import json
import os
import random
import subprocess
import sys
import time
from os import system
from shutil import which
from urllib import parse

try:
    import colorama
    import httpx
    import requests
    import speedtest
except Exception as e:
    sys.exit(e)


class Color:
    colorama.init(autoreset=True)
    LB = colorama.Fore.LIGHTBLUE_EX
    LC = colorama.Fore.LIGHTCYAN_EX
    LG = colorama.Fore.LIGHTGREEN_EX
    LR = colorama.Fore.LIGHTRED_EX
    LY = colorama.Fore.LIGHTYELLOW_EX
    RESET = colorama.Fore.RESET


class Home:
    def __init__(self,
                 help,
                 contact):
        self.help = help
        self.contact = contact

    def styleText(self, text):
        for animation in text:
            sys.stdout.write(animation)
            sys.stdout.flush()
            if animation != ".":
                time.sleep(0.01)
            else:
                time.sleep(1)

    def home(self):
        print(f"""{Color.LG}
SW DDOS TOOL
   
""")
        print(Color.LR+"<"+Color.LG+"S1"+Color.LR+">"+Color.LC+" SYN FLOOD")
