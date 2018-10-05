## A Blog Platform Implemented by Flask

This is a personal Blog platform that implemented by Flask web framework. It has some features of a blog like loggin, logout, follow, permission control, avatar, etc. It also has a azure blue theme.

The blog hasn't been completed yet. I will add more functionalities in the future.

Todo:

- [x] Tags.
- [x] Api.
- [ ] Third party login.
- [x] Search.

---
Simple Usage:
1. Use the `pipenv install` or `pip install -r requirements.txt` command to install the dependencies.
2. Add a environment variable named `FLASK_APP` which value is equal to this blog's directory path.
3. Execute the `flask create` command in your command line environment.

---
Generate Fake Data:
1. Once you done the above work, you can use `flask fake_user`, `flask fake_post`, `flask fake_comment` to generate the fake data to test.