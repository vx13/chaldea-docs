# Requable

## Cert Install

You need to install reqable generated cert into system to decrypt https traffic. See [Reqable cert install](https://reqable.com/en-US/docs/getting-started/installation/#mobile).

## Target Https Request

It's the login request:

- JP:

```:no-line-numbers
https://game.fate-go.jp/login/top?_userId=xxxx
```

- NA:

```:no-line-numbers
https://game.fate-go.us/login/top?_userId=xxxx
```

- CN: where `line3-s2-ios-fate` may change, the key point is `_key=toplogin`

```:no-line-numbers
https://line3-s2-ios-fate.bilibiligame.net/rongame_beta//rgfate/60_1001/ac.php?_userId=xxxx&_key=toplogin
```

- TW: similar with CN, but its domain is `https://line3-s1-all.fate-go.com.tw`

Find the target request, switch to `Response -> Body`, ensure `Text` or `JSON` format, click copy button ot download button, then import it in Chaldea.
