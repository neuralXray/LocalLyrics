# LocalLyrics
Lyrics plugin for Rhythmbox, display local lyrics files.

### Dependencies
`pylrc`

### Installation
Copy `LocalLyrics.py` and `LocalLyrics.plugin` files into the folder `~/Home/.local/share/rythmbox/plugins`.

### Fork updates

* Timeout of 1 second when updating the lyrics. The original project didn't include any delay and consumes a lot of resources.
* Recognize dark and light themes and set the lyric colors to yellow or black accordingly (at least in Linux Mint Xfce).

Installation commands:

```
cd ~/.local/share/rhythmbox/plugins
git clone https://github.com/neuralXray/LocalLyrics.git
cd LocalLyrics
git clone https://github.com/doakey3/pylrc.git
```

#### Support the fork developer

* Bitcoin: 1GDDJ7sLcBwFXg978qzCdsxrC8Ci9Dbgfa
* Monero: 4BGpHVqEWBtNwhwE2FECSt6vpuDMbLzrCFSUJHX5sPG44bZQYK1vN8MM97CbyC9ejSHpJANpJSLpxVrLQ2XT6xEXR8pzdCT
* Litecoin: LdaMXYuayfQmEQ4wsgR2Tp6om78caG3TEG
* Ethereum: 0x7862D03Dd9Dd5F1ebc020B2AaBd107d872ebA58E
* PayPal: paypal.me/neuralXray
