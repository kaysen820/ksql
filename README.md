# Ksql
Ksql is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers.Using mutiple threads to scaning<br>

------

## Screenshots
```
python ksql.py -u "http://localhost/test/test.php?id=1&name=kaysen" --current-user
```
<br>

![ksql](./screenshots/ksql_20170314.png)


## Installation
You can download the latest tarball by clicking [here](https://github.com/kaysen820/ksql/tarball/master) or latest zipball by clicking [here](https://github.com/kaysen820/ksql/zipball/master).<br>
Preferably, you can download ksql by cloning the Git repository:<br>
```
git clone --depth 1 https://github.com/kaysen820/ksql ksql-dev
```
ksql works out of the box with Python version 2.6.x and 2.7.x on any platform.


## Usage
To get a list of basic options and switches use:<br>
```
python ksql.py -h
```

## Blind SQL injection
- [x] Boolean-based blind SQL injection
- [ ] Time-based blind SQL injection
- [ ] Error-based SQL injection
- [ ] UNION query SQL injection
- [ ] Stacked queries SQL injection

