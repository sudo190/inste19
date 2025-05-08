# inste19
git clone https://github.com/sudo190/inste19.git 
cd inste19
curl -X GET "https://graph.instagram.com/v18.0/me?fields=id,username&access_token=$INSTA_ACCESS_TOKEN"
sudo apt install python3-venv
python3 -m venv venv 
source venv/bin/activate
python3 -m pip install -r requirements.txt
python3 inste19.py
or 
./inste19.sh
