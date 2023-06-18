- https://github.com/conventional-changelog/standard-version
- 더이상 사용되지 않음

### 사용 방법
1. `npm i --save-dev standard-version` 으로 패키지 설치
2. package.json에 다음 코드 추가
```
{
  "scripts": {
    "release": "standard-version"
  }
}
```
3. .versionrc 구성
    - https://github.com/conventional-changelog/conventional-changelog-config-spec/ 참고
4. 첫번째 릴리즈 변경로그 생성
```
npm run release -- --first-release
```
5. 이후 릴리즈 할 경우 npm run release 입력시 자동으로 버전업 및 태그 생성