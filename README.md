# csn-150-final-project

This is how to install Phoneinfoga in linux command line

step one

copy this command with the link and paste it in the command command line

curl -sSL https://raw.githubusercontent.com/sundowndev/phoneinfoga/master/support/scripts/install | bash

step two

check the version by copying this command and then paste it on the command line

./phoneinfoga version

step three

you will need to copy and this this command as well

sudo mv ./phoneinfoga /usr/bin/phoneinfoga

after you are done you can use phoneinfoga like this

type phoneinfoga followed by scan -n and then the phone number with its country code and press enter, for example

phoneinfoga scan -n 13526006900

this would show you many links that should provide you with info about the number like social media and more followed the following text

Results for local
Raw local: 3526006900                                                        
Local: (352) 600-6900                                                        
E164: +13526006900                                                           
International: 13526006900                                                   
Country: US   

I tried everything I could to find out why these links don't provide any usefull info but I couldn't resolve it.

for a GUI version type the following phoneinfoga serve -p after the -p the port number you can and the default port for this would port 5000 and I'll use port 8080 for this exmaple

phoneinfoga serve -p 8080

then you go to your browser and type https://localhost:port number

substitude the localhost part with your local host ip, it might be 127.0.0.1 and the port number part will be the port number you chose.
example

https://127.0.0.1:8080

and that would show you the HUI version of the results you get from the command line
