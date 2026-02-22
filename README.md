### Test repo used by 

- [pub-src-github v2.x](https://github.com/jldec/pub-src-github/tree/master/test)  
  Tests are serialized since they modify git state and are not atomic  
  GitHub Actions uses test-branch

- [pub-src-github v3.x](https://github.com/jldec/pub-server-monorepo/tree/main/packages/pub-src-github/test)
  Parallel test jobs for different combinations of platform and node version use different branches  
