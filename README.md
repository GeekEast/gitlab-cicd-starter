## Setup
- Install `npm install -g gatsby-cli`
- Create `gatsby new zengeast-blog && cd zengeast-blog`
- Develop `gatsby develop`
- Commit & Push 
```sh
git add -A
git commit -m 'commit'
git remote add origin git@gitlab.com:sx8807654/zengeast-blog.git
git push -u origin --all
```
- Build `gatsby build`





## Bugs
> zsh: command not found: gatsby
```sh
npm config delete prefix
npm config set prefix /usr/local
npm i -g gatsby-cli
```

## Reference
[Predefined Environment Variables](https://docs.gitlab.com/ee/ci/variables/predefined_variables.html)