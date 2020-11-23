# doppelganger-license
License violation is over.

## What is this?
doppelganger-license is npm package.

 You can check what you have to do for dependencies(only npm)' licenses.

For example,
```
©︎2020 Rintaro Kobayashi - doppelganger-license

‼CAUTION: 1.doppelganger-license cannot consider about contradiction of license. 
          2.Please choose license by yourself if you need to do dual-licensing.   

ALL YOU NEED TO IS: 
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

doppelganger-license writes that "ALL YOU NEED TO IS" to memo.txt and writing dependencies' licenses to dependencies.txt

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