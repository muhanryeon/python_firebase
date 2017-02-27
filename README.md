# python_firebase

**require interpreter**
- python-firebase ver 1.2

```
#Firebase console 계정 write
firebase_url = 'Your firebase realtime DB url'
fb = firebase.FirebaseApplication(firebase_url, None)

fb.post('/item', {'title': '1234','content':'456'})
```

(Reference http://ozgur.github.io/python-firebase/)
