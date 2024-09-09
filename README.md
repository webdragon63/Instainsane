# InstaInsane v1.0
 
Instainsane is an Shell Script to perform multi-threaded brute force attack against Instagram, this script can bypass login limiting and it can test infinite number of passwords with a rate of about 1000 passwords/min with 100 attemps at once.

## Legal disclaimer:
Usage of InstaInsane for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 
## Tool Interface
![Screenshot at 2024-09-08 18-30-35](https://github.com/user-attachments/assets/1e9a5a9b-3813-449a-8609-b4457550c258)
## After finding a password
![Screenshot at 2024-09-08 20-49-48](https://github.com/user-attachments/assets/c0f4c255-8053-4a27-bb11-7e413940c22a)

### Features
- Multi-thread (100 attempts at once)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Installation:
```
git clone https://github.com/webdragon63/Instainsane
cd instainsane
```
### Usage 
```
bash install.sh
sudo bash instainsane.sh
```

### In install.sh it will install these requirements
### Curl, Tor, Openssl


### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR instances to avoid blocking. 
The script uses Instagram-py algorithm (Python).
