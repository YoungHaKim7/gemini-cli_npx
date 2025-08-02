# gemini-cli_npx
https://github.com/google-gemini/gemini-cli


# Install
- Prerequisites: Ensure you have Node.js version 20 or higher installed.
- Run the CLI: Execute the following command in your terminal:

```bash
npx https://github.com/google-gemini/gemini-cli
```

# Update

```sh
$ npm config get cache

$ rm -rf /Users/my_name/.npm/_npx

# version 체크 아마 삭제 되서 안 나옴.
$ gemini --version

# 다시 설치
$ npx https://github.com/google-gemini/gemini-cli

$ npx @google/gemini-cli --version

```

# npm 설치시 npm으로 지워야함

```
# 삭제
npm uninstall -g @google/gemini-cli

# 다시 설치
npm install -g @google/gemini-cli
```

# node.js 업데이트(3개의 명령어)
- node.js 업데이트 (3개의 명령어를 차례차례 입력하세요.)
  - https://kimce.tistory.com/11

```bash
sudo npm cache clean --force
sudo npm install -g n
sudo n stable
```

-
```bash
sudo n stable
  installing : node-v22.17.0
       mkdir : /usr/local/n/versions/node/22.17.0
       fetch : https://nodejs.org/dist/v22.17.0/node-v22.17.0-linux-x64.tar.xz
     copying : node/22.17.0
   installed : v22.17.0 (with npm 10.9.2)

Note: the node command changed location and the old location may be remembered in your current shell.
         old : /usr/bin/node
         new : /usr/local/bin/node
If "node --version" shows the old version then start a new shell, or reset the location hash with:
hash -r  (for bash, zsh, ash, dash, and ksh)
rehash   (for csh and tcsh)
```
