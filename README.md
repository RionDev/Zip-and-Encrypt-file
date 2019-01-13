# Zip-and-Encrypt-file
Explanation
---
After compressing the file in the ZIP format, encrypt the file in AES mode. The key to be used for AES is converted to 128bit through MD5. After compressing the file, encrypt the file, and decrypt it after decoding. If the password is uncompressed in the wrong state, it will not work properly.

Dependency
---
Developed in C++/MFC for Visual Studio 2017 in windows 10 environment, used OPENSSL

암호압축 프로그램
---

설명
---
ZIP형식으로 파일을 압축한 뒤에 AES방식으로 파일을 암호화 한다. AES에 사용할 키는 입력한 비밀번호를 MD5를 통하여 128bit로 변환하여 사용한다.
파일을 압축후에 암호화를 하며, 복호화를 한뒤에 암축해제를 한다. 비밀번호가 틀린상태로 압축을 풀면 제대로 풀리지 않는다.

의존성
---
windows 10환경, Visual Studio 2017에서 C++/MFC 및 OPENSSL을 사용했다.

