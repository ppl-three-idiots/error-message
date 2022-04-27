## vue error messagee

### vue cli 설치 오류

```
npm install -g @vue/cli
```

해당 명령어를 쳤을 때 permission 에러가 뜨면, 두 가지 해결 방법이 있다.

```
npm install -g yarn
yarn global add @vue/cli
```

```
sudo npm install -g @vue/cli
```

해당 에러는 설치하려는 폴더에 쓰기 권한이 없기 때문에 발생하는 에러이므로, 관리자 권한을 줘서 해결할 수 있다.
