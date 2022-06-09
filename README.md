# go-qq-tea
又一个给go用的qq-tea轮子呢（摊手

# 简介
以<http://bbs.chinaunix.net/thread-583468-1-1.html>为基础改写过来

# API
```golang
type teaCipher struct
NewTeaCipher([]byte) *teaCipher
(*teaCipher) Encrypt([]byte) []byte
(*teaCipher) Decrypt([]byte) []byte
```