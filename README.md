# sav.com

bot scenario based on botreck to login make a screnshoot, get a list of domains, invoices


scenarios for botreck: got sav.com , login,get history, get domains, ..

### Add to file: apifork.txt

https://github.com/botreck/sav sav

```bash
echo "https://github.com/botreck/sav sav" >> apifork.txt
```

and install in project

```bash
./apifork install
```

start using

```bash
./apidsl 'puppeteer.csv("sav.com/login_user_screenshot.csv")'
```