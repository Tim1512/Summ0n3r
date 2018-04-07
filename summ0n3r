#!/usr/bin/python
# -*- coding: utf-8 -*- 
from subprocess import call
import os, re
from insides import *
import colorama
from colorama import Fore, Back, Style
import argparse
import sys
################################  Banner   ################################

os.system('clear') 
print(Banner)
sys.stdout.write("\x1b[8;{rows};{cols}t".format(rows=31, cols=130))

parser = argparse.ArgumentParser()
parser._optionals.title ="Tools List"
parser.add_argument("-1", "--crawlbox", help="CrawlBox - Easy way to bruteforce directory.", action="store_true")
parser.add_argument("-2", "--serenity", help="53R3N17Y - Python based script for Information Gathering.", action="store_true")
parser.add_argument("-3", "--trackout", help="TrackOut - Python IP Tracker.", action="store_true")
parser.add_argument("-4", "--wpscan", help="WPScan - Black box WordPress vulnerability Scanner.", action="store_true")
parser.add_argument("-5", "--subover", help="Sub0ver - Hostile Subdomain Takeover Tool.", action="store_true")
parser.add_argument("-6", "--joomscan", help="JoomScan - Detect and analysis Joomla CMS Vulnerability", action="store_true")
parser.add_argument("-7", "--xbruteforcer", help="XBruteForcer - Brute Force Tool.", action="store_true")
parser.add_argument("-8", "--findsploit", help="Findsploit - Find Exploits In Local And Online Databases.", action="store_true")
parser.add_argument("-9", "--sqlmap", help="SQLMap - Automatic SQL injection and database takeover tool.", action="store_true")
parser.add_argument("-10", "--cupp", help="CUPP - Common User Passwords Profiler.", action="store_true")
parser.add_argument("-11", "--weevely", help="Weevely - Weaponized web shell.", action="store_true")

args = parser.parse_args()
if args.crawlbox:
    call(["git", "clone", "https://github.com/abaykan/CrawlBox.git"])
elif args.serenity:
    call(["git", "clone", "https://github.com/abaykan/53R3N17Y.git"])
elif args.wpscan:
    call(["git", "clone", "https://github.com/wpscanteam/wpscan.git"])
elif args.subover:
    call(["git", "clone", "https://github.com/Ice3man543/SubOver.git"])
elif args.joomscan:
    call(["git", "clone", "https://github.com/rezasp/joomscan.git"])
elif args.xbruteforcer:
    call(["git", "clone", "https://github.com/Moham3dRiahi/XBruteForcer.git"])
elif args.findsploit:
    call(["git", "clone", "https://github.com/1N3/Findsploit.git"])
elif args.sqlmap:
    call(["git", "clone", "--depth", "1", "https://github.com/sqlmapproject/sqlmap.git"])
elif args.cupp:
    call(["git", "clone", "https://github.com/Mebus/cupp.git"])
elif args.weevely:
    call(["git", "clone", "https://github.com/epinna/weevely3.git"])
