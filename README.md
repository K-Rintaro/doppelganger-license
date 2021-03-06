# doppelganger-license
<img src="https://img.shields.io/npm/v/doppelganger-license?style=for-the-badge"/>   <img src="https://img.shields.io/npm/dt/doppelganger-license?style=for-the-badge" /> <img src="https://img.shields.io/travis/K-Rintaro/doppelganger-license/main?style=for-the-badge"> <img src="https://img.shields.io/npm/l/doppelganger-license?color=FFC0CB&style=for-the-badge" />

[![NPM](https://nodei.co/npm/doppelganger-license.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/doppelganger-license/)

License violation is over.

## DEMO
[![doppelganger-license DEMO](https://user-images.githubusercontent.com/70018855/100538396-e71c8a80-3272-11eb-942e-7e4064f5db4d.png)](http://www.youtube.com/watch?v=L5CKBMd6sWE "doppelganger-license DEMO")

## What is this?
doppelganger-license is npm package.

 You can check what you have to do for dependencies(only npm)' licenses.

For example,
```
©︎2020 Rintaro Kobayashi - doppelganger-license

‼CAUTION: 1.doppelganger-license cannot consider about contradiction of license. 
          2.Please choose license by yourself if you need to do dual-licensing.   

ALL YOU NEED TO DO IS: 
------------------------------------------------------------ 
⛓Add dependencies.txt in your software.
```

### <u>doppelganger-license can make to-do list automatically.</u>

Also, __doppelganger-license can gather all license terms into one text file.__

These features are based on <u>package-lock.json</u>.

## What should I do?

**First**, please install doppelganger-license.
```
$ npm install doppelganger-license
```

**Second**, make <u>"memo.txt"</u> & <u>"dependencies.txt"</u> wherever you like.

doppelganger-license writes that "ALL YOU NEED TO DO IS" to memo.txt and writing dependencies' licenses to dependencies.txt

**Third**, enter this command.
```
$ doppelganger-license
```

**Four**, please enter the path of package-lock.json, memo.txt & dependencies.txt.

When you finish these procedure, you can see "ALL YOU NEED TO IS" in memo.txt.

##  Disclaimer
doppelganger-license is just a simple tool that can check licenses.
<u>__doppelganger-license is not a complete open source license compliance solution.__</u>
Some licenses are not supported. doppelganger-license is not a substitute for human review of each dependency for licensing or any other issues. It is not the goal of doppelganger-license to provide <u>legal advice</u> about licensing or any other issues. Please note that I shall not be responsible for any loss, damages and troubles.

## LICENSE
doppelganger-license is licensed under the MIT license.
