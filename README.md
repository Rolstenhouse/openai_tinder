# openai_tinder

1. `virtualenv env`
2.  Create `config.py` folder with appropriate credentials for 
```
fb_username = ""
fb_password = ""
fb_access_token = fb_auth_token.get_fb_access_token(fb_username, fb_password)
fb_user_id = fb_auth_token.get_fb_id(fb_access_token)
openai_key = ""
host = 'https://api.gotinder.com'
```
3.  `python sample.py`
